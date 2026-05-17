# Smart Court Booking Website

A frontend web platform for sports court booking and management. It provides role-based access (Admin, Owner, User), interactive schedule management, and online payment integration. This repository contains the frontend application only; the backend API is maintained separately.

## Preview

![Owner](./screenshots/owner.png)
![Admin](./screenshots/admin.png)
![Home](./screenshots/home.png)

## My Contributions (TniTni)

- **Owner schedule management dashboard** — calendar UI for owners to create, view, and update booking slots with availability display.
- **Admin management portal** — platform-wide management of users, venues, and role/permission settings.
- **RESTful API integration** — integrated with backend endpoints to fetch and update booking data across views.

## Features

- Role-based access control (Admin, Owner, User)
- Interactive calendar-based schedule management
- Secure online payment integration
- Responsive UI for mobile and desktop

## Technologies

| Category | Stack |
|---|---|
| Frontend | React, Vite |
| Styling | CSS Modules |
| State Management | React Context API |
| HTTP Client | RESTful API |
| Build Tool | Vite |
| Version Control | Git |

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm or yarn

### Installation

```bash
npm install
```

### Development

Run the dev server:

```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Linting

```bash
npm run lint
```

## Environment Variables

Create a `.env` file in the project root:

## Project Structure (partial)

```
src/
├── app/                # App entry and layout components
│   ├── components/     # Reusable UI components
│   └── pages/          # Page views (user/owner/admin)
├── routes/             # Route definitions
├── services/           # API calls and service wrappers
├── utils/              # Helper utilities
└── main.jsx            # App entry
```

## Scripts

- `npm run dev` — start development server
- `npm run build` — build production assets
- `npm run preview` — preview production build locally
- `npm run lint` — run ESLint

## Collaborators

- [TniTni](https://github.com/Tnitni) — Frontend Developer
- [PanpaKawaii](https://github.com/PanpaKawaii) — Frontend Developer

---

If you'd like, I can also:

- add a `.env.example` file with recommended variables,
- add a short CONTRIBUTING guide,
- or translate this README to Vietnamese.