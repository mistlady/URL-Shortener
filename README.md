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
├── backend/                    # Backend application
│   ├── src/
│   │  ├── config/
│   │  ├── models/          #M in MVC
│   │  ├── controllers/
│   │  ├── routes/
│   │  ├── services/
│   │  ├── middleware/
│   │  └── index.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── README.md
│
├── frontend/                    # Frontend application
│ ├── src/
│ ├── package.json
│ ├── tsconfig.json
│ └── vite.config.ts
│
└── README.md




```
