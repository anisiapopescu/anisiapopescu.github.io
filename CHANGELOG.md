# Changelog

## 2026-10-12 — Independent refinement draft

All changes were performed on a local copy of the user-provided repository ZIP. No remote repository was changed.

### Repository organization
- Moved 32 root-level image, PDF, and video assets into purpose-based directories.
- Updated local Markdown/HTML references and project figures to Jekyll `relative_url` paths for portability.
- Preserved the bytes of every relocated asset; no image/PDF content was altered.
- Retained the existing theme assets, layouts, and project page filenames.
- Public URLs for relocated files will change unless compatibility redirects or aliases are introduced. Existing external bookmarks require review.

### Navigation
- Reordered the menu to Home, Publications, Projects, Teaching, CV in `_config.yml`.
- Added direct CV PDF navigation and new-tab handling in `_includes/menu.html` and `_includes/sidebar.html`.
- This is a small Jekyll configuration change; no dependency or plugin changes.

### Projects
- Created `projects.md` with four cards, using original project titles and descriptions, existing images, and links to existing pages.
- Repaired invalid front matter in `test.md` and kept its original project-list content for reference.
- Added `_sass/refinement.sass` for responsive card layout and media alignment.
- Imported the stylesheet from the existing Sass entrypoints `assets/css/frame.sass` and `assets/css/index.sass`.
- No new framework, JavaScript, gems, or build system.

### Home and project presentation
- Replaced inline flex styles with shared `.research-media` styling in existing pages.
- Replaced generic image alt text with a neutral description; project-card thumbnails use empty alt text because their adjacent text describes the linked project.
- No academic descriptions or bibliography entries were rewritten.

### Technical notes and unresolved issues
- No Ruby, Bundler, Jekyll, or gem upgrades.
- No Jekyll build or browser preview could be completed in this environment.
- Temporary GitHub Pages project-site baseurl requires deployment verification.
- Existing publication and teaching content preserved without substantive changes.
- Original PDF/image URLs are not automatically redirected after relocation.
- Image alternative text on individual research figures should be reviewed and made more specific with author input.

### File relocation map

| Original root-level path | New path |
|---|---|
| `ANISIA POPESCU_CVFR_Fev2024.pdf` | `assets/documents/cv/ANISIA POPESCU_CVFR_Fev2024.pdf` |
| `ASA_F3_poster.pdf` | `assets/documents/publications/ASA_F3_poster.pdf` |
| `Anisia Popescu_CVEN_FEV24.pdf` | `assets/documents/cv/Anisia Popescu_CVEN_FEV24.pdf` |
| `AnisiaPopescu_CVEN_JAN2025.pdf` | `assets/documents/cv/AnisiaPopescu_CVEN_JAN2025.pdf` |
| `CLS54_Proceedings.pdf` | `assets/documents/publications/CLS54_Proceedings.pdf` |
| `FEDEPA_Newsletter_Camp.pdf` | `assets/documents/publications/FEDEPA_Newsletter_Camp.pdf` |
| `LabPhon18_Paper123.mp4` | `assets/documents/publications/LabPhon18_Paper123.mp4` |
| `PoA_dev.jpg` | `assets/images/projects/PoA_dev.jpg` |
| `PoA_dev.png` | `assets/images/projects/PoA_dev.png` |
| `Popescu&Chitoran_ISSP2024.pdf` | `assets/documents/publications/Popescu&Chitoran_ISSP2024.pdf` |
| `Popescu_Lamel_Vasilescu_ICNLSP2023.pdf` | `assets/documents/publications/Popescu_Lamel_Vasilescu_ICNLSP2023.pdf` |
| `Popescu_etal2022_Labphon18.pdf` | `assets/documents/publications/Popescu_etal2022_Labphon18.pdf` |
| `Popescu_etal_ICPhS2023.pdf` | `assets/documents/publications/Popescu_etal_ICPhS2023.pdf` |
| `Popescu_etal_ISSP2024.pdf` | `assets/documents/publications/Popescu_etal_ISSP2024.pdf` |
| `ROI_site.png` | `assets/images/projects/ROI_site.png` |
| `Refereed_Conference_Presentations.pdf` | `assets/documents/publications/Refereed_Conference_Presentations.pdf` |
| `cavar_site.jpg` | `assets/images/projects/cavar_site.jpg` |
| `cavar_site.png` | `assets/images/projects/cavar_site.png` |
| `cleardark.png` | `assets/images/projects/cleardark.png` |
| `contour.jpg` | `assets/images/projects/contour.jpg` |
| `contour.png` | `assets/images/projects/contour.png` |
| `coord.jpg` | `assets/images/projects/coord.jpg` |
| `coord.png` | `assets/images/projects/coord.png` |
| `fig_site.jpg` | `assets/images/projects/fig_site.jpg` |
| `img.jpeg` | `assets/images/projects/img.jpeg` |
| `img_site.jpg` | `assets/images/projects/img_site.jpg` |
| `logo_FCoda.png` | `assets/images/projects/logo_FCoda.png` |
| `poster.jpg` | `assets/images/profile/poster.jpg` |
| `poza.jpg` | `assets/images/profile/poza.jpg` |
| `sequi_site.jpg` | `assets/images/projects/sequi_site.jpg` |
| `sequi_site.png` | `assets/images/projects/sequi_site.png` |
| `sesqui.jpg` | `assets/images/projects/sesqui.jpg` |
