# LiveDocs

A real-time collaborative document editor built with Next.js and Liveblocks, featuring GitHub authentication, multi-user editing, document management, comments, real-time presence indicators, notifications, and responsive design.

<p align="center">
  <img src="https://github.com/user-attachments/assets/507f6e00-d381-42f4-a466-9d79c6e46a8c" alt="Screenshot">
</p>

## Live Demo

Check out the live demo [here](https://live-docs-ks.vercel.app/).

## Tech Stack

- Next.js
- TypeScript
- Liveblocks
- Lexical Editor
- Shadcn
- Tailwind CSS

## Features

- Authentication: Secure sign-in/out and session management via NextAuth and Clerk.
- Collaborative Text Editor: Real-time multi-user document editing with live updates.
- Documents Management: Create, delete, share (via email or link with permissions), and list documents with search and sorting.
- Comments: Add inline and general comments with threaded discussions.
- Active Collaborators: Real-time presence indicators for collaborators.
- Notifications: Alerts for document shares, new comments, and collaborator activities.
- Responsive Design: Optimized for all devices.
- Undo/Redo: Allows for the undo or redo of prior actions, facilitating flexibility in design decision-making.
- Keyboard Actions: Provides users with the option to employ keyboard shortcuts for a range of actions, enhancing efficiency and accessibility.
- And numerous additional features, encompassing code architecture, advanced react hooks, and reusability.

## Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

**Cloning the Repository**

```bash
git clone https://github.com/kutaysahindev/live-docs.git
cd live-docs
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
LIVEBLOCKS_SECRET_KEY=
```

Replace the placeholder values with your actual credentials. You can get liveblocks credentials by signing up on the [Liveblocks website](https://liveblocks.io).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
