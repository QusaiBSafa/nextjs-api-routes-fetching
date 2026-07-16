# Infrastructure Overview
This application uses Next.js to create a server-rendered React application with API routes.

# Data Models
- User: { id: number, name: string, email: string }
- Post: { id: number, title: string, body: string }

# API Design
- `GET /api/users`: Fetches user data from an external API.
- `GET /api/posts`: Fetches post data from an external API.

# Key Decisions
- Using Next.js API routes for simplicity and ease of deployment.
- Fetching data from public APIs to demonstrate functionality.