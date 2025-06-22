# SaaS LMS App – Built with Next.js, Supabase & Stripe

## 📋 Table of Contents

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🚀 [More](#more)

## 🤖 Introduction

This is a SaaS Learning Management System (LMS) app that allows users to sign up, subscribe to plans, and learn interactively using AI-powered voice agents. Built with scalability and modern UX in mind, it leverages a powerful full-stack architecture using Next.js, Supabase, and Stripe.

## ⚙️ Tech Stack

* **Next.js** – Full-stack React framework with SSR and API support.
* **Supabase** – PostgreSQL database with real-time support and authentication.
* **Clerk** – Authentication, user management, and billing.
* **Stripe** – Payment processing and subscription management.
* **Tailwind CSS** – Utility-first CSS framework for responsive UI.
* **shadcn/ui** – Customizable and accessible UI components.
* **TypeScript** – Type-safe JavaScript for better code reliability.
* **Sentry** – Error tracking and performance monitoring.
* **Vapi** – Voice AI platform for real-time, multilingual interactions.
* **Zod** – TypeScript-first schema validation.

## 🔋 Features

* **AI Voice Agents** – Practice and learn with conversational AI tutors.
* **Authentication** – Secure login/signup with Clerk.
* **Subscriptions & Billing** – Managed via Stripe integration.
* **Bookmarks & History** – Organize sessions and resume learning.
* **Create Tutors** – Customize AI tutors based on subject and style.
* **Cross-Device Support** – Fully responsive across all devices.
* **Real-time Database** – Powered by Supabase.
* **Modern UI** – Built with Tailwind CSS and shadcn/ui.
* **Search & Filters** – Quickly find tutors or topics.
* **Modular Codebase** – Reusable components and scalable structure.

## 🤸 Quick Start

Follow the steps below to set up the project locally:

### Prerequisites

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/)
* [npm](https://www.npmjs.com/)

### Clone the Repository

```bash
git clone https://github.com/your-username/saas-app.git
cd saas-app
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file in the root directory and add:

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

Replace each placeholder with your actual project credentials.

### Run the Project

```bash
npm run dev
```

Visit `http://localhost:3000` in your browser to see the app in action.

## 🚀 More

Future improvements could include:

* Admin dashboard for managing tutors
* Real-time chat with AI tutor memory
* Email integration and session reminders
* Advanced analytics for users and admins

---

### 👤 Contributor

Originally inspired by a tutorial from JavaScript Mastery.
