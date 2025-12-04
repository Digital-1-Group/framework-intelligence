# Framework Intelligence

Central repository for AI agent framework intelligence - current versions, patterns, and deprecations.

## Overview

This repository provides a comprehensive intelligence cache that AI agents can use to:
- Know current stable versions of 70+ frameworks and libraries
- Avoid deprecated patterns and configurations
- Use current best practices for each framework

## Usage

### Sync Intelligence to Your Project

```bash
# Download the sync script
curl -o scripts/sync-framework-intelligence.sh https://raw.githubusercontent.com/itsflippen-dev/framework-intelligence/main/scripts/sync-framework-intelligence.sh
chmod +x scripts/sync-framework-intelligence.sh

# Run sync
./scripts/sync-framework-intelligence.sh
```

### Direct Download

```bash
curl -o .framework-intelligence.json https://raw.githubusercontent.com/itsflippen-dev/framework-intelligence/main/intelligence/latest.json
```

## Covered Frameworks

### Languages & Runtimes
- Rust, Python, JavaScript/TypeScript, Go, Swift, Kotlin, Java
- Node.js, Deno, Bun

### Frontend
- React 19, Next.js 15, Vue 3.4, Nuxt 3.10
- Svelte 5, SvelteKit 2, Astro 4, Angular 18

### UI/Styling
- Tailwind CSS 4.0, shadcn/ui 2.0, Radix UI
- Framer Motion 11, Headless UI 2.0

### State Management
- Zustand 5, Jotai 2, Redux Toolkit 2
- TanStack Query 5, SWR 2, Pinia 2.1

### Backend
- Express 5, Fastify 5, Hono 4, NestJS 10
- Django 5, FastAPI, Flask 3, Actix-web 4, Axum

### Database/ORM
- Prisma 5.10, Drizzle ORM, TypeORM
- SQLAlchemy 2.0, Diesel 2.1, Mongoose 8

### Build Tools
- Vite 5, Turbopack, esbuild, Webpack 5
- ESLint 9 (flat config), Biome 1.5, Prettier 3.2

### Testing
- Vitest 1.3, Jest 30, Playwright 1.41
- Testing Library 15, Cypress 13, pytest 8

### AI/ML
- OpenAI SDK 1.12, Anthropic SDK 0.18
- Vercel AI SDK 3, LangChain, LlamaIndex

## Contributing

To update framework versions or add new patterns:
1. Edit `intelligence/latest.json`
2. Run validation
3. Submit a PR

## License

MIT
