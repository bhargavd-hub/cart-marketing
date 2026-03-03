# CART° — E-Commerce Marketing Team Site

Built with **Next.js 14** (App Router) + TypeScript.

---

## 🚀 Deploy to Vercel (2 minutes)

### Option A — Vercel CLI (fastest)

```bash
# 1. Install Vercel CLI
npm i -g vercel

# 2. Install dependencies
npm install

# 3. Deploy (follow the prompts — all defaults are fine)
vercel

# 4. For production deployment:
vercel --prod
```

### Option B — GitHub → Vercel Dashboard

1. Push this folder to a GitHub repo:
```bash
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/YOUR_USERNAME/cart-marketing.git
git push -u origin main
```

2. Go to [vercel.com/new](https://vercel.com/new)
3. Import your GitHub repo
4. Click **Deploy** — Vercel auto-detects Next.js, no config needed ✅

---

## 🛠 Local Development

```bash
npm install
npm run dev
# → http://localhost:3000
```

## 📁 Project Structure

```
cart-marketing/
├── app/
│   ├── layout.tsx      # Root layout + metadata
│   ├── page.tsx        # Main page
│   └── globals.css     # All styles
├── components/
│   ├── Navbar.tsx
│   ├── Hero.tsx
│   ├── Work.tsx        # Filterable case studies
│   ├── Capabilities.tsx
│   ├── Team.tsx
│   ├── CtaFooter.tsx
│   └── ScrollReveal.tsx
└── README.md
```

## ✏️ Customization

- **Brand name**: Search for `CART` across files
- **Team members**: Edit `components/Team.tsx`
- **Case studies**: Edit the `CASES` array in `components/Work.tsx`
- **Colors**: CSS variables in `app/globals.css` under `:root`
