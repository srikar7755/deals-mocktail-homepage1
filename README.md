# DealsMocktail - Next.js E-Commerce Homepage

A responsive, production-quality e-commerce homepage built with **Next.js 14**, **React**, **Tailwind CSS**, and **TypeScript**. Converted from Figma design specifications from the top of the page up to and including the **Today's Hottest Offers** section.

## 🚀 Live Demo & Links

- **Live Deployed URL**: [https://deals-mocktail-homepage1.vercel.app](https://deals-mocktail-homepage1.vercel.app)
- **GitHub Repository**: [https://github.com/srikar7755/deals-mocktail-homepage1](https://github.com/srikar7755/deals-mocktail-homepage1)

---

## ✨ Features & Component Breakdown

### 1. Navigation TopBar (`TopBar.tsx`)
- Custom vector logo matching `deal$` mocktail branding.
- Navigation links with smooth-scroll section anchors (`Latest Deals`, `Hot Deals`, `Top Savers`, `Categories`, `Blog`).
- Pill-shaped search bar with query clearing.
- User profile icon & shopping cart with active item counter badge.
- Mobile responsive menu drawer.

### 2. Category Stories (`CategoryStories.tsx`)
- Story-style avatar row for top categories (Fashion, Men's, Watches, Sneakers, Beauty, Home, Fitness, Tech).
- Gradient ring container with hover animations and active filter toggles.

### 3. Hero Section (`HeroSection.tsx`)
- Warm peach background container.
- `🔥 Limited Time Offer` pill badge.
- "Summer Sale Up to 70% Off" heading with vibrant gradient typography.
- CTAs ("Shop Now →", "View All Deals") with smooth scroll anchors.
- Key metrics counters (`500+ Active Deals`, `50K+ Happy Shoppers`, `4.8★ Rating`).
- Featured monochrome street-market banner image with floating badge.

### 4. Latest Deals (`LatestDeals.tsx`)
- Section header with "Freshly added deals on trending products" and "View All" outline button.
- 6 responsive product cards with discount tags, star ratings, strike-through pricing, and "Get Deal" buttons.

### 5. Today's Hottest Offers (`TodaysHottestOffers.tsx`)
- Full-width rich brand gradient background.
- `🔥 HOT DEALS` center pill badge and subtitle.
- 4 lightning-deal cards with live countdown timers, discount badges (`-50% OFF`), sales overlay (`📈 245 sold today`), green "You Save" highlights, and "Grab This Deal" action buttons.

---

## 🛠️ Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Deployment**: Vercel

---

## 💻 Instructions to Run Locally

### Prerequisites
Make sure you have **Node.js** (v18.0.0 or higher) and **npm** installed on your system.

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/srikar7755/deals-mocktail-homepage1.git
   cd deals-mocktail-homepage1
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```

4. **Open in browser**:
   Navigate to [http://localhost:3000](http://localhost:3000) to view the homepage.

---

## 📦 Build & Deployment

To build the project for production:

```bash
npm run build
npm run start
```

Deploy easily to **Vercel**:
1. Import your GitHub repository `srikar7755/deals-mocktail-homepage1` into Vercel.
2. Click **Deploy**. Vercel automatically detects Next.js and deploys your live site!
