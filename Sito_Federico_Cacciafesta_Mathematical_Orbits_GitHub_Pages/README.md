# Federico Cacciafesta — academic website (preview)

A complete, responsive, static academic website, designed for GitHub Pages. No framework, database, build tools or paid hosting needed.

## Preview

Open `index.html` in a browser. The five pages (`index.html`, `research.html`, `publications.html`, `teaching.html`, `contact.html`) are linked and contain pre-rendered content even without JavaScript. Publication search, filters and responsive navigation require JavaScript; external paper links require an internet connection. An additional self-contained single-file navigation preview is delivered outside this folder.

## Deploy on GitHub Pages

1. Create a **public** repository named `<your-GitHub-username>.github.io` for a root site, or any repository name for a project site.
2. Upload the contents of this folder to the repository root.
3. In **Settings > Pages**, choose **Deploy from a branch**, then **main / (root)** (for a non-username repository).
4. Visit your GitHub Pages URL once published.

For updates: publication details live in `assets/data.js`, styling in `assets/style.css`, and page content / behavior in `assets/app.js`. No compilation required.

## Important review items before publication

- **CV:** A full English translation of the owner-provided LaTeX CV is now included in `assets/CV_Cacciafesta_EN.tex`, with a compiled PDF download at `assets/CV_Cacciafesta_EN.pdf`. The content and publication metadata were not independently fact-checked; revise the TeX and recompile if anything changes.
- **Photograph:** uses `assets/federico-cacciafesta.jpg`, supplied by the website owner. Edit or replace this file to update the portrait.
- **Publications:** 26 papers and 5 proceedings were transcribed from the public Google Sites page; 2 newer 2026 arXiv preprints were added. The venue metadata is from the website and may need editorial checking. Some titles and arXiv titles differ subtly.
- **Teaching:** 2026–27 and 2025–26 course information was confirmed on University of Padova's STEM platform. The 2022–23 entry is from the existing Google Sites website.
- **No GitHub publication performed:** this is a local preview, not a deployed website.

## Sources consulted (18 November 2026)

- Original homepage: https://sites.google.com/view/fcacciafesta/home
- Original publications: https://sites.google.com/view/fcacciafesta/research
- Original teaching: https://sites.google.com/view/fcacciafesta/teaching
- University profile: https://www.math.unipd.it/en/department/people/federico.cacciafesta/
- University teaching profile: https://stem.elearning.unipd.it/blocks/course_managers/manager.php?b=175&id=369
- Preprint: https://arxiv.org/abs/2611.07445
- Preprint: https://arxiv.org/abs/2607.03242

This preview is not affiliated with or endorsed by the University of Padova. Site content is a proposed presentation based on public professional information.

## November 18, 2026 changes

Replaced the abstract artwork with the provided portrait; removed the generic home introduction; added invariant/Gibbs measures as a distinct line of research and an archive filter. All page copy remains editable in `assets/app.js`.

## Editorial revision 2 (18 November 2026)

- Home: removed the research directions card grid (the five detailed cards remain on the Research page).
- Research: removed the lateral "The central question / Key methods" box. Intro now explicitly mentions dispersive, smoothing and Strichartz estimates. Curved-space card now covers variable-coefficient problems. Fourth card concerns harmonic analysis alone.
- Publications: one heading per year, with publication entries grouped under it. Topic badges are replaced by the five research glyphs; their meanings are accessible via title and aria-label. Topic, year and text filters still work together.
- Teaching: unified the course title to "Analisi Matematica 1 (Modulo A)" for all previously listed years; no additional teaching years were invented.
- CV: synchronized the download with the corrected English LaTeX version that compiles on the user's setup.

## Research introduction simplification (18 November 2026)

Research now starts with one concise sentence, “My research focuses on dispersive partial differential equations.” The five detailed research cards remain unchanged. No other page content was altered.

## Revision 4 (18 November 2026)

- Academic contact email: federico.cacciafesta@unipd.it.
- Removed the Previous website link from Contact and the old Google Sites archive link from Teaching.
- Home: replaced the sequential topic labels with an interactive, overlapping constellation of linked research interests (including Dirac equations, dispersive and Strichartz estimates, PDEs on manifolds, nonlinear dynamics, invariant measures, and harmonic analysis).
- Research: preserved the five detailed subjects and their source links, adding deep-link anchors so that each topic in the diagram is clickable.

## Final selected home visual: Mathematical Orbits

The homepage includes the selected interactive **Mathematical Orbits** research map (six topics). The earlier comparison controls and unused design variants were removed from the live page. Strichartz estimates are included under dispersive estimates, not shown separately. The diagram uses an inline SVG plus semantic links and CSS; no image rendering dependency.

### Publishing on GitHub Pages

1. Create a free GitHub account (or use an existing account).
2. Create a **public** repository named `<username>.github.io` for a clean `https://<username>.github.io/` address, OR any other repository for `https://<username>.github.io/<repository>/`.
3. Upload the **contents of this folder**, keeping `index.html` at repository root and `assets/` next to it (do not upload the outer directory as the only repository folder).
4. Open Repository **Settings > Pages**. Set **Build and deployment > Source: Deploy from a branch > main / (root)** and save.
5. Once published, check all five pages, publication filtering, and that CV and portrait load.
6. If replacing a Google Sites URL, keep the Google Sites page live as a notice with a link to the new URL; a `sites.google.com/view/...` address cannot directly host a GitHub Pages site.

Updated 18 November 2026.
