# Julia Set Explorer

Single-page visualization of Julia sets optimised for static hosting. The root of the project now contains an `index.html`, making it compatible with Vercel's static deployments out of the box.

## Deploying to Vercel

1. Install the Vercel CLI if you do not have it yet:
   ```bash
   npm install -g vercel
   ```
2. Authenticate:
   ```bash
   vercel login
   ```
3. From the project root, link or create a Vercel project (answer the prompts as needed):
   ```bash
   vercel link
   ```
4. Deploy. Use `vercel` for a preview or `vercel --prod` for production:
   ```bash
   vercel --prod
   ```

The included `vercel.json` pins the project name, declares the static build (no build command required), and ensures `/` serves `index.html`.
