# Prompt to Give Codex

Use this prompt directly with Codex to generate the website implementation.

---

You are a senior product designer + frontend architect.
Build a **production-ready, multi-page, futuristic agency website** named **NeonPulse**.

## Objectives
- Make the design modern, premium, and dynamic.
- Follow this graphic charter:
  - Background: #070B14 and #0F172A
  - Accent: #00E5FF and #7C3AED
  - Text: #E6EDF7 / #9FB0C7
  - Glass borders: rgba(159,176,199,0.22)
  - Fonts: Space Grotesk (headings), Inter (body), JetBrains Mono (metrics)
- The result must feel **more advanced** than typical AI capture / cloud digital services websites.
- Include refined animations and micro-interactions throughout.

## Tech stack
- Next.js (latest stable)
- TypeScript
- Tailwind CSS
- Framer Motion for motion
- Optional GSAP only where Framer is insufficient

## Pages to build
1. Home (`/`)
2. Services (`/services`)
3. Case Studies (`/case-studies`)
4. Dynamic Case Study Detail (`/case-studies/[slug]`)
5. About (`/about`)
6. Process (`/process`)
7. Insights (`/insights`)
8. Contact (`/contact`)
9. Privacy (`/privacy`)
10. Terms (`/terms`)

## Home page requirements
- Hero with animated gradient mesh background.
- Strong headline and two CTAs.
- Metrics counters with smooth count-up.
- Services preview cards with hover tilt + glow.
- Case study carousel with motion transitions.
- Process timeline section.
- Testimonials section.
- Sticky floating CTA on desktop.

## Animation requirements (important)
- Staggered reveal animations on scroll for all sections.
- Button micro-interactions (glow pulse + slight scale).
- Smooth page transitions between routes.
- Cursor-reactive light effect in hero on desktop.
- Respect `prefers-reduced-motion`.
- Keep animations performant (transform/opacity first).

## UX and UI quality bar
- Fully responsive (mobile/tablet/desktop).
- Accessibility: semantic structure, keyboard nav, visible focus states.
- Premium spacing and typography rhythm.
- No generic template feel; use strong composition and hierarchy.

## Content
Use business-focused copy with clear outcomes.
Include example links on an “Inspiration” block (open in new tab):
- https://www.framer.com/motion/
- https://gsap.com/showcase/
- https://lottiefiles.com/
- https://spline.design/examples
- https://dribbble.com/tags/futuristic_web_design
- https://www.awwwards.com/websites/

## Deliverables
- Complete Next.js project structure.
- Reusable component architecture.
- Clean, maintainable TypeScript.
- SEO metadata for each page.
- README with setup + deploy steps.

## Deployment
- Optimize for deployment on Vercel.
- Add environment placeholder configuration if needed.

Now generate the full codebase.
