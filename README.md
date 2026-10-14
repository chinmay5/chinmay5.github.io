# Chinmay Prabhakar — personal research website

This is a **static GitHub Pages** website. No Jekyll, JavaScript framework, build tool, paid hosting, or dependencies are necessary.

## Install (copy/paste)

1. Open your GitHub repository: https://github.com/chinmay5/chinmay5.github.io
2. Replace the existing root `index.html`, `style.css`, and `README.md` with the files in this package.
3. Create the folder `projects/vesseltok/` and put this package's `projects/vesseltok/index.html` inside it. GitHub's **Add file → Upload files** supports the entire folder structure if you drag the unzipped folder content, or you can use Git locally.
4. Keep your existing `assets/profile.png` and `assets/cv.pdf` in the repository. These files were **not supplied with this update**, so they are not included in the ZIP.
5. Commit to your GitHub Pages publishing branch (currently `main`, repository root). Wait for deployment.

Homepage: https://chinmay5.github.io/
VesselTok project: https://chinmay5.github.io/projects/vesseltok/

### Important: the images

This update uses *verified figure files from your own public GitHub research repositories*, with direct `https://raw.githubusercontent.com/...` image URLs, so no extra image files need uploading. They are:

- VesselTok: `chinmay5/vessel_tok/vesseltok_overview.png` (featured card + paper dropdown + project page)
- MICCAI 2025 graph generation: `chinmay5/semantically_consistent_graph_generation/static_resources/overview.png` (dropdown)
- MICCAI 2024 vessel diffusion: `chinmay5/vessel_diffuse/static_resources/main_fig.png` (dropdown)

If those research repositories are renamed, made private, or the images are moved, the previews will stop loading. For longer-term reliability, you may later download those same three images into `assets/papers/` of this site and replace the URLs in `index.html` and `projects/vesseltok/index.html` with local paths.

Only papers with a verified representative image are given a dropdown. The other publications remain text-only until you supply figures. This avoids publishing misleading figures.

## Local preview

Open `index.html` in a web browser. Click the **VesselTok** project button to open the project page. The figures require an internet connection because they are hosted on your public code repositories.

Optionally, from the website folder run `python -m http.server 8000`, and open `http://localhost:8000`.

## Editing publications

Publication cards are plain HTML in `index.html`. To add a paper figure, add a `<details class="paper-preview">` block to the relevant `<article class="publication">` following any existing preview. The expandable preview works without JavaScript.

## Project-page citations

The VesselTok citation is taken from the official code repository and should be checked against the final ECCV proceedings metadata when available.

## Existing content preserved

Your submitted Education, Industry Experience, and Service & Miscellaneous content and existing profile links remain in the new homepage. Your six listed papers are retained, and VesselTok / Sparse Representation Learning for Vessels are added. The figure URLs and other new paper links were checked against public author repositories and official paper pages.
