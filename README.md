# dlaconte.github.io

Personal portfolio site, served at [dominiclaconte.com](https://dominiclaconte.com) by GitHub Pages (Jekyll).

## Common edits

| To change | Edit |
| --- | --- |
| Email, LinkedIn, resume link | `_config.yml` |
| About me text | `_includes/about.md` |
| Intro line under your name | `index.html` (top) |
| CAD/CAM gallery | `_data/cad_cam.yml` + images in `assets/img/cad-cam/` |
| A project's write-up | `_projects/<name>.md` |
| Colors, fonts, spacing | `assets/css/style.css` (variables at the top) |

## Adding the resume

1. Put the PDF at `assets/resume.pdf`.
2. In `_config.yml`, set `resume: /assets/resume.pdf`.

## Adding a project

1. Copy an existing file in `_projects/` (e.g. `carbon-tray.md`) to `_projects/<new-name>.md`.
2. Put its photos in `assets/img/projects/<new-name>/`.
3. Edit the front matter at the top (title, summary, order, hero image, facts) and the write-up below it.

`order` sets the position in the grid (1 = first). Set `draft: true` to hide a project without deleting it.

## Previewing locally

```
gem install jekyll
jekyll serve
```

Then open http://localhost:4000.
