# Yuda Wu (武昱达) — Personal Academic Homepage

Source code of my personal academic homepage, built with the
[al-folio](https://github.com/alshedivat/al-folio) Jekyll theme and hosted for free on
GitHub Pages at <https://wuyudapku.github.io>.

## Structure

| Path                            | Purpose                                               |
| ------------------------------- | ----------------------------------------------------- |
| `_pages/about.md`               | Homepage bio, profile photo, news, latest posts       |
| `_pages/cv.md` + `_data/cv.yml` | CV page (education, awards, skills)                   |
| `_posts/`                       | Blog posts (Markdown, filename `YYYY-MM-DD-title.md`) |
| `_news/`                        | Short news announcements on the homepage              |
| `_projects/`                    | Project portfolio pages                               |
| `_bibliography/papers.bib`      | Publications in BibTeX                                |
| `assets/img/prof_pic.jpg`       | Profile photo (replace with your own)                 |

## Local development (optional)

The site builds automatically on GitHub Actions — you normally just edit Markdown
and push. To preview locally you need Ruby, then run `bin/bootstrap` and `bundle exec jekyll serve`.
