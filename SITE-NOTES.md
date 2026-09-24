# How this site is put together

Served by GitHub Pages at https://friederikequint.github.io

The six main pages use a custom layout, `_layouts/quint.html`, with its own
stylesheet at `assets/css/quint.css`. The AcademicPages theme files are still
here and still generate some legacy URLs under `/teaching/` and `/talks/`, so
do not delete them.

Page content lives in `_pages/`. Anything that repeats lives in `_data/` so it
is edited in one place.

| File | Holds |
| --- | --- |
| `_data/publications.yml` | Peer-reviewed articles and research reports |
| `_data/work_in_progress.yml` | Work in progress |
| `_data/talks.yml` | Invited talks, guest lectures and workshops |
| `_data/conferences.yml` | Conference presentations |
| `_data/teaching.yml` | Supervision, guest lectures, reviewing |
| `_data/reading.yml` | The "Off the clock" books block on the About page |
| `_data/quint_nav.yml` | Main navigation |
| `_data/quint_profile_links.yml` | Google Scholar, ORCID and the rest |

The header and the contact footer live in `_includes/quint/`.

`_data/cv.yml` is no longer read by anything, since the CV page became a
redirect to the PDF.

## Updating the CV

Overwrite `cv/Friederike-Quint-CV.pdf` and keep that file name. The CV button in
the header, the footer link and the `/cv/` redirect all point at that one path.

## Running it locally

    bundle install
    bundle exec jekyll serve

Then open http://localhost:4000
