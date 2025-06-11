# JSM SAS App - LMS with Next.js, Supabase & Payments

<div align="center">
  <a href="https://www.youtube.com/watch?v=XUkNR-JfHwo" target="_blank">
    <img src="public/readme/hero.png" alt="Project Banner" width="600">
  </a>

  <div>
    <img src="https://img.shields.io/badge/-Next.js-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=black" alt="Next.js" />
    <img src="https://img.shields.io/badge/-Vapi-green?style=for-the-badge&logoColor=white&logo=vapi&color=green" alt="Vapi" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-00BCFF?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  </div>

  <h1 align="center">SaaS App - Learning Management System</h1>


</div>

## 📋 Table of Contents

1. [Introduction](#introduction) 🤖
2. [Tech Stack](#tech-stack) ⚙️
3. [Features](#features) 🔋
4. [Quick Start](#quick-start) 🤸
5. [Assets](#assets) 🔗
6. [More](#more) 🚀


## 🤖 Introduction <a name="introduction"></a>

This project is a Learning Management System (LMS) SaaS application built from scratch using Next.js, Supabase, and Stripe. It features user authentication, subscription management, payment integration, and real-time teaching sessions with AI voice agents powered by Vapi. The app provides an interactive platform for users to create and engage with AI tutors, manage their learning journey, and access previous sessions and bookmarks.


## ⚙️ Tech Stack <a name="tech-stack"></a>

- **[Clerk](https://jsm.dev/converso-clerk)**: A platform for authentication, user management, and billing, offering UI components, APIs, and dashboards for secure user management and subscription handling.
- **[Next.js](https://nextjs.org/)**: A React framework for building fast, scalable web applications with server-side rendering, static site generation, and API routes.
- **[Sentry](https://jsm.dev/converso-sentry)**: An error tracking and performance monitoring tool providing real-time alerts, stack traces, and insights for debugging.
- **[shadcn/ui](https://ui.shadcn.com/)**: A customizable component library built on Radix UI and Tailwind CSS, offering accessible, modern UI components.
- **[Supabase](https://supabase.com/)**: An open-source backend-as-a-service platform with instant APIs, real-time subscriptions, authentication, storage, and a PostgreSQL database.
- **[Tailwind CSS](https://tailwindcss.com/)**: A utility-first CSS framework for designing custom user interfaces with low-level utility classes.
- **[TypeScript](https://www.typescriptlang.org/)**: A JavaScript superset adding static typing for better tooling, code quality, and error detection.
- **[Vapi](https://jsm.dev/converso-vapi)**: A voice AI platform for creating conversational agents with low-latency voice interactions, speech-to-text, and text-to-speech capabilities.
- **[Zod](https://zod.dev/)**: A TypeScript-first schema validation library for defining and validating data structures with ease.

## 🔋 Features <a name="features"></a>

- **AI Voice Agents**: Engage in tutoring sessions with AI-powered voice agents specializing in various subjects and topics.
- **Authentication**: Secure user sign-up and sign-in with Clerk, supporting Google authentication and more.
- **Billing & Subscriptions**: Manage subscription plans, upgrades, and payments seamlessly with Stripe integration.
- **Bookmarks and Session History**: Organize learning by bookmarking tutors and accessing previous sessions, with user-specific data stored in Supabase.
- **Code Reusability**: Utilize reusable components and a modular codebase for efficient development.
- **Create a Tutor**: Build custom AI tutors by selecting a subject, topic, and conversation style.
- **Cross-Device Compatibility**: Fully responsive design ensuring seamless functionality across all devices.
- **Database Integration**: Leverage Supabase for real-time data management and storage.
- **Modern UI/UX**: Clean, responsive design built with Tailwind CSS and shadcn/ui for an enhanced user experience.
- **Scalable Tech Stack**: Powered by Next.js for a fast, production-ready application that scales effortlessly.
- **Search Functionality**: Quickly find tutors using filters and a search bar.

And much more, including a focus on code architecture and reusability.

## 🤸 Quick Start <a name="quick-start"></a>

Follow these steps to set up and run the project locally.

### Prerequisites

Ensure you have the following installed:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en) (v18 or later recommended)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Cloning the Repository

```bash
git clone https://github.com/MohdAli056/saas-app.git
cd jsm-saas-app
```

### Installation

Install the project dependencies:

```bash
npm install
```

### Set Up Environment Variables

Create a `.env` file in the project root and add the following:

```env
# Sentry
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

Replace the placeholders with your actual credentials from:
- [Supabase](https://supabase.com/dashboard)
- [Clerk](https://jsm.dev/converso-clerk)
- [Sentry](https://jsm.dev/converso-sentry)
- [Vapi](https://jsm.dev/converso-vapi)

### Running the Project

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## 🚨 Tutorial

This repository contains the code for an in-depth tutorial available on the [JavaScript Mastery YouTube channel](https://www.youtube.com/@javascriptmastery/videos). If you prefer visual learning, this tutorial is perfect for you! Follow along to build this project step-by-step in a beginner-friendly manner.