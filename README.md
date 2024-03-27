# PixelPerfect: An AI-Powered Photo Editor

PixelForge is a web-based photo editor powered by AI. It allows users to enhance and manipulate their photos using advanced algorithms and machine learning techniques.

## Features

- AI-powered photo enhancement
- Advanced image manipulation tools: Image Restore, Generative Fill, Generative Replace, Object Remove, Object Recolor, and Background Remove
- User authentication with Clerk
- User-friendly interface
- Real-time preview
- Cross-platform compatibility
- Quick and simple in-app purchases

## Technologies Used

- Next.js: A React framework for building server-side rendered and static websites
- TypeScript: JavaScript With Syntax For Types
- MongoDB: A NoSQL database that provides a flexible and scalable solution for storing and retrieving user/content/transaction data
- Cloudinary API: Powerful tool for managing and manipulating images in the cloud using AI
- Clerk API: For authenticating users and securing their profile
- Stripe API: For payment processing with regards to image transformation credit plans
- Shadcn: A library for rapid UI development with style props, color modes, themes and variants
- TailwindCSS: A utility-first CSS framework for rapidly building modern websites straight from HTML

## Getting Started

To get started with PixelPerfect, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/ai-photo-editor.git`
2. Install the dependencies: `npm install`
3. Start the development server: `npm run dev`
4. Open your browser and navigate to `http://localhost:3000`
5. Provide your own API keys

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the
following content:

```env
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

# Clerk Webhook Secret
CLERK_WEBHOOK_SECRET=

# MongoDB
MONGODB_URI=

# Cloudinary
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

# Stripe
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=

# Next
NEXT_PUBLIC_SERVER_URL=
```

Replace the placeholder values with your actual respective account credentials.
You can obtain these credentials by signing up on the
[Clerk](https://clerk.com/), [MongoDB](https://www.mongodb.com/),
[Cloudinary](https://cloudinary.com/) and [Stripe](https://stripe.com)