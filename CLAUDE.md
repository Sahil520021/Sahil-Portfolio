# CLAUDE.md

## Project Overview
This is Sahil Mehra's personal portfolio website — an AI Engineer and Co-founder & CTO @ Shiftora.ai. Built with Next.js (App Router), React, Tailwind CSS, Framer Motion, and Three.js for the star background.

## Owner
- **Name:** Sahil Mehra
- **Role:** AI Engineer / Co-founder & CTO @ Shiftora.ai
- **Email:** sahilmehra0507@gmail.com
- **GitHub:** https://github.com/Sahil520021
- **LinkedIn:** https://www.linkedin.com/in/sahil-mehra-a93549258/

## Commands
- `npm run dev` — Start dev server
- `npm run build` — Production build
- `npm run lint` — Run ESLint

## Project Structure
- `config/index.ts` — Site metadata (title, description, author)
- `constants/index.ts` — All content data: skills, projects, social links, footer, nav links
- `components/sub/hero-content.tsx` — Hero section text (title, bio, CTA)
- `components/sub/skill-text.tsx` — Skills section intro text
- `components/main/navbar.tsx` — Navigation bar with name display
- `components/main/footer.tsx` — Footer with copyright
- `components/main/encryption.tsx` — Automation & Intelligence section
- `components/main/star-background.tsx` — Three.js animated star background
- `public/skills/` — Skill icon images
- `public/projects/` — Project screenshot images

## Key Conventions
- All personal content is centralized in `constants/index.ts` and the component files above
- Skill icons are in `/public/skills/` — add new `.png` files there when adding skills
- The site uses Framer Motion for animations and `@react-three/fiber` for the 3D star background
- TypeScript strict mode is enabled
- Deployed on Vercel with GitHub auto-deploy from `main` branch
