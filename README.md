# odunayoakinlade.github.io

Personal website of Odunayo Akinlade, live at https://odunayoakinlade.github.io.

Built with Jekyll using the [AcademicPages](https://github.com/academicpages/academicpages.github.io) template (a fork of [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/)).

## Where to edit

| What | File / folder |
| --- | --- |
| Name, bio, sidebar links | `_config.yml` (the `author:` section) |
| Profile photo | `images/profile.png` |
| Homepage & news | `_pages/about.md` |
| Top navigation | `_data/navigation.yml` |
| Experience | `_experience/` (one `.md` per role) |
| Projects | `_projects/` (one `.md` per project) |
| Publications | `_publications/` (one `.md` per paper) |
| Misc | `_misc/` |
| PDFs (CV, papers) | `files/` → served at `/files/<name>.pdf` |

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Deploy

Push to the `master` branch. In the repo's **Settings → Pages**, set the source to "Deploy from a branch", `master`, `/ (root)`.
