This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Create .env.local and add the following Firebase configuration

```bash
NEXT_PUBLIC_FIREBASE_API_KEY = "your-api-key"
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN = "your-auth-domain"
NEXT_PUBLIC_FIREBASE_PROJECT_ID = "your-project-id"
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET = "your-storage-bucket"
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID = "your-sender-id"
NEXT_PUBLIC_FIREBASE_APP_ID = "your-app-id"
NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID = "your-measurement-id"
```

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
