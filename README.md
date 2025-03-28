# Mission Fresh

## A Comprehensive Health & Wellness Platform

Mission Fresh is a cutting-edge application designed to support users on their journey toward better health, with a particular focus on smoking cessation and nicotine reduction. By combining behavioral science with modern web technologies, Mission Fresh delivers a personalized, mobile-first experience for tracking health metrics, managing cravings, and achieving wellness goals.

## ✨ Key Features

### 🔄 Holistic Health Tracking
- **Craving Tracker**: Monitor nicotine cravings, identify triggers, and track successful resistance strategies
- **Mood Tracker**: Log and visualize emotional states with trigger identification
- **Energy Tracker**: Track energy levels and correlate with lifestyle factors
- **Focus Tracker**: Monitor cognitive performance and productivity
- **Sleep Tracker**: Record sleep patterns and quality metrics
- **Step Rewards**: Earn rewards and incentives based on physical activity

### 📊 Advanced Analytics
- Real-time data visualization
- Correlation analysis between different health metrics
- Pattern recognition for behavior prediction
- Personalized insights and recommendations
- Progress tracking with milestone celebrations

### 📱 Mobile-First Experience
- Responsive design for all device sizes
- Touch gestures for intuitive navigation
- Haptic feedback for interactive elements
- Offline capabilities for uninterrupted usage
- PWA support for app-like experience

### 👥 Community & Support
- Progress sharing capabilities
- Friend connections and group challenges
- Success stories and community forums
- Expert advice and guidance
- Anonymous mode for privacy

### 🏆 Rewards & Gamification
- Step-based rewards system
- Achievement badges for milestones
- Partner discounts and special offers
- Unlockable content and features
- Points-based progression system

### 📚 Resource Library
- Educational content on health improvement
- Strategy guides for craving management
- Scientific articles on nicotine cessation
- Expert videos and tutorials
- Searchable FAQ database

### 🚬 Comprehensive Quit Support
- Support for all nicotine products: cigarettes, vaping, pouches, etc.
- Multiple quit methods: cold turkey, tapering, NRT
- Personalized quit plans based on usage patterns
- Product tracking and reduction goals
- Symptom management and relief strategies

### 🛍️ Smokeless Product Directory
- Comprehensive database of smokeless nicotine alternatives
- Detailed product information and comparisons
- User reviews and health ratings
- Country-specific availability details
- Affiliate links to trusted vendors

## 🛠️ Technologies

Mission Fresh is built using a modern tech stack:

- **Frontend**: React, TypeScript, Vite
- **UI Components**: Custom component library with shadcn/ui
- **State Management**: React Query, Context API
- **Animations**: Framer Motion
- **Backend Integration**: Supabase (Auth, Database, Storage)
- **API**: REST endpoints with TypeScript type safety
- **Mobile Integration**: Capacitor for native device features
- **Styling**: Tailwind CSS for utility-first styling
- **Testing**: Vitest, Testing Library

## 🚀 Getting Started

### Prerequisites
- Node.js 16+
- npm or yarn
- Supabase account (for backend services)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/mission-fresh.git
cd mission-fresh
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
```
Edit `.env.local` with your Supabase credentials.

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

5. Build for production:
```bash
npm run build
# or
yarn build
```

## 🏗️ Architecture

Mission Fresh follows a micro-frontend architecture pattern for scalability and maintainability:

- **Core**: Authentication, user management, and shared utilities
- **Health**: Components for tracking various health metrics
- **Community**: Social features and user interactions
- **Resources**: Educational content and reference materials
- **Rewards**: Gamification and incentive systems

### Key Design Principles:

1. **Component-First Architecture**: Modular, reusable components
2. **Type Safety**: Comprehensive TypeScript coverage
3. **API Standardization**: Consistent REST API patterns
4. **Mobile Optimization**: Performance-focused for mobile devices
5. **Accessibility**: WCAG compliance for inclusive user experience
6. **Offline Capability**: Service workers for offline functionality
7. **Security**: End-to-end data protection and privacy controls

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For questions or support, please contact [support@missionfresh.io](mailto:support@missionfresh.io). 