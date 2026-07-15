# PixelFlow

PixelFlow is a full-stack AI-powered media processing platform built with **Next.js**, **TypeScript**, and **Cloudinary**. It enables users to upload, optimize, transform, and manage images and videos through a modern web interface, with secure authentication and cloud-based media storage.

## Features

- Secure authentication with Clerk
- Upload and manage images and videos
- AI-powered image transformations using Cloudinary
- Video compression and automatic format optimization
- Responsive dashboard for browsing uploaded media
- Preview and download processed images and videos
- Persistent storage using Prisma and NeonDB (PostgreSQL)
- Modern UI built with Tailwind CSS and DaisyUI

---

## Tech Stack

| Category | Technologies |
|----------|--------------|
| Framework | Next.js (App Router) |
| Language | TypeScript |
| Authentication | Clerk |
| Media Processing | Cloudinary |
| Database | PostgreSQL (NeonDB) |
| ORM | Prisma |
| Styling | Tailwind CSS, DaisyUI |

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/pixelflow.git
cd pixelflow
```

### Install dependencies

```bash
npm install
```

### Configure environment variables

Copy the sample environment file.

```bash
cp env.sample .env
```

Update the required environment variables for:

- Clerk
- Cloudinary
- NeonDB
- Prisma

### Generate the Prisma Client

```bash
npx prisma generate
```

### Apply database migrations

```bash
npx prisma migrate deploy
```

### Start the development server

```bash
npm run dev
```

Visit **http://localhost:3000** in your browser.

---

## Project Structure

```text
app/            Next.js App Router
components/     Shared UI components
prisma/         Prisma schema
public/         Static assets
types/          TypeScript types
```

---

## Future Improvements

- AI background removal
- Image upscaling
- Batch media processing
- Drag-and-drop uploads
- Media search and filtering
- User storage analytics

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- Next.js
- Clerk
- Cloudinary
- Prisma
- NeonDB
- Tailwind CSS
- DaisyUI
