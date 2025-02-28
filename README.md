# FitnessZen: Health & Fitness Tracking Platform

FitnessZen is a comprehensive health and fitness tracking platform that helps users maintain their fitness goals by providing a unified dashboard for tracking workouts, nutrition, and progress.

## Features

### 1. Unified Dashboard
- All health metrics in one place
- Track workouts, nutrition, and progress
- Simple, easy-to-use interface

### 2. Smart Personalization
- Customized workout plans
- Personalized nutrition tracking
- Adaptive difficulty based on progress

### 3. Progress Tracking
- Visual progress charts
- Achievement system
- Regular progress reports

### 4. Community Features
- Share goals and achievements
- Join fitness challenges
- Connect with other users

## Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Supabase Auth
- **Charts**: Chart.js with React-Chartjs-2

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Supabase account

### Installation

1. Clone the repository
```
git clone https://github.com/yourusername/fitness-zen.git
cd fitness-zen
```

2. Install dependencies
```
npm install
```

3. Create a `.env` file in the root directory with your Supabase credentials
```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. Run the development server
```
npm run dev
```

5. In a separate terminal, start the backend server
```
npm run server
```

## Project Structure

```
fitness-zen/
├── src/                  # Frontend source code
│   ├── components/       # Reusable UI components
│   ├── contexts/         # React contexts
│   ├── pages/            # Application pages
│   ├── services/         # API services
│   └── types/            # TypeScript type definitions
├── server/               # Backend source code
│   └── index.js          # Express server
├── supabase/             # Supabase migrations
│   └── migrations/       # SQL migration files
└── public/               # Static assets
```

## Database Schema

The application uses the following database tables:

- `profiles` - User profile information
- `workouts` - User workout records
- `meals` - User meal and nutrition records
- `measurements` - User body measurements
- `posts` - Community posts
- `challenges` - Fitness challenges
- `challenge_participants` - Users participating in challenges

## License

This project is licensed under the MIT License.