# URL Shortener Project

A URL Shortener is a service that generates a short, unique alias for a given long URL and redirects users to the original address when the shortened link is accessed.  
This project is built using **Bun** and **TypeScript** for both the backend and frontend, providing a fast and modern development environment.

---

## Technology Stack

### Frontend

| Technology     | Version | Purpose                 |
| -------------- | ------- | ----------------------- |
| **React**      | 18.x    | UI Framework            |
| **TypeScript** | 5.x     | Type Safety             |
| **Vite**       | 5.x     | Build Tool & Dev Server |

### Backend

| Technology     | Version | Purpose              |
| -------------- | ------- | -------------------- |
| **Bun**        | 1.x     | JavaScript Runtime   |
| **Express**    | 5.x     | Web Framework        |
| **TypeScript** | 5.x     | Type Safety          |
| **Redis**      | 7.x     | In-Memory Data Store |
| **CORS**       | 2.x     | Cross-Origin Support |

---

## Project Structure

```
url-shortener/
├── backend/                        # Backend application
│   ├── src/
│   │  ├── config/
│   │  ├── models/
│   │  ├── controllers/
│   │  ├── tests/
│   │  │   ├──integration/
│   │  │   └── unit/
│   │  ├── routes/
│   │  ├── services/
│   │  ├── middleware/
│   │  └── index.ts                   # Application entry point
│   ├── bun.lock                      # Dependency lock file
│   ├── package.json                  # Backend dependencies
│   └── tsconfig.json                 # TypeScript configuration
│
├── frontend/                         # Frontend application
│   ├── src/
│   │  ├── assets/
│   │  ├── components/
│   │  ├── hooks/
│   │  ├── styles/
│   │  ├── App.tsx                    # Root component
│   │  ├── index.css                  # Global styles
│   │  └── main.tsx                   # Application entry
│   ├── index.html                    # HTML template
│   ├── package.json                  # Frontend dependencies
│   ├── tsconfig.json                 # TypeScript configuration
│   └── vite.config.ts                # Vite configuration
│
└── README.md                         # This file

```

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/mistlady/URL-Shortener
cd URL-Shortener
```
