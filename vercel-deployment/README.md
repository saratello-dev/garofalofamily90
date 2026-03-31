# Garofalo Family Form - Vercel Deployment

## Files Included
- `index.html` - The form (will be served at the root)
- `vercel.json` - Vercel configuration

## How to Deploy to Vercel

### Option 1: Drag & Drop (Easiest)
1. Go to https://vercel.com/new
2. Drag this entire `vercel-deployment` folder onto the page
3. It deploys automatically
4. You'll get a free `*.vercel.app` domain

### Option 2: Git-Based (Recommended)
1. Create a new GitHub repository
2. Push this folder to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
   git push -u origin main
   ```
3. Go to https://vercel.com/new and import the GitHub repo
4. Vercel auto-deploys on every push

### Option 3: Vercel CLI
1. Install Vercel CLI: `npm install -g vercel`
2. Run: `vercel`
3. Follow the prompts
4. Done!

## Form Submission
- Forms submit to **Formspree** (endpoint: `https://formspree.io/f/mpqyeydp`)
- Submissions go to your email automatically
- View all submissions at https://formspree.io (login with your account)

## Custom Domain
After deployment, connect a custom domain:
1. In Vercel dashboard, go to Project Settings → Domains
2. Add your domain (e.g., `garofalo90.com`)
3. Update DNS records as instructed

## No Cost
- Vercel hosting: Free
- Formspree forms: Free
- Custom domain: You pay for the domain only (~$10/year)
