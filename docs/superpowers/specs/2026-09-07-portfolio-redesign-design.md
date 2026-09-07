# Portfolio Redesign Design

## Goal

Redesign Palguna Shetty's portfolio for recruiters and open-source collaborators. The site should communicate technical focus quickly, make projects easy to inspect, and feel polished without visual clutter.

## Technical Constraints

- Keep the site compatible with GitHub Pages.
- Use one dependency-free `index.html` with embedded CSS and JavaScript.
- Build responsive layouts for desktop, tablet, and mobile.
- Respect reduced-motion preferences and use accessible HTML.

## Visual Direction

Use an editorial minimal style with a warm white background, near-black text, and forest-green accents. Typography should be strong and readable. Thin rules, generous spacing, restrained cards, and subtle motion will create hierarchy without making the page busy.

## Page Structure

1. Fixed header with name, section links, and resume link.
2. Hero with a short positioning statement focused on AI agents, developer tools, and infrastructure.
3. About section with education, interests, and working style.
4. Selected Projects featuring Termyte, FreshBrief, Revflo, and EvalSmith.
5. Skills grouped into languages, frameworks, AI tooling, data, and deployment.
6. Open Source section with live GitHub contribution data and a direct profile link.
7. Writing section presented as an intentional coming-soon area covering coding agents, developer tooling, and reliable AI systems.
8. Contact section with email, GitHub, LinkedIn, X, and resume links.

## Project Presentation

Each project will include a concise problem-focused description, relevant technology tags, repository link, and a clear status or role. The first two projects will receive more visual weight. Content will be based on the current public GitHub profile and repositories.

## Behaviour

JavaScript will:

- manage the mobile navigation;
- highlight the active section;
- reveal content with subtle motion;
- fetch the public GitHub contribution calendar;
- show a clean fallback link if contribution data cannot load.

Core content will remain visible and usable without JavaScript.

## Accessibility and Performance

- Use semantic landmarks and visible keyboard focus states.
- Maintain readable color contrast and comfortable text sizes.
- Avoid a custom cursor and heavy visual effects.
- Respect `prefers-reduced-motion`.
- Keep assets light and avoid runtime frameworks.

## Validation

- Check page structure and links.
- Test desktop and mobile layouts.
- Confirm the page works as a static GitHub Pages document.
- Verify graceful handling of GitHub contribution API failure.
- Check keyboard navigation and reduced-motion behavior.
