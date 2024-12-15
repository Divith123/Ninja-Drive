# Ninja Drive - Google Drive Clone with NextJS, Firebase, Stripe, and Clerk

Embark on a journey to build your own Google Drive clone with **Next.js** as the front-end framework, **Firebase** for backend functionality, **Stripe** for secure payment integration, and **Clerk** for authentication. This project is designed for developers eager to enhance their skills while creating a powerful cloud storage application.

## 🚀 Demo

[https://drive.ninja.com](https://drive.ninja.com)

## 🧐 Features

Here are the standout features of **Ninja Drive**:

- **Stripe Integration** for payments
- **Clerk Authentication** for secure logins
- **Firebase Backend** for real-time data management
- **Light and Dark mode** 🌓 for theme switching
- List management: rename, delete, drag & drop, reorder, and copy
- **Stripe Subscription** to unlock unlimited storage for organizations
- **Zustand** for efficient state management
- Detail-oriented effects and animations using **TailwindCSS**
- Setup with **TypeScript** and **NextJS** app routes for smooth performance

## 🛠️ Installation Steps:

1. Install the required packages:

```bash
npm install & yarn install
```

2. Setup your `.env` file with the following environment variables:

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_STRIPE_SECRET_KEY=
NEXT_PUBLIC_DOMAIN=
```

3. Start the app:

```bash
npm run dev & yarn dev
```

## 💻 Built with

Technologies used in the project:

- **ReactJS**
- **NextJS** with app routes
- **NodeJS**
- **TailwindCSS**
- **ShadcnUI**
- **Clerk** for authentication
- **Stripe** for payment processing
- **TypeScript** for type safety
- **Firebase** for backend functionality
- **Zustand** for state management
