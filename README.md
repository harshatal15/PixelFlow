# PixelFlow

PixelFlow is a media SaaS app for uploading, transforming, and sharing images and videos. It's built on Next.js with Cloudinary handling the media processing, Prisma/NeonDB for storage, and Clerk for auth.

## Features

- Sign-in/sign-up with Clerk
- Upload images and generate social-media-ready crops/formats through Cloudinary
- Upload and compress videos, with automatic format optimization
- Dashboard to browse, preview, and download uploaded videos
- Postgres (NeonDB) database via Prisma to keep track of everything you upload

## Stack

- Next.js (App Router)
- Clerk for authentication
- Cloudinary for media storage/transformation
- Prisma + NeonDB (Postgres)
- Tailwind CSS + Daisy UI

## Setup

Install dependencies:

```bash
npm install
```

Copy `env.sample` to `.env` and fill in your Clerk, Cloudinary, and database credentials:

```bash
cp env.sample .env
```

Set up the database:

```bash
npx prisma generate
npx prisma migrate deploy
```

Run it:

```bash
npm run dev
```

Then open `http://localhost:3000`.

## License

MIT
