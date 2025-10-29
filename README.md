🌐 Social Media App — Next.js, Prisma, PostgreSQL, Clerk & TypeScript
⚡ Overview

A modern full-stack social media platform built with the latest Next.js App Router architecture.

Features include authentication, database integration, file uploads, and real-time updates.

Demonstrates advanced usage of Server Components, Server Actions, and API Route Handlers.

Designed with a clean and modular architecture for scalability and performance.

🚀 Project Highlights

🧩 Tech Stack: Next.js 14 (App Router), TypeScript, PostgreSQL, Prisma ORM, Clerk Authentication, TailwindCSS, Shadcn/UI, UploadThing

💻 Architecture: Built with Server Components, Layouts, Route Handlers, and Server Actions

🧠 Routing System: Uses Dynamic & Static Routes for user profiles, posts, and feeds

🔁 Data Handling: Includes Data Fetching, Caching, and Revalidation for performance optimization

🗃️ Database Integration: Fully managed through Prisma ORM connected to PostgreSQL

🔒 Authentication: Secured login/signup using Clerk (Email, Google, GitHub OAuth)

📤 File Uploads: Upload profile pictures and post media with UploadThing

🎨 UI/UX Styling: Designed using TailwindCSS and Shadcn/UI components for a clean and modern look

⚡ Optimistic Updates: Instant UI updates on likes, comments, and follows using Server Actions

🧭 Error & Loading States: Implemented loading.tsx, error.tsx, and not-found.tsx for smooth UX

📡 API Integration: Handled using Next.js Route Handlers for both client and server communication

🔄 Revalidation: Leverages Next.js caching and ISR for dynamic content freshness

🧠 Core Features

🧍‍♂️ User Authentication & Profiles

Sign up, log in, and manage your profile using Clerk authentication

View and edit name, username, and profile picture

📰 News Feed

Displays posts from all users in reverse chronological order

Supports real-time-like updates with optimistic UI

✍️ Create & Manage Posts

Create text and media posts with UploadThing integration

Edit or delete your posts anytime

❤️ Likes & Comments

Like/unlike posts instantly using Server Actions

Comment on posts with real-time updates

👥 Follow System

Follow/unfollow other users dynamically

Personalized feed based on following relationships

🔎 Search & Explore

Search users or hashtags dynamically using Server Components

Explore trending posts and discover new users

🧰 Tech Stack

Framework: Next.js (App Router)

Language: TypeScript

Database: PostgreSQL

ORM: Prisma

Auth: Clerk

UI: TailwindCSS, Shadcn/UI

File Uploads: UploadThing

Hosting: Vercel / Railway / Render

Version Control: Git & GitHub

🔒 Authentication Flow (Clerk Integration)

User signs up or logs in via Clerk (supports Google & GitHub OAuth)

Authentication state is globally available via Server Components

Protected routes are wrapped with <SignedIn> and <SignedOut> components

📤 File Uploads (UploadThing)

Integrated UploadThing for profile and post image uploads

Validates file size, type, and storage path automatically

Files stored securely with public/private access control

⚡ Server Actions & Optimistic UI

Server Actions handle posts, likes, comments, and follows

Instant UI updates via optimistic rendering

Background revalidation ensures consistent data with the server

🎨 UI & Design

Built with TailwindCSS for responsive, modern design

Enhanced with Shadcn/UI components (modals, buttons, cards, alerts)

Includes clean dark/light theme integration

🧪 Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/yourusername/social-media-app.git
cd social-media-app

2️⃣ Install Dependencies
npm install

3️⃣ Setup Environment Variables

Create a .env file in the project root and add the following:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
DATABASE_URL=
UPLOADTHING_TOKEN=

4️⃣ Run the Application
npm run dev


Then open http://localhost:3000
 in your browser 🚀

