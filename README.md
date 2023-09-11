# Fullstack Discord Clone: Next.js 13, React, Socket.io, Prisma, Tailwind, PostgreSQL

Features:

- Real-time messaging using Socket.io
- Send attachments as messages using UploadThing
- Delete & Edit messages in real time for all users
- Create Text, Audio and Video call Channels
- 1:1 conversation between members
- 1:1 video calls between members
- Member management (Kick, Role change Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (tanstack/query)
- Server creation and customization
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsivity and mobile UI
- Light / Dark mode
- Websocket fallback: Polling with alerts
- ORM using Prisma
- MySQL database using Planetscale
- Authentication with Clerk

### Prerequisites

**Node version 18.x.x**

### Install packages

```shell
pnpm i
```

### Setup Prisma

Add PostgreSQL Database (I used Supabase)

```shell
pnpx prisma generate
pnpx prisma db push

```

### Start the app

```shell
pnpm run dev
```

## Available commands

Running commands with pnpm `pnpm run [command]`

| command | description                              |
|:--------|:-----------------------------------------|
| `dev`   | Starts a development instance of the app |
