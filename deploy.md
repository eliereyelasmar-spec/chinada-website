# Deploy CHINADA Website

## Before Deploying

**Update these in `index.html`:**

1. Search for `PASTE_YOUR_CONTRACT_ADDRESS_HERE` → Replace with actual contract
2. Search for `PASTE_TOKEN_ADDRESS` → Replace with token address (4 places)
3. Update Twitter handle if different from `@ChinadaCoin`
4. Update Telegram link if different from `t.me/ChinadaCoin`

---

## Option 1: Vercel (Recommended - Free)

### Via CLI
```bash
npm i -g vercel
cd website
vercel
```

### Via Dashboard
1. Go to vercel.com
2. Sign up / Log in
3. Click "Add New Project"
4. Import from Git or drag & drop the `website` folder
5. Deploy

**Custom domain (optional):**
- Buy domain (Namecheap, GoDaddy, etc.)
- Add in Vercel dashboard → Settings → Domains
- Point DNS to Vercel

---

## Option 2: Netlify (Free)

### Drag & Drop
1. Go to netlify.com
2. Sign up / Log in
3. Drag the `website` folder onto the dashboard
4. Done - get your URL

### Via CLI
```bash
npm i -g netlify-cli
cd website
netlify deploy --prod
```

---

## Option 3: GitHub Pages (Free)

1. Create GitHub repo
2. Push `website` folder contents to repo
3. Go to Settings → Pages
4. Source: main branch, root folder
5. Save - get `username.github.io/repo-name` URL

---

## Option 4: Fleek (Web3/IPFS)

1. Go to fleek.co
2. Connect GitHub or upload folder
3. Deploy to IPFS
4. Get decentralized URL

---

## Suggested Domain Names

Check availability on Namecheap:
- chinada.io
- chinada.xyz
- chinada.lol
- chinada.wtf
- gochinada.com
- chinadacoin.com
- chinadatoken.com

**Budget option:** Use free Vercel URL like `chinada.vercel.app`

---

## After Deploying

1. Test the site on mobile
2. Update Twitter bio with website URL
3. Add website to Telegram group description
4. Update pump.fun profile if possible
