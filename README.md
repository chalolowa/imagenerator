# Image Generator :wink:

This is a [Next.js](https://nextjs.org/) typescript project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app). The project makes use of image generation via text prompts.

## Prerequisite

You're gonna need an API Key for using Hugging Face’s Inference API. Go ahead and create an account on [Hugging Face](https://huggingface.co/) in order to get access tokens.

## Getting Started

First, install the required dependencies:
```bash
npm i
#or
yarn i
```

Next, run the development server:
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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Working Mechanism

1. User inputs a prompt on the frontend
2. We send this prompt to our backend, which further calls Hugging Face's API
3. We get an image back from Hugging Face and display it on the frontend
4. Small and simple project 🙂 

