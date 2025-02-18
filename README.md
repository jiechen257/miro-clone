<a name="readme-top"></a>

# Miro - Real-time collaboration, versatile canvas, rich media, secure.

![Miro Clone - Real-time collaboration, versatile canvas, rich media, secure.](/.github/images/img_main.png "Miro Clone - Real-time collaboration, versatile canvas, rich media, secure.")

## Getting Started

1. Make sure **Git** and **NodeJS** is installed.
2. Clone this repository to your local computer.
3. Create `.env.local` file in **root** directory.
4. Contents of `.env.local`:

```env
# .env.local

# disable next.js telemetry
NEXT_TELEMETRY_DISABLED=1

# deployment for convex
CONVEX_DEPLOYMENT=dev:convex-app-name # team: <your-team-name>, project: <your-project-name>

# convex deployment url
NEXT_PUBLIC_CONVEX_URL=https://convex-app-name.convex.cloud

# clerk auth keys
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
CLERK_SECRET_KEY=sk_test_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

# liveblocks api keys
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=pk_dev_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
NEXT_PUBLIC_LIVEBLOCKS_SECRET_KEY=sk_dev_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

```
