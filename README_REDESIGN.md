# Lateef Adeleke website redesign

This package contains the proposed research-portfolio redesign for `lateefadeleke.github.io`.

## Files added/replaced
- `_config.yml`
- `_layouts/default.html`
- `assets/css/style.css`
- `index.md`
- `research.md`
- `projects.md` (new)
- `publications.md`
- `fieldwork.md` (new)
- `cv.md`

The existing files in `assets/img/` and `cv/Lateef_cv.pdf` are intentionally reused and are not duplicated here.

## Recommended Git workflow
```bash
git checkout main
git pull origin main
git checkout -b redesign-research-portfolio

# Copy the files in this package into the repository root, preserving directories.

git add _config.yml _layouts/default.html assets/css/style.css index.md research.md projects.md publications.md fieldwork.md cv.md
git commit -m "Redesign academic website as research portfolio"
git push -u origin redesign-research-portfolio
```

Then open a pull request from `redesign-research-portfolio` into `main`.

## Review checklist before merge
1. Verify the preferred email address in `_config.yml` and `_layouts/default.html`.
2. Verify the current CV exists at `/cv/Lateef_cv.pdf`.
3. Add stable Hugging Face dataset/model links to `projects.md` when desired.
4. Verify all publication metadata against the current CV/Scholar record.
5. Preview with GitHub Pages or locally with Jekyll before merging.
