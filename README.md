# Modern Full Stack ECommerce Application with Stripe & Sanity

A Next.js E-commerce app with Sanity.io and Stripe API. Built with TailwindCSS framework 

![image](https://user-images.githubusercontent.com/70798723/218365328-9ae85632-74b6-4811-abb5-0f5a4d779cc1.png)


## Getting Started

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

## Run the app locally
To run this app locally, you need to have Sanity.io and Stripe accounts.

### Setting up Sanity
+ Head over to the Sanity.io's getting started page and generate a blank template
+ Copy the schema files located in sanity/schemas from this project to your sanity project's schemas directory
+ Make sure to replace the client configuration found under src/lib/sanity/client.ts with your own Sanity project

### Setting up Stripe
+ Create a Stripe account
+ Make sure to enable Test mode first
+ Submit basic account details to enable test mode payment

### Environment Variables

It is important to provide the following environment variables in order for this project to run properly locally

+ SANITY_PROJECT_TOKEN - Found under https://www.sanity.io/manage then select your project and then go to API -> Tokens

+ NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY - This can be found in your Stripe's dashboard

+ STRIPE_SECRET_KEY - This can be found in your Stripe's dashboard

## Demo Link
https://drive.google.com/file/d/1GkrUVzLkscShTSfRT5in0psUlP-mfOf8/view?usp=share_link


