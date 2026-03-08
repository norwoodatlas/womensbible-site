# Women's Bible Website (Vercel)

This folder is a static site intended for Vercel deployment.

## Pages

- `/` - Home
- `/privacy` - Privacy Policy
- `/terms` - Terms & Conditions
- `/app-ads.txt` - AdMob app-ads.txt verification file

## Deploy Through GitHub + Vercel

1. Create a repo in your GitHub account (`norwoodatlas`) and push this project.
2. In Vercel, click **Add New Project** and import that repo.
3. Set **Root Directory** to `website`.
4. Framework Preset: **Other**.
5. Build Command: leave empty.
6. Output Directory: leave empty.
7. Deploy.

## Domain

After deploy:

1. Open project settings in Vercel.
2. Go to **Domains**.
3. Add `womensbible.vercel.app` (default) or your preferred custom domain.

If you specifically need `womensbible.vercel.xyz`, add that exact domain in Vercel and point DNS for `vercel.xyz` where applicable.

## AdMob Verification Notes

- Required for verification: `app-ads.txt` at the root URL (`https://<domain>/app-ads.txt`).
- This project includes:
  - Publisher line: `google.com, pub-2794944930580709, DIRECT, f08c47fec0942fa0`
  - Ad unit references:
    - `bfaw_banner` -> `ca-app-pub-2794944930580709/3168042905`
    - `bfaw_interstitial` -> `ca-app-pub-2794944930580709/5219491178`
- The ad unit IDs belong in your app's AdMob integration/config, not in Privacy/Terms content.
