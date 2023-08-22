# Spotify Clone

## Live Demo

Demo Link - [Spotify](https://spotify-clone-falak097.vercel.app/)

![Spotify](https://github.com/FALAK097/spotify_clone/blob/main/screenshot.PNG)

Welcome to my personal project, a Spotify Clone! This project replicates some of the key features and functionalities of Spotify and is intended to showcase my development skills.

## Introduction

This project is a Spotify Clone that I've developed to showcase my skills in building web applications with modern technologies. It closely resembles the design and features of the Spotify music streaming platform.

## Key Features

- Song upload
- Stripe integration for premium subscriptions
- User authentication with Supabase and GitHub integration
- Audio playback functionality
- Favorites and playlists system
- Advanced Player component
- Stripe recurring payment integration

## Technologies Used

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Supabase](https://supabase.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [Stripe](https://stripe.com/)

### Prerequisites

Before you begin, make sure you have the following installed on your system:

- Node.js and npm (Node Package Manager)
- Git
- PostgreSQL
- Stripe account (for integrating Stripe payments)

## Installation

- Clone the repository:
  `git clone https://github.com/FALAK097/spotify_clone.git`

- Navigate to the project directory:
  `cd spotify_clone`

- Install dependencies:
  `npm install`

- Create an .env.local file for Supabase and Stripe credentials.
- Supabase Credentials  
  NEXT_PUBLIC_SUPABASE_URL=<https://your-supabase-url.com>  
  NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anonymous-key  
  SUPABASE_SERVICE_ROLE_KEY=your-service-role-key
- Stripe Credentials  
  NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your-stripe-publishable-key  
  STRIPE_SECRET_KEY=your-stripe-secret-key  
  STRIPE_WEBHOOK_SECRET=your-stripe-webhook-secret

  You can get these keys from your supabase dashboard or stripe dashboard respectively after creating a new application in their
  respective platforms.

- Start the development server:
  `npm run dev`

- Open your browser and visit `http://localhost:3000` to see the Spotify Clone Project up & running.

## Credits

- Project developed by [Falak Gala](https://portfolio-falak.vercel.app/)
- [React](https://reactjs.org)
- [Tailwind CSS](https://tailwindcss.com/)
- [Supabase](https://supabase.io/)
- [Stripe](https://stripe.com/)
- Inspired by [Code With Antonio](https://github.com/AntonioErdeljac)
- Built with [Vite](https://vitejs.dev/)
