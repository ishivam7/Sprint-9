# Sprint-9
Cine-Stream - Next.js Migration
A modern, SEO-optimized Movie Discovery application upgraded for the Track A: Frontend Specialists requirements. The application migrates the previous Sprint 08 architecture to a Next.js 15 environment, utilizing Server-Side Rendering (SSR) and the new App Router.

Important Links
Live Website:https://sprint-9-red.vercel.app/

Demo Video: https://drive.google.com/file/d/1Z7MHwYJsRUQUlmQSCJEiR1QurTiV0YNH/view?usp=drivesdk

Screenshot
https://github.com/Sarvesh-88/Sprint-9/blob/main/sprint-9-img1.png

Project Overview
Cine-Stream SPA Upgrade focuses on modernizing a React-based movie application by migrating it to Next.js 15. The core theme revolves around Server-Side Rendering (SSR) and SEO optimization, moving away from client-side routing to Next.js native file-based routing.

Tech Stack
Next.js 15 (App Router)
React.js
JavaScript (ES6+)
HTML5
CSS3
TMDB REST API

Features Completed (Phase 1: Base Architecture - P0 Mandatory)
The following mandatory Phase 1 requirements have been successfully completed:

Environment Setup
Initialized a Next.js 15 environment utilizing the App Router.
Asset Migration
Ported the Sprint 08 "Cine-Stream" UI architecture into the new Next.js environment.
Routing Architecture
Deprecated react-router-dom and recreated all routes utilizing Next.js native file-based routing.

Project Structure
src/
│
├── app/
│   ├── layout.jsx
│   ├── page.jsx
│   └── globals.css
│
├── components/
│   ├── MovieCard.jsx
│   ├── MovieGrid.jsx
│   └── SearchBar.jsx
│
└── services/
└── tmdb.js
