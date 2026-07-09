# Trackora - Real-time Location Tracking Application

A modern web application for real-time location tracking, analytics, and collaboration.

## Features

- **Real-time Location Tracking**: Track device locations in real-time using geolocation APIs
- **Interactive Maps**: View locations on an interactive map with live updates
- **Analytics Dashboard**: Comprehensive analytics and activity tracking
- **User Management**: Invite and manage team members
- **Privacy Controls**: Granular privacy settings and two-factor authentication
- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices

## Tech Stack

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Supabase Auth
- **Maps**: Google Maps API
- **UI Components**: Custom components with Radix UI

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn
- Supabase account
- Google Maps API key

### Installation

1. Clone the repository
```bash
git clone https://github.com/shashanks19102010-hue/Trackora-S.git
cd Trackora-S
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
cp .env.example .env.local
```

Fill in your Supabase and Google Maps credentials.

4. Run the development server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
trackoraS/
├── app/              # Next.js app directory
├── components/       # Reusable React components
├── lib/             # Utility functions and helpers
├── public/          # Static assets
├── supabase/        # Supabase configuration
└── types/           # TypeScript type definitions
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License - see LICENSE file for details
