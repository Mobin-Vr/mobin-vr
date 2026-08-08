# Hi 👋, I'm Mobin

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://mobin-portfo.vercel.app/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:mobin.varnaseri@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat&logo=telegram&logoColor=white)](https://t.me/mobin_vr)
<!-- [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mobin-vr) -->

## Frontend Engineer

I build modern web applications with React, Next.js, and TypeScript. Currently focused on frontend architecture, AI engineering, and building reliable software systems that combine modern web technologies with LLM-powered workflows.

---

## Core Technologies

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-149ECA?style=flat&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat&logo=clerk&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Selected Engineering Projects

### [Microsoft To Do (clone)](https://github.com/Mobin-Vr/To-Do)
A multi-tenant task app where authorization lives in the database, not the UI. A security audit surfaced and fixed a tautological RLS join condition and client-trusted RPC parameters; every mutation now runs through `SECURITY DEFINER` functions that re-validate the caller server-side. Real-time sync, an offline change log with write-coalescing, and domain-scoped Zustand stores keep collaborators consistent over an unreliable network.

### [Google Translate (clone)](https://github.com/Mobin-Vr/Google-Translate)
An LLM-only translation app: DeepSeek handles both language detection and translation in a single call, validated against a Zod schema before the response ever reaches the UI. Since DeepSeek doesn't support request cancellation, a latest-wins pipeline guards against out-of-order responses from fast typing. Server-first rendering scores 96 on Lighthouse Performance.
