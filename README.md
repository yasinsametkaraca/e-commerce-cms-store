# Full Stack Content Management System | E-Commerce | Dashboard: Next.js App Router, React, Tailwind, Prisma, MySQL, Shadcn

Next.js App Router, React, Tailwind, Prisma, MySQL, shadcn/ui, Clerk, Stripe, Cloudinary

### Prerequisites

**Node version 14.x**

### Install packages

```shell
npm install
```

### Setup .env file

```js
NEXT_PUBLIC_API_URL=http://localhost:3000/api/15548fca-d1d8-476b-bd6b-d734afc018c9 (your_api_url/api/store_id)
NEXT_PUBLIC_STORE_URL=http://localhost:3001 (your store url)
```

### Connect to DB and Push Prisma

```shell
npx prisma generate
npx prisma db push
```

### Install and start the app

```shell
npm install
npm run dev
```
