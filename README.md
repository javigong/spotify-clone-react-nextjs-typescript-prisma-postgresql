# Spotify Clone Web App

Spotify Clone is a work in progress web app developed with Next.js and TypeScript. It includes user/email authentication, home page, playlists, and music player with shuffle, repeat, play, current duration, and seek bar. 
This project takes advantage of different Next.js features like API routes protection by using a middleware edge function that checks users token, custom hooks with SWR to fetch user and playlists data, server side rendering to load playlists by exporting the getServerSideProps function, manages the music player state with the Easy Peasy library and synchronises its UI updates using the requestAnimationFrame method.

- [Live Site (Vercel)](https://spotify-clone-react-nextjs-typescript-prisma-postgresql.vercel.app/)

## Tech Stack

- Frontend/Backend: React.js, Node.js, Next.js, Chakra UI, React Howler, React Material Design Icons.
- Authentication: BCrypt and JWT.
- API/Database: Prisma and PostgreSQL.
- Deployment: Vercel and Heroku.

## Screenshots

![Screen Shot 2022-05-11 at 5 21 44 PM](https://user-images.githubusercontent.com/42308135/168132029-ab594005-be9a-467a-a2d1-0f11b346252d.png)

![Screen Shot 2022-05-11 at 5 21 58 PM](https://user-images.githubusercontent.com/42308135/168132034-a603590d-040e-4d4a-8d0b-82709242fe6d.png)

![Screen Shot 2022-05-11 at 5 22 14 PM](https://user-images.githubusercontent.com/42308135/168132035-3cb5bfa0-03d4-473c-9139-0515d13dd3ff.png)

![Screen Shot 2022-05-11 at 5 22 46 PM](https://user-images.githubusercontent.com/42308135/168132042-355dcace-a4c4-4a51-9c16-6bf0e59a0fa2.png)

![Screen Shot 2022-05-11 at 5 23 13 PM](https://user-images.githubusercontent.com/42308135/168132044-4fa0108b-ddea-4423-b747-e638245f42ec.png)


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

