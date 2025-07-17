<div align="center">

# 💳 Subscrybe - Advanced Subscription Management Platform

*Take control of your subscriptions with AI-powered insights and smart analytics*
*This is just the README file the Platform will be published as soon as everything is ready, so it includes mock sites or links for now, everything will be updated.*

[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-blue.svg)](./LICENSE)
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/)

### 🔗 Quick Links
[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-4285F4?style=for-the-badge)](https://subscrybe.vercel.app)
[![Download](https://img.shields.io/badge/📱_Download-00C851?style=for-the-badge)](https://github.com/yourusername/subscrybe/releases)
[![Documentation](https://img.shields.io/badge/📖_Docs-FF6900?style=for-the-badge)](./docs)
[![Support](https://img.shields.io/badge/💬_Support-7289DA?style=for-the-badge)](https://discord.gg/subscrybe)

</div>

---

## 📋 Table of Contents
- [Overview](#-overview)
- [Screenshots](#-screenshots)
- [Features](#-features)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [Quick Start](#-quick-start)
- [Configuration](#-configuration)
- [Development](#-development)
- [Architecture](#-architecture)
- [Services & Integrations](#-services--integrations)
- [Security](#-security)
- [Performance](#-performance)
- [Testing](#-testing)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)
- [Support](#-support)

## ✨ Overview

Subscrybe is a comprehensive subscription management platform that helps users track, analyze, and optimize their recurring subscriptions. Built with modern web technologies, it offers AI-powered insights, advanced analytics, and seamless integrations with multiple services.

### 🎯 Key Highlights
- **🤖 AI-Powered Insights** - Smart cost optimization and usage pattern recognition
- **📊 Advanced Analytics** - 12+ chart types with predictive forecasting
- **💰 Budget Management** - Category-based budgets with real-time alerts
- **🎁 Trial Management** - Auto-cancel functionality with value tracking
- **📱 Mobile-First Design** - Responsive interface optimized for all devices
- **🔒 Enterprise Security** - Advanced encryption and security monitoring
- **🌐 Multi-Platform** - Web, mobile, and browser extension support

## 📸 Screenshots

<div align="center">

### 🏠 Dashboard Overview
![Dashboard](docs/screenshots/dashboard.png)
*Real-time subscription overview with AI-powered insights*

### 📊 Advanced Analytics
![Analytics](docs/screenshots/analytics.png)
*Comprehensive analytics with 12+ chart types and predictive forecasting*

### 💰 Budget Management
![Budget Management](docs/screenshots/budget.png)
*Category-based budgets with real-time alerts and optimization suggestions*

### 👥 Family Sharing
![Family Sharing](docs/screenshots/family-sharing.png)
*Multi-user subscription management with cost splitting*

### 📱 Mobile Experience
<img src="docs/screenshots/mobile.png" alt="Mobile View" width="300">

*Fully responsive design optimized for mobile devices*

</div>

## 🚀 Features

### 🏠 Core Dashboard
- **Real-time Overview** - Live subscription metrics and spending analysis
- **Interactive Charts** - Recharts-powered visualizations with 12+ chart types
- **Smart Notifications** - Contextual alerts for renewals, price changes, and optimization opportunities
- **Quick Actions** - One-click subscription management and bulk operations

### 📊 Advanced Analytics
- **Cost Optimization Analysis** - AI-powered savings recommendations
- **Usage Pattern Recognition** - Behavioral insights and trend analysis
- **Renewal Prediction** - Smart forecasting for upcoming renewals
- **Budget Variance Tracking** - Real-time budget performance monitoring
- **Duplicate Detection** - Automatic identification of redundant services
- **Price Change Monitoring** - Historical price tracking and alerts

### 💰 Budget Management
- **Category-based Budgets** - Flexible budget allocation by service type
- **Real-time Alerts** - Instant notifications for budget overruns
- **Spending Forecasts** - Predictive spending analysis
- **Budget Optimization** - AI-suggested budget adjustments

### 🎁 Trial Management
- **Auto-cancel Setup** - Automated trial cancellation before billing
- **Value Tracking** - ROI analysis for trial subscriptions
- **Conversion Insights** - Trial-to-paid conversion analytics

### 👥 Family Sharing
- **Multi-user Support** - Shared subscription management
- **Permission Controls** - Granular access management
- **Cost Splitting** - Automatic expense allocation

### 🔔 Smart Notifications
- **Intelligent Alerts** - Context-aware notification system
- **Custom Rules** - User-defined notification triggers
- **Multi-channel Delivery** - Email, push, and in-app notifications

### 🔗 Integrations
- **Email Integration** - Automatic subscription detection from emails
- **Calendar Integration** - Usage pattern analysis from calendar events
- **Browser Extension** - Real-time subscription tracking while browsing
- **Payment Processors** - Stripe, PayPal, and Paddle integration
- **External APIs** - Webhook support for third-party services

## 🛠 Technology Stack

### Frontend
- **React 18** - Modern React with hooks and concurrent features
- **TypeScript** - Type-safe development with strict mode
- **Vite** - Lightning-fast build tool with HMR
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Accessible component primitives
- **Recharts** - Powerful charting library
- **React Query** - Server state management
- **Zustand** - Lightweight state management
- **React Hook Form** - Performant form handling
- **Zod** - Runtime type validation

### Backend & Services
- **Firebase** - Authentication and real-time database
- **Groq AI** - Advanced AI analytics and insights
- **Supabase** - PostgreSQL database with real-time features
- **Webhook Service** - Event-driven architecture
- **Smart Analytics Engine** - Custom AI-powered analytics

### Development Tools
- **ESLint** - Code linting and quality enforcement
- **Prettier** - Code formatting
- **Husky** - Git hooks for quality gates
- **Vitest** - Unit and integration testing
- **Playwright** - End-to-end testing
- **Storybook** - Component development and documentation

### Security & Monitoring
- **AES-GCM Encryption** - Data protection at rest
- **XSS/CSRF Protection** - Advanced security measures
- **Sentry** - Error tracking and performance monitoring
- **Security Monitor** - Real-time threat detection

## 📁 Project Structure

```
subscrybe-site-switch-main/
├── 📁 src/
│   ├── 📁 components/          # Reusable UI components
│   │   ├── 📁 ui/             # Base UI components (Radix UI)
│   │   ├── 📁 access/         # Access management components
│   │   ├── 📁 charts/         # Chart components
│   │   └── 📄 Layout.tsx      # Main layout component
│   ├── 📁 pages/              # Application pages
│   │   ├── 📄 Landing.tsx     # Landing page
│   │   ├── 📄 Index.tsx       # Dashboard
│   │   ├── 📄 Subscriptions.tsx
│   │   ├── 📄 Analytics.tsx   # (Deactivated)
│   │   └── 📄 Settings.tsx
│   ├── 📁 services/           # Business logic and API services
│   │   ├── 📄 apiService.ts   # Core API service
│   │   ├── 📄 integrationService.ts
│   │   ├── 📄 smartAnalytics.ts
│   │   ├── 📄 webhookService.ts
│   │   └── 📄 notificationService.ts
│   ├── 📁 hooks/              # Custom React hooks
│   │   ├── 📄 useFirebaseAuth.ts
│   │   ├── 📄 useBudgetManagement.ts
│   │   ├── 📄 useTrialManagement.ts
│   │   └── 📄 useUsageTracking.ts
│   ├── 📁 utils/              # Utility functions
│   │   ├── 📄 security.ts     # Security utilities
│   │   ├── 📄 accessibility.ts
│   │   ├── 📄 errorHandler.ts
│   │   └── 📄 performanceMonitor.ts
│   ├── 📁 store/              # State management
│   │   └── 📄 index.ts        # Zustand store
│   ├── 📁 types/              # TypeScript type definitions
│   │   ├── 📄 api.ts
│   │   ├── 📄 subscription.ts
│   │   └── 📄 analytics.ts
│   └── 📁 styles/             # Global styles and themes
├── 📁 public/                 # Static assets
├── 📁 docs/                   # Documentation files
│   ├── 📄 SETUP_CHECKLIST.md
│   ├── 📄 FIREBASE_SETUP_GUIDE.md
│   ├── 📄 INTEGRATION_SETUP.md
│   └── 📄 ADVANCED_FEATURES.md
├── 📄 package.json           # Dependencies and scripts
├── 📄 vite.config.ts         # Vite configuration
├── 📄 tailwind.config.js     # Tailwind CSS configuration
├── 📄 tsconfig.json          # TypeScript configuration
└── 📄 .env.example           # Environment variables template
```

## 🚀 Quick Start

<div align="center">

[![Download for Windows](https://img.shields.io/badge/Download_for_Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://subscrybe.com/download/windows)
[![Download for macOS](https://img.shields.io/badge/Download_for_macOS-000000?style=for-the-badge&logo=apple&logoColor=white)](https://subscrybe.com/download/macos)
[![Try Web Version](https://img.shields.io/badge/Try_Web_Version-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://app.subscrybe.com)

</div>

### Prerequisites
- **Node.js** 18+ and npm/yarn (for development)
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for cloud features

### 🔧 Development Setup

> **Note**: This is proprietary software. Development access requires authorization.

1. **Contact for access**
   ```bash
   # Request development access at: dev@subscrybe.com
   ```

2. **Install dependencies** (authorized developers only)
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   ```
   Edit `.env.local` with your authorized configuration values.

4. **Start development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open in browser**
   Navigate to `http://localhost:5173`

### 🎯 Essential Setup

For basic functionality, you need:
- **Firebase** - Authentication and database
- **Groq AI** (optional) - AI-powered insights

See [SETUP_CHECKLIST.md](SETUP_CHECKLIST.md) for detailed setup instructions.

## ⚙️ Configuration

### Environment Variables

Create a `.env.local` file with the following variables:

```env
# Core Configuration
VITE_APP_ENV=development
VITE_DEBUG_MODE=true

# Firebase (Required)
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id

# AI Integration (Optional)
VITE_GROQ_API_KEY=your_groq_api_key
VITE_AI_ENABLED=true

# Feature Flags
VITE_FEATURE_AI_INSIGHTS=true
VITE_FEATURE_FAMILY_SHARING=true
VITE_FEATURE_ADVANCED_ANALYTICS=true
```

See [.env.example](.env.example) for all available configuration options.

## 🔧 Development

### Available Scripts

```bash
# Development
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build

# Code Quality
npm run lint         # Run ESLint
npm run type-check   # TypeScript type checking
npm run format       # Format code with Prettier

# Testing
npm run test         # Run unit tests
npm run test:e2e     # Run end-to-end tests
npm run test:coverage # Generate coverage report
```

### Development Guidelines

1. **Code Style** - Follow ESLint and Prettier configurations
2. **Type Safety** - Use TypeScript strictly, avoid `any` types
3. **Component Structure** - Use functional components with hooks
4. **State Management** - Prefer React Query for server state, Zustand for client state
5. **Error Handling** - Use the centralized error handling system
6. **Performance** - Implement lazy loading and code splitting
7. **Accessibility** - Follow WCAG 2.1 AA guidelines

## 🏗 Architecture

### Component Architecture
- **Atomic Design** - Components organized by complexity
- **Composition Pattern** - Flexible component composition
- **Render Props** - Reusable logic sharing
- **Custom Hooks** - Business logic abstraction

### State Management
- **React Query** - Server state, caching, and synchronization
- **Zustand** - Client-side state management
- **Context API** - Theme and user preferences
- **Local Storage** - Persistent user settings

### Data Flow
```
User Interaction → Component → Hook → Service → API → Database
                                ↓
                           State Update → Re-render
```

## 🔌 Services & Integrations

### Core Services

#### API Service (`src/services/apiService.ts`)
- Centralized API communication
- Request/response interceptors
- Error handling and retry logic
- Type-safe API calls

#### Integration Service (`src/services/integrationService.ts`)
- Unified service coordination
- Health monitoring
- Configuration management
- Service initialization

#### Smart Analytics (`src/services/smartAnalytics.ts`)
- AI-powered insights using Groq
- Cost optimization analysis
- Usage pattern recognition
- Predictive analytics

#### Webhook Service (`src/services/webhookService.ts`)
- External webhook processing
- Event-driven architecture
- Retry logic and error handling
- Security validation

#### Notification Service (`src/services/notificationService.ts`)
- Multi-channel notifications
- Smart notification rules
- Delivery tracking
- User preferences

### Advanced Integrations

#### Email Integration (`src/services/emailIntegrationService.ts`)
- Gmail, Outlook, Yahoo support
- Automatic subscription detection
- Receipt parsing and analysis
- Privacy-focused processing

#### Calendar Integration (`src/services/calendarIntegrationService.ts`)
- Google Calendar, Outlook integration
- Usage pattern analysis
- Meeting-based subscription tracking
- CalDAV protocol support

#### Browser Extension (`src/services/browserExtensionService.ts`)
- Real-time subscription detection
- Website tracking and analysis
- Cross-browser compatibility
- Privacy protection

## 🔒 Security

### Security Features

#### Data Protection
- **AES-GCM Encryption** - Secure data storage
- **Password Security** - Strength validation and secure generation
- **Session Management** - Timeout and activity tracking
- **Secure Storage** - Encrypted localStorage implementation

#### Input Protection
- **XSS Prevention** - HTML sanitization and script blocking
- **SQL Injection Protection** - Pattern detection and sanitization
- **CSRF Protection** - Token generation and validation
- **Input Validation** - Advanced threat detection

#### Security Monitoring
- **Real-time Threat Detection** - SecurityMonitor class
- **Failed Login Tracking** - Brute force protection
- **Suspicious Activity Alerts** - Automated threat response
- **Security Event Logging** - Comprehensive audit trail

### Implementation
```typescript
// Security utilities usage
import { SecurityMonitor, encryptData, validateInput } from '@/utils/security';

// Initialize security monitoring
const monitor = new SecurityMonitor();

// Encrypt sensitive data
const encrypted = encryptData(sensitiveData);

// Validate user input
const isValid = validateInput(userInput, 'email');
```

## ⚡ Performance

### Optimization Features

#### Code Splitting
- **Route-based Splitting** - Lazy-loaded pages
- **Component Splitting** - Dynamic imports for heavy components
- **Vendor Splitting** - Optimized chunk strategy
- **Tree Shaking** - Dead code elimination

#### Caching Strategy
- **React Query** - Intelligent server state caching
- **Service Worker** - Offline functionality
- **Browser Caching** - Optimized asset caching
- **Memory Management** - Efficient state cleanup

#### Performance Monitoring
- **Web Vitals Tracking** - Core performance metrics
- **Bundle Analysis** - Size optimization
- **Runtime Monitoring** - Performance bottleneck detection
- **Error Tracking** - Performance-related error monitoring

### Performance Metrics
- **First Contentful Paint** - < 1.5s
- **Largest Contentful Paint** - < 2.5s
- **Cumulative Layout Shift** - < 0.1
- **First Input Delay** - < 100ms

## 🧪 Testing

### Testing Strategy

#### Unit Testing
- **Vitest** - Fast unit test runner
- **React Testing Library** - Component testing
- **Mock Service Worker** - API mocking
- **Coverage Reports** - Comprehensive test coverage

#### Integration Testing
- **Component Integration** - Multi-component testing
- **Service Integration** - API service testing
- **Hook Testing** - Custom hook validation
- **State Management Testing** - Store testing

#### End-to-End Testing
- **Playwright** - Cross-browser E2E testing
- **User Journey Testing** - Complete workflow validation
- **Visual Regression Testing** - UI consistency checks
- **Performance Testing** - Load and stress testing

### Running Tests
```bash
# Unit tests
npm run test

# E2E tests
npm run test:e2e

# Coverage report
npm run test:coverage

# Watch mode
npm run test:watch
```

## 🚀 Deployment

### Build Process
```bash
# Production build
npm run build

# Preview build
npm run preview

# Type checking
npm run type-check
```

### Deployment Platforms
- **Vercel** - Recommended for React applications
- **Netlify** - Alternative with great DX
- **Firebase Hosting** - Integrated with Firebase services
- **AWS S3 + CloudFront** - Enterprise-grade hosting

### Environment Configuration
```env
# Production environment
VITE_APP_ENV=production
VITE_DEBUG_MODE=false

# Security
CORS_ORIGIN=https://yourdomain.com
JWT_SECRET=your_production_jwt_secret

# Monitoring
SENTRY_DSN=your_production_sentry_dsn
```

## 🤝 Contributing

> **Note**: Subscrybe is proprietary software. Contributions are limited to authorized developers and partners.

### 🔒 Contribution Access

This project is **not open source**. Contributions are restricted to:
- **Authorized Developers**: Internal team members
- **Licensed Partners**: Approved third-party developers
- **Beta Testers**: Selected community members

### 📝 How to Get Involved

#### For General Users:
- **🐛 Report Bugs**: Use our [official support](Will be added)
- **💡 Suggest Features**: Submit via [feature requests](Will be added)
- **📖 Improve Documentation**: Contact [docs@subscrybe.com](Will be added)
- **🌍 Translations**: Join our [localization program](Will be added)

#### For Developers:
- **🤝 Partnership Program**: Apply at [partners@subscrybe.com](Will be added)
- **🧪 Beta Testing**: Join our [beta program](Will be added)
- **🔌 Plugin Development**: Review our [API documentation](Will be added)

### 📋 Development Guidelines

For authorized contributors:

#### Code Standards
- Follow TypeScript best practices
- Use ESLint and Prettier configurations
- Write comprehensive tests
- Document all public APIs

#### Security Requirements
- Sign Contributor License Agreement (CLA)
- Follow security review process
- Use approved dependencies only
- Implement proper error handling

#### Review Process
1. Create feature branch from `develop`
2. Implement changes with tests
3. Submit internal pull request
4. Pass security and code review
5. Merge after approval

### 📞 Contact for Contributions

- **Development Team**: [dev@subscrybe.com](martuk839@gmail.com)
- **Partnership Inquiries**: [partners@subscrybe.com](martuk839@gmail.com)
- **Security Issues**: [security@subscrybe.com](martuk839@gmail.com)

## 📄 License

This project is proprietary software owned by Subscrybe. See the [LICENSE](LICENSE) file for details.

```
Subscrybe - Proprietary Software License

Copyright (c) 2024 Subscrybe. All rights reserved.

This software is provided free of charge for personal and commercial use,
but remains proprietary software owned by Subscrybe.

Key restrictions:
- No modification or derivative works
- No redistribution or sublicensing  
- No reverse engineering
- No use for competing products

For full terms, see the LICENSE file.
For licensing inquiries: legal@subscrybe.com
```

---

## 📞 Support

<div align="center">

### 🤝 Get Help

[![Official Support](https://img.shields.io/badge/Official_Support-4285F4?style=for-the-badge&logo=google&logoColor=white)](Will be added)
[![Email Support](https://img.shields.io/badge/Email_Support-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](Will be added)

</div>

### 💬 Community & Support

- **🐛 Bug Reports**: [Report issues](Will be added)
- **✨ Feature Requests**: [Request features](Will be added)
- **💬 Community**: [Join Discord](Will be added)
- **📖 Documentation**: [Help Center](Will be added)
- **🔧 Setup Help**: [Setup Guide](Will be added)
- **📧 Direct Support**: [support@subscrybe.com](Will be added)

### 📚 Additional Resources

- [User Guide](Will be added) - Complete user manual
- [Video Tutorials](Will be added) - Step-by-step tutorials
- [FAQ](Will be added) - Frequently asked questions
- [System Status](Will be added) - Service status page
- [Release Notes](Will be added) - Latest updates

### 🏢 Business & Enterprise

- **Enterprise Sales**: [enterprise@subscrybe.com](mailto:enterprise@subscrybe.com)
- **Partnership Inquiries**: [partners@subscrybe.com](mailto:partners@subscrybe.com)
- **Media & Press**: [press@subscrybe.com](mailto:press@subscrybe.com)

---

<div align="center">

**⭐ Try Subscrybe today - Free for personal and commercial use!**

**Built with ❤️ by the Indie Developer**

[⬆ Back to Top](#-subscrybe---advanced-subscription-management-platform)

---

© 2025 Subscrybe. All rights reserved.

</div>
