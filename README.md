# 🏢 ENKI Reality Admin Panel

## Cyprus Real Estate Platform - Admin Dashboard

A modern, feature-rich admin panel for managing real estate properties, projects, and developers in Cyprus. Specialized in new developments and Golden Visa eligible properties (≥€300,000).

## 🚀 Features

### Core Functionality
- 📊 **Advanced Dashboard** - Real-time KPIs and analytics
- 🏗️ **Project Management** - Developer → Project → Building → Property hierarchy
- 👥 **CRM System** - Lead management with AI-powered scoring
- 💰 **Commission Tracking** - Automated calculations and payment management
- 🏅 **Golden Visa Detection** - Automatic flagging of eligible properties
- 🌍 **Multi-language Support** - 8 languages (EN, FR, EL, RU, ES, IT, DE, NL)
- 📸 **Media Management** - Advanced image handling with Supabase Storage
- 📈 **Analytics & Predictions** - AI-powered insights and market trends

### Business Impact
- ✅ **Centralized Management** - Single source of truth
- ✅ **Process Automation** - Save 80% time on repetitive tasks
- ✅ **Data-Driven Decisions** - Real-time metrics and insights
- ✅ **International Ready** - Multi-language and multi-currency

## 🛠 Tech Stack

### Frontend
- **React 19** + **TypeScript** - Modern, type-safe development
- **Vite** - Lightning-fast build tool
- **Tailwind CSS** + **Shadcn/ui** - Beautiful, responsive UI
- **Framer Motion** - Smooth animations
- **React Query** - Server state management
- **React Hook Form** + **Zod** - Form handling and validation
- **React-i18next** - Internationalization

### Backend
- **Supabase** - PostgreSQL database with real-time subscriptions
- **Row Level Security (RLS)** - Fine-grained access control
- **Database Triggers** - Automated business logic
- **Edge Functions** - Serverless API endpoints

## 📁 Project Structure

```
enki-realty-admin/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/         # Admin panel pages
│   ├── hooks/         # Custom React hooks
│   ├── lib/           # Utilities and helpers
│   ├── styles/        # Global styles
│   └── types/         # TypeScript definitions
├── database/
│   ├── migrations/    # Supabase migrations
│   └── seeds/         # Sample data
├── public/           # Static assets
└── docs/            # Documentation
```

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- npm or yarn
- Supabase account

### Installation

```bash
# Clone the repository
git clone https://github.com/dainabase/enki-realty-admin.git
cd enki-realty-admin

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env.local
# Add your Supabase credentials to .env.local

# Run development server
npm run dev
```

## 📊 Database Schema

### Main Entities
- **developers** (21 records) - Real estate development companies
- **projects** (3 records) - Development projects
- **buildings** (13 records) - Individual buildings within projects
- **properties** (3 records) - Individual units/properties
- **leads** - Customer prospects and contacts
- **commissions** - Commission tracking and payments

### Key Features
- Automatic Golden Visa detection (≥€300,000)
- Multi-currency support (EUR, GBP, USD)
- VAT calculations (5% residential, 19% commercial)
- Commission automation (3-5% standard)

## 🌍 Supported Regions

- 🏙️ **Limassol** - Commercial and financial hub
- 🏖️ **Paphos** - Tourist and premium residential area
- ✈️ **Larnaca** - Near international airport
- 🏛️ **Nicosia** - Capital and administrative center
- 🌊 **Famagusta** - Emerging opportunities

## 📸 Screenshots

_Coming soon_

## 🔑 Environment Variables

```env
# Supabase
VITE_SUPABASE_URL=your-project-url
VITE_SUPABASE_ANON_KEY=your-anon-key

# Optional: Analytics
VITE_GA_ID=your-google-analytics-id
```

## 📝 License

Proprietary - ENKI Reality Cyprus

## 👥 Team

Developed for ENKI Reality Cyprus - Premium Real Estate Solutions

## 📞 Support

For support, email: support@enki-reality.com

---

**Project Status**: 🟢 Production Ready
- ✅ 20/20 Development steps completed
- ✅ 15+ Database tables with RLS
- ✅ 16 Functional admin pages
- ✅ 8 Languages fully supported
- ✅ 50+ Reusable React components