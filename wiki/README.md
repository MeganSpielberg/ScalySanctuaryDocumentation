# Scaly Sanctuary Research and Project Documentation

This is an [MkDocs](https://www.mkdocs.org/) site (using the [Ivory](https://github.com/karlborn/mkdocs-ivory) theme) generated from the project's Confluence space export.

## Running locally

1. Create and activate a virtual environment (optional, but recommended):

   ```bash
   python -m venv .venv
   # Windows
   .venv\Scripts\activate
   # macOS/Linux
   source .venv/bin/activate
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. From the `wiki/` directory, start the live-reloading dev server:

   ```bash
   mkdocs serve
   ```

   Then open <http://127.0.0.1:8000> in your browser. The site reloads automatically when you edit a file under `docs/`.

4. To produce a static build (output goes to `site/`, which is git-ignored):

   ```bash
   mkdocs build --strict
   ```

   `--strict` fails the build on broken internal links or missing pages, which is useful for catching mistakes before publishing.

## Structure

- `docs/` — page content in Markdown, plus `docs/images/` for embedded images and PDF attachments.
- `mkdocs.yml` — site config and navigation tree.
- `requirements.txt` — Python packages needed to build/serve the site (`mkdocs`, `mkdocs-ivory`).
- `overrides/nav.html` — overrides the Ivory theme's nav template to drop the per-page table-of-contents links it would otherwise inject into the sidebar, so the left nav only lists pages, not their subsections.

Note: a handful of GIFs embedded in the devlog pages (e.g. `1212439.md`) are linked from temporary, signed S3 URLs from the original Confluence export and have since expired upstream — those images can't be recovered from this repo and would need to be re-attached from their original source.
