# Bible for Men Website (Vercel)

Static marketing + legal site for the iOS app.

## Pages
- `/` Home + app overview + metadata snapshot
- `/support` Support contact page
- `/privacy` Privacy policy
- `/terms` Terms and conditions
- `/app-ads.txt` AdMob app-ads verification file

## Deploy on Vercel
1. Push this `website` directory to GitHub.
2. Import the repo into Vercel.
3. Set project root to `website`.
4. Deploy.

## Domain
Use your production domain in App Store Connect (for example `bibleformen.app`).
If you are still using `thewomensbible.vercel.app`, this site content is already rebranded for Bible for Men.

## app-ads.txt
Keep this exact line in `website/app-ads.txt`:

`google.com, pub-2794944930580709, DIRECT, f08c47fec0942fa0`

Publish at your domain root:
- `https://<your-domain>/app-ads.txt`
