# Top of the Capital - Pool Player Ranking System

A dynamic pool player ranking system for Top of the Capital in Helena, Montana, designed to revolutionize local pool competition tracking and player engagement.

## Features

- Player rankings and statistics tracking
- Challenge system for competitive play
- Match history and results
- Tournament management
- User authentication and profiles
- Notification system for challenges and results

## Tech Stack

- **Frontend**: React, TypeScript, TailwindCSS, shadcn/ui
- **Backend**: Node.js, Express
- **Database**: PostgreSQL with Drizzle ORM
- **Authentication**: Passport.js

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- PostgreSQL database

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/top-of-capital-pool.git
   cd top-of-capital-pool
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory with the following variables:
   ```
   DATABASE_URL=postgresql://username:password@localhost:5432/topcapital
   SESSION_SECRET=your_session_secret
   ```

4. Run database migrations:
   ```bash
   npm run db:push
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure

- `/client` - Frontend React application
- `/server` - Backend Express server
- `/shared` - Shared types and schemas
- `/public` - Static assets

## License

[MIT](LICENSE)
