# ScanCart for Trent (Zudio)

A fast, interactive product showcase & pitch web page for ScanCart for Trent / Zudio.

## Deployment to Vercel

### Option 1: Deploy via Vercel Dashboard (Connected to GitHub)
1. Push this repository to GitHub:
   ```bash
   git add .
   git commit -m "Prepare repository for Vercel deployment"
   git push origin main
   ```
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import the `rupendrajangid-dev/scancart-trent` repository.
4. Leave settings as default (Framework Preset: **Other**, Root Directory: `./`).
5. Click **Deploy**.

### Option 2: Deploy via Vercel CLI
Run the following in your terminal:
```bash
npx vercel
```
Follow the interactive prompts to log in and deploy. For production deployment:
```bash
npx vercel --prod
```