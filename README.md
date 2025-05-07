homewell-post-los/
├── README.md
├── packages/
│   ├── web-app/
│   │   ├── public/
│   │   │   └── index.html
│   │   ├── src/
│   │   │   ├── components/
│   │   │   │   └── UserForm.tsx
│   │   │   ├── hooks/
│   │   │   │   └── useNullable.ts
│   │   │   ├── App.tsx
│   │   │   └── index.tsx
│   │   ├── tsconfig.json
│   │   └── package.json
│   └── mobile-app/
│       ├── App.tsx
│       ├── tsconfig.json
│       ├── package.json
│       └── babel.config.js
└── lerna.json (or turbo.json)

# HomeWell Web & Mobile UI (TypeScript)

This monorepo provides both a React Web app and a React Native Mobile app, built in TypeScript with strict null checks and utility hooks to catch UI nullables.

## Overview
- **TypeScript** with `strictNullChecks` enabled
- **React** (Web) & **React Native** (Mobile)
- **Nullable guard** hook `useNullable` to safely handle optional props
- Basic **UserForm** component illustrating nullable handling

---

## Prerequisites
- Node 18+
- Yarn (or npm)
- For mobile: Android/iOS simulator or device setup

---

## Project Setup

```bash
git clone https://github.com/your-org/homewell-post-los.git
cd homewell-post-los
yarn install
