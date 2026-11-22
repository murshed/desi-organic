# Desi Organic 🌱

A modern, full-featured e-commerce platform for authentic, chemical-free organic food products. Built with React, TypeScript, Vite, Tailwind CSS, shadcn/ui, and Supabase.

---

## ✨ Features

- **Storefront & Catalog**: Browse organic products categorized into pure honey, cold-pressed mustard oil, bilona ghee, dates, nuts, and authentic spices.
- **Product Details & Reviews**: Rich product views with images, specifications, customer ratings, and testimonials.
- **Cart & Fast Checkout**: Streamlined cart drawer, coupon discount support, delivery zone fee calculator, and order placement.
- **Admin Dashboard**: Comprehensive back-office management including:
  - Product & category management
  - Order processing & status tracking
  - Coupon & promotional banner controls
  - Delivery zones & shipping rates
  - Sales analytics & reporting
  - Blog post & policy editor
- **Customer Support**: Integrated live chat widget and direct WhatsApp ordering support.
- **Modern Responsive Design**: Mobile-first design crafted with Tailwind CSS and Radix UI / shadcn components.

---

## 🛠️ Tech Stack

- **Frontend Framework**: [React 18](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) + [shadcn/ui](https://ui.shadcn.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **State & Data Fetching**: [TanStack Query (React Query)](https://tanstack.com/query)
- **Forms & Validation**: [React Hook Form](https://react-hook-form.com/) + [Zod](https://zod.dev/)
- **Backend & Database**: [Supabase](https://supabase.com/) (PostgreSQL, Authentication, Realtime, Storage)

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) or [Bun](https://bun.sh/)

### 1. Clone the repository

```bash
git clone https://github.com/murshed/desi-organic.git
cd desi-organic
```

### 2. Install dependencies

```bash
npm install
# or with bun:
bun install
```

### 3. Configure environment variables

Copy the example environment configuration:

```bash
cp .env.example .env
```

Open `.env` and fill in your Supabase credentials:

```env
VITE_SUPABASE_PROJECT_ID="your-project-id"
VITE_SUPABASE_PUBLISHABLE_KEY="your-anon-or-publishable-key"
VITE_SUPABASE_URL="https://your-project-id.supabase.co"
```

### 4. Start the development server

```bash
npm run dev
# or with bun:
bun run dev
```

Visit `http://localhost:8080` in your browser.

---

## 📦 Build for Production

To create an optimized production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

---

## 📁 Project Structure

```text
desi-organic/
├── public/                 # Static assets and icons
├── src/
│   ├── assets/             # Product and category images
│   ├── components/
│   │   ├── admin/          # Admin dashboard components & dialogs
│   │   ├── cart/           # Cart and checkout drawer
│   │   ├── chat/           # Live chat support widget
│   │   ├── home/           # Homepage sections (Hero, Features, Slider)
│   │   ├── layout/         # Header, Footer, Navigation
│   │   └── ui/             # Reusable shadcn/ui primitives
│   ├── hooks/              # Custom React hooks
│   ├── integrations/       # Supabase client and query helpers
│   ├── lib/                # Utility functions
│   ├── pages/              # Application views and routes
│   ├── types/              # TypeScript interfaces and definitions
│   ├── App.tsx             # Main routing and providers
│   └── main.tsx            # React application entry point
├── supabase/               # Supabase database migrations and configs
├── package.json
└── vite.config.ts
```

---

## 📄 License

This project is licensed under the MIT License.
