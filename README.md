# Cloudinary AI SaaS

A modern SaaS app for uploading, transforming, and sharing media with Cloudinary.
Built with Next.js and Prisma, and designed for production-ready workflows.

## Features

- Secure image and video uploads
- Cloudinary-backed transformations
- Social sharing-friendly media pages
- Auth-ready routing with Next.js App Router
- Persistent storage with Prisma and a Postgres database

## Tech Stack

- Next.js (App Router)
- TypeScript
- Prisma ORM
- Cloudinary
- Tailwind CSS and DaisyUI

## Getting Started

### Prerequisites

- Node.js 18+
- Cloudinary account
- Postgres database (e.g., Neon)

### Setup

1. Install dependencies
	```bash
	npm install
	```
2. Copy `env.sample` to `.env.local` and fill in values
3. Run database migrations
	```bash
	npx prisma migrate deploy
	```
4. Start the development server
	```bash
	npm run dev
	```
