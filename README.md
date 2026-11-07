# pknandi.github.io

Source for the personal academic website of **Pranjal Kumar Nandi**: <https://pknandi.github.io>

Machine learning engineer and researcher working on multimodal learning, vision–language models, and edge intelligence.

## Contents

| Path                                            | What it holds                     |
| ----------------------------------------------- | --------------------------------- |
| `_pages/about.md`                               | Homepage bio                      |
| `_bibliography/papers.bib`                      | Publications and patents          |
| `_projects/`                                    | Project pages                     |
| `_news/`                                        | News items shown on the homepage  |
| `_data/cv.yml`                                  | Data for the CV page              |
| `assets/pdf/Pranjal_Kumar_Nandi_CV.pdf`         | Downloadable CV                   |
| `assets/img/publication_preview/`               | Publication and project figures   |

## Run locally

Requires Ruby 3.x and ImageMagick (`brew install ruby imagemagick` on macOS).

```bash
bundle install
bundle exec jekyll serve --livereload   # http://localhost:4000/
```

## Credits

Built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (MIT License, see [`LICENSE`](LICENSE)).
