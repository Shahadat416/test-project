# Cursor

Project notes for Cursor in this folder.

## About

This is a Node.js web app built with **Next.js** and **TypeScript**.

## Tech stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)
- **Package manager:** npm

## Conventions

- Use TypeScript throughout; avoid `any` unless there is no practical alternative.
- Prefer Server Components; add `"use client"` only when the feature needs client state, effects, or browser APIs.
- Colocate UI, styles, and feature logic under `app/` and `components/`.
- Keep changes scoped to the request.
- Do not commit unless asked.

## Commands

```bash
npm install
npm run dev
npm run build
npm start
npm run lint
```
