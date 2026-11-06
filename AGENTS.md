# Purple Leaves Website — Agent Instructions

## Development

When starting the dev server, use background mode:

```
astro dev --background
```

Manage the background server with `astro dev stop`, `astro dev status`, and `astro dev logs`.

## Documentation

Full documentation: https://docs.astro.build

Consult these guides before working on related tasks:

- [Adding pages, dynamic routes, or middleware](https://docs.astro.build/en/guides/routing/)
- [Working with Astro components](https://docs.astro.build/en/basics/astro-components/)
- [Using React, Vue, Svelte, or other framework components](https://docs.astro.build/en/guides/framework-components/)
- [Adding or managing content](https://docs.astro.build/en/guides/content-collections/)
- [Adding styles or using Tailwind](https://docs.astro.build/en/guides/styling/)
- [Supporting multiple languages](https://docs.astro.build/en/guides/internationalization/)

## Project purpose

This repository contains the public website for Purple Leaves Ltd, an independent UK technology consultancy.

The website is a simple, static, single-page professional presence.

It should communicate the company's services clearly, without marketing exaggeration or unnecessary complexity.

## Technology

- Astro, using static site generation
- TypeScript where appropriate
- Plain CSS
- GitHub Pages hosting
- GitHub Actions deployment
- No frontend framework or runtime backend

## Engineering principles

### Keep it simple

Prefer the simplest implementation that meets the requirements.

Do not introduce:

- React, Vue or other UI frameworks
- Tailwind or CSS frameworks
- Component libraries
- State management
- Client-side routing
- CMS platforms
- Build-time complexity without justification
- Unnecessary dependencies

Avoid adding JavaScript when HTML and CSS can provide the required behaviour.

### Maintainability

- Prefer readable code over clever abstractions.
- Keep components small and purposeful.
- Avoid premature generalisation.
- Use consistent naming conventions.
- Follow established Astro conventions.
- Keep content straightforward to update.
- Do not overengineer a single-page website.

### Design

Maintain a restrained, minimalist visual identity.

- Warm off-white background
- Charcoal text
- Muted green accents
- Generous whitespace
- Strong typography
- Subtle separators
- Minimal decorative elements

Avoid visual clutter, excessive animation, stock photography, gradients and generic corporate design patterns.

New sections should feel consistent with the existing design.

### Content and tone

Write content in Markdown.

Use British English.

The tone must be:

- Professional
- Understated
- Direct
- Clear
- Technically credible

Avoid:

- Buzzwords
- Marketing superlatives
- Unsupported claims
- Invented credentials
- Invented client names
- Invented testimonials
- Claims about team size or delivery capacity that are not established

Purple Leaves should be positioned as a small independent consultancy, not a large agency or a personal freelance portfolio.

Core service areas:

1. Technology leadership and fractional CTO support
2. Software architecture and cloud engineering
3. End-to-end software project delivery

Do not introduce new business offerings or specific technology partnerships without approval.

### Accessibility

Use semantic HTML and accessible interaction patterns.

Maintain WCAG 2.2 AA accessibility principles.

Ensure responsive layouts, keyboard navigation, visible focus states and sufficient contrast.

### Performance

The website should remain extremely lightweight.

Avoid external assets, tracking scripts and third-party dependencies unless explicitly requested.

Do not sacrifice performance for decorative effects.

### SEO

Maintain accurate metadata, logical heading hierarchy and meaningful page descriptions.

Do not invent business information, URLs or social media accounts.

### Deployment

The site is deployed using GitHub Actions to GitHub Pages.

Keep deployment configuration simple and reproducible.

Do not commit build output.

Preserve compatibility with the configured GitHub Pages URL and Astro base path.

## Agent workflow

For every change:

1. Read the relevant existing files.
2. Prefer minimal, focused modifications.
3. Preserve the established design and content tone.
4. Avoid unrelated refactoring.
5. Run the build and relevant checks.
6. Report what changed and what was verified.

When requirements are ambiguous, choose the simplest reasonable implementation.

Ask before adding significant dependencies, changing the site's positioning, or introducing new features.

Do not claim tests have passed unless they were actually executed.

## Scope

This is a professional company website, not a web application.

Prioritise clarity, reliability, accessibility and long-term maintainability over features.
