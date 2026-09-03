# HUMANITAS @ CLEF — website source

Jekyll site for GitHub Pages, written entirely in Markdown. It uses the `minima` theme, which renders the section links in the top-right corner of the header.

## Files

| File | Content |
| --- | --- |
| `_config.yml` | Site settings and navigation order |
| `index.md` | Landing page |
| `scope.md` | Scope, evaluation dimensions, motivation |
| `programme.md` | Session structure and invited speakers |
| `organisers.md` | Organising team, steering and programme committees |
| `participate.md` | Audience, contributions, dates, registration |
| `resources.md` | Infrastructures, collections, related initiatives |
| `contact.md` | Contact details |
| `TODO-missing-information.md` | Working checklist, not published |

## Publishing

1. Create a repository, for example `humanitas-clef`, under the organisation or personal account that will own the site.
2. Copy these files to the root of the `main` branch.
3. In Settings › Pages, set the source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Edit `url` and `baseurl` in `_config.yml` to match the resulting address. If the repository is named `<account>.github.io`, leave `baseurl` empty; otherwise set it to `"/humanitas-clef"`.
5. Wait for the build to finish, then check the navigation links.

## Editing

Every page starts with a front-matter block between `---` markers. Keep `layout`, `title` and `permalink`; `title` is what appears in the navigation bar.

To add a page, create a new `.md` file with the same front matter and add its filename to `header_pages` in `_config.yml`, in the position where the link should appear.

Passages that still need input are marked with a blockquote beginning `> **To complete:**`. To find them all:

```
grep -rn "To complete" *.md
```

## Local preview (optional)

```
gem install bundler jekyll
bundle init
echo 'gem "github-pages", group: :jekyll_plugins' >> Gemfile
bundle install
bundle exec jekyll serve
```

## A note on styling

The request was for strict Markdown, so the site relies on the default `minima` theme. If a distinct visual identity is wanted later (custom colours, a header image, institutional logos), it can be added through a small `assets/css/style.scss` file without touching the Markdown content.
