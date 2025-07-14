This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

# Clear Setup

- [Document] (https://dashboard.clerk.com/apps/app_2zolHo5Dfwo6zEnl9YyNW4ETl8L/instances/ins_2zolHpP4aw1foNLNqtN4YaYNi8m)

### install clerk

`npm install @clerk/nextjs`

### Set Clerk API keys

![Step 2 instructions for setting Clerk API keys. The left side explains to add Clerk API keys to the .env file or create the file if it does not exist, and provides a link to the API keys page. The right side shows a code block labeled .env with two example environment variables: NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY and CLERK_SECRET_KEY, each followed by sample values. The overall tone is instructional and clear, with a focus on guiding the user through configuration.]
copy this keys and past to .env file

### Update middleware.ts

### install mongoose

`npm i mongoose`

### connect to mongodb

in .env file add
`MONGODB_URI="you url"`
