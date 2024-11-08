# SyncBoard

SyncBoard is a Notion-style application built with Next.js 13, React, Convex, and Tailwind CSS, designed for a real-time collaborative document editing experience with rich management features.

## Key Features

- **Real-Time Database**: Instant updates across users and devices 🔗
- **Notion-Style Editor**: Rich text editing experience 📝
- **Light & Dark Mode**: Easily toggle between light and dark themes 🌓
- **Nested Documents**: Organize content with unlimited nested documents 🌲
- **Trash Can & Soft Delete**: Soft-delete documents with a trash can feature for recovery 🗑️
- **User Authentication**: Secure user authentication for personalized data 🔐
- **File Management**:
  - **Upload**: Attach files to your documents
  - **Delete**: Remove files when needed
  - **Replace**: Update existing files with new ones
- **Real-Time Document Icons**: Dynamic icons for each document, updating in real-time 🌠
- **Expandable Sidebar**: Effortlessly navigate documents with a collapsible sidebar ➡️🔀⬅️
- **Responsive Design**: Full mobile responsiveness for seamless access on all devices 📱
- **Web Publishing**: Publish notes to the web and share with a public link 🌐
- **Fully Collapsible Sidebar**: Hide and reveal the sidebar as needed ↕️
- **Landing Page**: Customizable landing page for a welcoming start 🛬
- **Cover Image Support**: Add personalized cover images to each document 🖼️
- **File Recovery**: Restore deleted files from the trash 📄🔄

## Prerequisites

- **Node.js**: Ensure you have Node.js v18.x.x installed.

## Getting Started

### Clone the repository:

```shell
   git clone https://github.com/AbhishekAggarawal/SyncBoard.git
```


### Install packages

```shell
npm i
```

### Setup .env file


```js
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### Setup Convex

```shell
npx convex dev

```

### Start the app

```shell
npm run dev
```
