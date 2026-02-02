# Deploy to Netlify - Step by Step

## Quick Deploy Method (Drag & Drop)

1. Go to: **https://app.netlify.com**
2. Sign in with GitHub (or create free account)
3. Click **"Add new site" → "Deploy manually"**
4. Drag and drop your portfolio folder here
5. Your site will be live instantly!

## Alternative: Connect GitHub Repository

1. Create repository: `Sarvardev035.github.io` on GitHub
2. Push your files:
   ```bash
   cd /home/sarvarbek/Desktop/portfolio
   git add .
   git commit -m "Portfolio ready for deployment"
   git push -u origin main
   ```
3. Go to **https://app.netlify.com**
4. Click **"New site from Git"**
5. Select your repository
6. Deploy automatically

## Your Portfolio Files

- ✅ index.html (Main portfolio)
- ✅ demos.html (Live demos page)
- ✅ demo-weight-calculator.html (Weight calculator)
- ✅ README.md (Documentation)

All files are ready to deploy!
