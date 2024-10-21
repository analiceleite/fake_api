# Eplay - Fake API

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app). The primary purpose of this project is to provide a fake API that simulates a game store environment for development and testing purposes.

## Getting Started

To install the project's dependencies, run:

`npm install`

To start the development server, run:

`npm run dev # or yarn dev # or pnpm dev`

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application in action. You can begin editing the page by modifying `pages/index.tsx`, and the page will auto-update as you make changes.

## Purpose of the Fake API

The fake API was created to serve as a backend for the Eplay game store application. It allows developers to test various features without relying on a real backend service. This approach facilitates rapid development and ensures that the frontend can function independently from backend implementations.

## API Endpoints

The API routes can be accessed at the following endpoints:

- **GET** `/api/eplay/acao` - Retrieves actions related to the game store.
- **GET** `/api/eplay/destaque` - Retrieves featured games.
- **GET** `/api/eplay/em-breve` - Retrieves upcoming games.
- **GET** `/api/eplay/esportes` - Retrieves sports games available in the store.
- **GET** `/api/eplay/jogos/[id]` - Retrieves detailed information about a specific game by its ID.
- **GET** `/api/eplay/luta` - Retrieves fighting games available in the store.
- **GET** `/api/eplay/promocoes` - Retrieves ongoing promotions.
- **GET** `/api/eplay/rpg` - Retrieves role-playing games available in the store.
- **GET** `/api/eplay/simulacao` - Retrieves simulation games available in the store.

### Example Endpoints

- You can access the sample API route at [http://localhost:3000/api/eplay/acao](http://localhost:3000/api/eplay/acao). This endpoint can be modified in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`, meaning files in this directory are treated as API routes instead of React pages.

## Learn More

To learn more about Next.js, check out the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - Learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - An interactive Next.js tutorial.

You can also check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

Checkout the [API deployment](https://analice-fake-api.vercel.app/).