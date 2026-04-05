# B2 Suomi Harjoittelu

A Finnish B2 language learning platform with AI-powered writing feedback.

## Deploy to Vercel (free, 10 minutes)

### Step 1 — Get an Anthropic API key
1. Go to https://console.anthropic.com
2. Sign up or log in
3. Click "API Keys" → "Create Key"
4. Copy the key (starts with `sk-ant-`)

### Step 2 — Put the code on GitHub
1. Go to https://github.com and create a free account if you don't have one
2. Click "New repository" → name it `finnish-b2-platform` → click "Create repository"
3. Upload all these files to the repository (drag and drop in the browser, or use GitHub Desktop)

### Step 3 — Deploy on Vercel
1. Go to https://vercel.com and sign up with your GitHub account
2. Click "Add New Project"
3. Select your `finnish-b2-platform` repository
4. Click "Deploy" — Vercel auto-detects Next.js

### Step 4 — Add your API key
1. In your Vercel project → click "Settings" → "Environment Variables"
2. Add a new variable:
   - Name: `ANTHROPIC_API_KEY`
   - Value: your key from Step 1
3. Click "Save"
4. Go to "Deployments" → click the three dots on your latest deployment → "Redeploy"

### Done!
Your app is live at `your-project-name.vercel.app` — share that URL with anyone.

## Local development

```bash
npm install
cp .env.example .env.local
# Edit .env.local and add your API key
npm run dev
```

Open http://localhost:3000
