# Health Lab Tracker

A modern health lab report tracking application built with React and Tailwind CSS, featuring a lime green (#d4e95e) and purple (#b3a8ff) theme.

## Features

- **Home Page**: Health score card with progress rings, key parameters grid, cholesterol trends chart, and AI-powered health insights
- **Reports Page**: Lab reports grouped by month with score circles and status badges
- **Trends Page**: Parameter cards with expandable charts and informational popups explaining each health marker
- **Upload Page**: Three upload options with helpful tips for adding lab reports
- **Profile Page**: User statistics and settings management
- **Health Score Detail**: Detailed breakdown showing calculation methodology and parameter contributions

## Tech Stack

- React 18.3
- Tailwind CSS 4.1
- Vite 6.3
- TypeScript
- Lucide React (icons)
- Recharts (data visualization)

## Design

All pages follow a consistent design pattern with:
- Purple rounded headers
- White rounded cards
- Glassmorphism bottom navigation bar
- Responsive layouts

## Getting Started

```bash
# Install dependencies
pnpm install

# Start development server
pnpm run dev

# Build for production
pnpm run build
```

## Project Structure

```
src/
├── app/
│   ├── components/
│   │   ├── Reports.tsx
│   │   ├── Trends.tsx
│   │   ├── Upload.tsx
│   │   ├── Profile.tsx
│   │   ├── AskAI.tsx
│   │   ├── HealthScore.tsx
│   │   └── ui/          # Radix UI components
│   └── App.tsx          # Main app with navigation
├── styles/
│   ├── theme.css
│   ├── fonts.css
│   └── tailwind.css
└── imports/             # Images and assets
```

## License

MIT
