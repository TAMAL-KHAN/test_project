# Text Project

A Node.js workspace intended for a **Next.js** app with **TypeScript**. The repo is early-stage: dependencies and project notes are in place; application code is still being added.

## Tech stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)
- **Config:** [dotenv](https://www.npmjs.com/package/dotenv) for environment variables

## Getting started

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- npm (comes with Node.js)

### Install

```bash
npm install
```

### Environment

Copy or create a `.env` file in the project root for local secrets and config. Do not commit real credentials.

### Scripts

| Command     | Description                          |
| ----------- | ------------------------------------ |
| `npm test`  | Placeholder (no tests configured yet)|

App scripts (`dev`, `build`, `start`) will be added once the Next.js app is scaffolded.

## Project layout

```
.
├── cursor.md      # Cursor / contributor conventions
├── package.json
└── README.md
```

## Conventions

- Keep changes focused and minimal.
- Prefer clear, readable structure.
- Ask before committing or pushing.
- Use TypeScript types/interfaces consistently; avoid `any` unless necessary.
- Follow Next.js App Router patterns.

## License

ISC
