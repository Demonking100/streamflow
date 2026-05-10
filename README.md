Streamflow
A Netflix-inspired streaming platform built with Next.js, TypeScript, and Prisma. Streamflow replicates core Netflix features including authentication, browsing, and video playback — built as a learning project to explore full-stack development with modern tooling.

Tech Stack

Framework: Next.js 13 (Pages Router)
Language: TypeScript
Styling: Tailwind CSS
Auth: NextAuth.js with Prisma Adapter
Database ORM: Prisma
State Management: Redux Toolkit + React-Redux
Data Fetching: SWR
Video Playback: React Player
Notifications: React Hot Toast
Icons: Heroicons


Features

User authentication (sign up / sign in) with hashed passwords via bcrypt
Session management using NextAuth.js
Browse movies/shows with a Netflix-style UI
Video playback support via React Player
Global state management with Redux Toolkit
Responsive design with Tailwind CSS
Database-backed user and content storage via Prisma


Project Structure
streamflow/
├── components/     # Reusable UI components
├── hooks/          # Custom React hooks
├── lib/            # Utility libraries (prisma client, auth config)
├── pages/          # Next.js pages and API routes
├── prisma/         # Prisma schema and migrations
├── public/         # Static assets
├── screenshots/    # Project screenshots
├── store/          # Redux store and slices
├── styles/         # Global styles
└── utils/          # Helper functions
