# Placement Interaction and Tracking System (FSAD-PS14)

A production-level, investor-demo-ready placement management system built with React 18, Vite, Tailwind CSS, and integrated AI assistance.

## Features

### Role-Based Dashboards
- **Admin**: Manage users, employers, job categories, system settings, and view analytics
- **Student**: Browse jobs, apply, track applications, manage profile
- **Employer**: Post jobs, manage applications, update candidate status, view analytics
- **Placement Officer**: Track placements, monitor students/employers, generate reports

### Key Capabilities
- Secure authentication with role-based access control
- Protected routes with session persistence
- Responsive design (mobile, tablet, desktop)
- Real-time AI assistant powered by OpenAI (with mock fallback)
- Interactive charts and analytics
- Professional SaaS UI with smooth animations
- Complete CRUD operations for all entities

## Tech Stack

- **Frontend**: React 18, Vite
- **Styling**: Tailwind CSS
- **Routing**: React Router DOM v6
- **State Management**: Zustand
- **Charts**: Recharts
- **Icons**: Lucide React
- **AI Integration**: OpenAI API with Axios

## Installation

1. Install dependencies:
```bash
npm install
```

2. Create `.env` file (optional for AI features):
```bash
VITE_OPENAI_API_KEY=your_openai_api_key_here
```

3. Start development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## Demo Credentials

- **Admin**: admin@placement.com / admin123
- **Student**: student@placement.com / student123
- **Employer**: employer@placement.com / employer123
- **Officer**: officer@placement.com / officer123

## Project Structure

```
src/
├── components/
│   ├── layout/          # Sidebar, Navbar, LayoutShell
│   ├── ui/              # Reusable UI components
│   ├── ai/              # AI Assistant
│   └── ProtectedRoute.jsx
├── pages/
│   ├── admin/           # Admin pages
│   ├── student/         # Student pages
│   ├── employer/        # Employer pages
│   └── officer/         # Officer pages
├── context/             # Zustand store
├── routes/              # Route configuration
├── services/            # API services
├── data/                # Mock data
└── utils/               # Helper functions
```

## Features Breakdown

### Authentication
- Login/Register pages
- Role-based redirection
- Session persistence with localStorage
- Protected routes

### UI Components
- Card, Button, Badge, Modal, Table
- FormInput, Select, StatCard
- Responsive and accessible

### AI Assistant
- Floating chat button
- ChatGPT-style interface
- OpenAI integration with fallback
- Conversation memory
- Markdown support

### Analytics
- Bar charts, line charts, pie charts
- Real-time statistics
- Department-wise breakdowns
- Trend analysis

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT

## Author

FSAD-PS14 Team
