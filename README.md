# Spotify Clone Web App

Spotify Clone is a work in progress web app developed with Next.js and TypeScript. It includes user/email authentication, home page, playlists, and music player with shuffle, repeat, play, current duration, and seek bar. Includes middleware to protect API routes by using a Next.js middleware edge function that checks user token, custom hooks with SWR to fetching user and playlists data, server side rendering to load playlists by exporting the getServerSideProps function from Next.js, state management for the music player using Easy Peasy library and requestAnimationFrame method to update synchronously its UI.

- [Live Site (Vercel)](https://spotify-clone-react-nextjs-typescript-prisma-postgresql.vercel.app/)

## Tech Stack

- Frontend/Backend: React.js, Node.js, Next.js, Chakra UI, React Howler, React Material Design Icons.
- Authentication: BCrypt and JWT.
- API/Database: Prisma, PostgreSQL and Heroku.
- Deployment: Vercel.
___

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
