# Raguveer Sweets - Landing Page

## Before Hosting — Update These Values

### 1. WhatsApp Number
In `src/react-app/pages/Home.tsx`:
```
const WHATSAPP_NUMBER = '919999999999'; // Replace with real number
```

### 2. Instagram Handle
In `src/react-app/components/InstagramSection.tsx` and `Navbar.tsx`:
```
href="https://www.instagram.com/raguveer.sweets"  // Update handle
```

### 3. Phone Numbers in Branches
In `src/react-app/components/Branches.tsx`:
Replace the placeholder phone numbers with real ones.

### 4. Branch Addresses
In `src/react-app/components/Branches.tsx`:
Update the real addresses for each branch.

---

## Hosting on Netlify (Free)

### Option A — Drag & Drop (Easiest)
1. Run in terminal: `npm install && npm run build`
2. Go to [netlify.com](https://netlify.com) → Sign up free
3. Click "Add new site" → "Deploy manually"
4. Drag the `dist` folder into Netlify
5. Done! You get a free live URL.

### Option B — GitHub + Netlify (Auto-deploy)
1. Push this folder to a GitHub repository
2. Go to [netlify.com](https://netlify.com) → "Add new site"
3. Connect GitHub → Select your repo
4. Build settings are auto-detected from `netlify.toml`
5. Click Deploy → Live in 2 minutes!

---

## Local Development
```
npm install
npm run dev
```
Open http://localhost:3000
