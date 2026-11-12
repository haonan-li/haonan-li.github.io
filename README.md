# haonan-li.github.io

Source for [Haonan Li's personal website](https://haonan-li.github.io), built with Jekyll and the
[AcademicPages](https://github.com/academicpages/academicpages.github.io) template (a fork of
Minimal Mistakes; MIT License, see `LICENSE`). GitHub Pages builds and deploys the site on every push.

## Where things live

| What | File |
| --- | --- |
| Site settings, sidebar profile, social links | `_config.yml` |
| Home page: bio, highlights, selected publications, news | `_pages/about.md` |
| Older news | `_pages/about_old_news.md` |
| Publication list | `_pages/publications.md` |
| CV page / PDF | `_pages/cv.md`, `files/CV_Haonan_1page.pdf` |
| Photo, favicons, web manifest | `images/`, `favicon.ico` |
| Head tags (icons, CSS) | `_includes/head/custom.html` |

## Preview locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open http://localhost:4000.
