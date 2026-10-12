# Anisia Popescu — refined academic website

This is an independent refinement of the existing Jekyll / Contrast-theme website. It is intended for review in a separate repository before any final migration.

## Structure

- `index.md`: homepage and academic biography.
- `publications.md`: existing bibliography.
- `projects.md`: image-based project overview.
- `liquids.md`, `TAL.md`, `acquisition.md`, `foundation.md`: existing dedicated project pages.
- `teaching.md`: teaching activities.
- `assets/images/profile/`: profile imagery.
- `assets/images/projects/`: research figures and project card images.
- `assets/documents/cv/`: all existing CV versions.
- `assets/documents/publications/`: publication PDFs and presentation video.
- `_sass/refinement.sass`: site-specific CSS using the original theme's Sass pipeline.
- `_layouts/`, `_includes/`, `_sass/`, `assets/css/`: existing Contrast theme components.

## Updating content

**Publication:** edit `publications.md` and add a PDF to `assets/documents/publications/` if needed. Link using `{{ "/assets/documents/publications/FILENAME.pdf" | relative_url }}`.

**Project:** add the project page as Markdown with `layout: page`, then add a matching card in `projects.md`; place its representative image in `assets/images/projects/`. Follow the existing card markup. Keep the page URL stable.

**Teaching:** edit `teaching.md`; put any new course documents in `assets/documents/teaching/` (create this folder when first needed).

**CV:** replace `assets/documents/cv/AnisiaPopescu_CVEN_JAN2025.pdf` with the updated PDF, retaining that filename. The header CV link and homepage link then keep working.

## Preview and deployment

The original `Gemfile` and Jekyll theme remain unchanged. Do not upgrade dependencies to preview this project.

If the existing Ruby/Jekyll environment is available, run `bundle exec jekyll serve --baseurl ""` for a local root-site preview, using the existing dependency setup. No gems were installed as part of this refinement.

For a temporary GitHub Pages project site named `personal-website-refined`, its URL is normally `/personal-website-refined/` under the account's domain. Set `baseurl: "/personal-website-refined"` in the temporary repository's Pages/Jekyll configuration **only if required by the deployment setup**; verify this before publishing. For the final root site, use an empty baseurl. Do not attach the existing custom domain to the temporary repository.

**Important:** the current files have not been successfully built in this environment, because Ruby/Jekyll executables were unavailable. Review `VALIDATION.md` before deployment. The original repository must not be modified during preview.
