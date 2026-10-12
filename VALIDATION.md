# Validation report — 2026-10-12

## Completed checks
- ZIP successfully extracted into an independent working directory.
- Original source file inventory: 162 files.
- Every original file has a corresponding path in the refined directory: PASS.
- Original files whose bytes are unchanged at their mapped path: 150/162.
- 32 binary assets relocated with their original contents unchanged.
- Exactly five navigation entries configured.
- Four project cards created and target existing dedicated Markdown pages.
- `Gemfile` unchanged: True.
- No original GitHub repository changes were made.

## Not yet verified
- Jekyll compilation, because Ruby/Bundler/Jekyll are not installed in this execution environment.
- GitHub Pages preview and temporary repository baseurl.
- Rendered appearance on desktop, tablet and mobile.
- HTTP availability of all external links.
- Full link crawl of rendered HTML and historical public URLs.
- Whether the current GitHub Pages deployment uses a separate Actions workflow.
- No remote repository or GitHub Pages deployment was created.

## Before publishing
1. Run the original Jekyll build without upgrading gems.
2. Configure the temporary project-site baseurl if necessary and verify generated links.
3. Test all five navigation entries, all four project pages, CV and PDFs.
4. Inspect mobile layouts, keyboard navigation, and figure alt text.
5. Check whether historical direct links to relocated PDFs require aliases.
6. Obtain approval before any changes to the original repository or final domain.
