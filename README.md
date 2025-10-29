A modern full-stack social media platform built with the latest Next.js App Router architecture, featuring authentication, database integration, file uploads, and real-time updates. This project showcases advanced usage of Server Components, Server Actions, and API Route Handlers, while maintaining a clean and modular architecture.

🚀 Project Highlights
Feature	Description
🧩 Tech Stack	Next.js 14 (App Router), TypeScript, PostgreSQL, Prisma ORM, Clerk Authentication, TailwindCSS, Shadcn/UI, UploadThing
💻 Architecture	Built with Server Components, Layouts, Route Handlers, and Server Actions
🧠 Routing System	Uses Dynamic & Static Routes for user profiles, posts, and feeds
🔁 Data Handling	Includes Data Fetching, Caching, and Revalidation for performance optimization
🗃️ Database Integration	Fully managed through Prisma ORM connected to PostgreSQL
🔒 Authentication	Secured login/signup using Clerk (Email, Google, GitHub OAuth)
📤 File Uploads	Upload profile pictures and post media with UploadThing
🎨 UI/UX Styling	Designed using TailwindCSS and Shadcn/UI components for a clean and modern look
⚡ Optimistic Updates	Instant UI updates on actions like likes, comments, and follows using Server Actions
🧭 Error & Loading States	Implemented loading.tsx, error.tsx, and not-found.tsx for smooth UX
📡 API Integration	Handled using Next.js Route Handlers for both client and server communication
🔄 Revalidation	Leverages Next.js caching and ISR for dynamic content freshness
🧠 Core Features
🧍‍♂️ User Authentication & Profiles

Sign up, log in, and manage your profile using Clerk authentication.

View and edit your profile details, including name, username, and profile picture.

📰 News Feed

Displays posts from all users in reverse chronological order.

Supports real-time-like updates (optimistic UI).

✍️ Create & Manage Posts

Create text and media posts using an UploadThing-integrated form.

Edit or delete your own posts anytime.

❤️ Likes & Comments

Like/unlike posts instantly using Server Actions.

Comment on posts with real-time updates.

👥 Follow System

Follow/unfollow other users dynamically.

Personalized feed based on following relationships.

🔎 Search & Explore

Search users or hashtags dynamically using Server Components.

Explore trending posts and new users.

🧰 Tech Stack
Category	Tools Used
Framework	Next.js (App Router)
Language	TypeScript
Database	PostgreSQL
ORM	Prisma
Auth	Clerk
UI	TailwindCSS, Shadcn/UI
File Uploads	UploadThing
Hosting	Vercel / Railway / Render
Version Control	Git & GitHub

🔒 Authentication Flow (Clerk Integration)

User signs up or logs in via Clerk (supports Google & GitHub OAuth).

Auth state is globally available via Server Components.

Protected routes are wrapped with Clerk’s <SignedIn> and <SignedOut> components.

📤 File Uploads (UploadThing)

Integrated UploadThing for seamless profile and post image uploads.

Validations on file size, type, and storage path handled automatically.

Stored securely with public/private access control.

⚡ Server Actions & Optimistic UI

Server Actions are used for posts, likes, comments, and follows.

Updates appear instantly on the client via optimistic rendering.

Background revalidation keeps UI consistent with server data.

🎨 UI & Design

Built using TailwindCSS for responsive design.

Enhanced with Shadcn/UI components (modals, buttons, cards, alerts).

Clean dark/light theme integration.

Then open: http://localhost:3000
### Setup .env file
```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
DATABASE_URL=
UPLOADTHING_TOKEN=
```
### Run the app

```shell
npm run dev
```
