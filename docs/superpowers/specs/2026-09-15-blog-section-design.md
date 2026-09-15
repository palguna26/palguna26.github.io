# Blog Section Design

## Goal

Add a scalable static blog structure to the portfolio. The homepage should promote the latest article, while a blog index and individual article pages provide room for future writing.

## Page Structure

- `index.html` keeps the existing portfolio and replaces the Writing coming-soon panel with one article preview.
- `blog/index.html` lists published blog posts with title, summary, topic, date, and reading time.
- `blog/memory-systems-for-ai-agents.html` contains the complete article about memory systems for AI agents.

## Article Content

The article will explain what agent memory is, why agents need it, the main memory types, a practical memory-layer architecture, and key implementation concerns. It will include short code examples, an HTML/CSS architecture diagram, and inline numbered citations linked to a references section.

References will favor primary research papers and official technical documentation. The article will avoid claiming benchmark results or implementation details without a citation or clear framing as an example.

## Visual and Interaction Design

Use the existing portfolio style: warm white background, near-black text, muted green accent, thin borders, rounded soft panels, and responsive spacing. The article page will use a narrower reading column than the portfolio, a compact article header, readable section hierarchy, styled blockquotes/code, and a back-to-blog link.

The homepage Writing navigation item will link to `blog/`. The homepage preview will link directly to the article. Blog pages will include links back to the portfolio and blog index.

## Technical Constraints

- Keep the site dependency-free and compatible with GitHub Pages.
- Use ordinary relative links so the pages work when hosted from a repository subpath.
- Keep existing portfolio behavior intact, including mobile navigation, active-section highlighting, contribution loading, accessibility, and reduced-motion support.
- Use semantic HTML, visible focus states, descriptive link text, and responsive layouts.

## Validation

- Check all internal links between the portfolio, blog index, and article.
- Confirm the article renders at desktop and mobile widths without horizontal overflow.
- Confirm citations link to the matching references and external references open safely.
- Confirm the original homepage scripts and contribution fallback remain functional.
- Verify the pages require no build step.
