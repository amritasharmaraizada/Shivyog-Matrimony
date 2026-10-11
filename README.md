# ShivYog Matrimony (Demo)

A static, single-file demo of a verified, privacy-first matrimony platform for the Shivyog community.
Sample profiles are fictional. SYID verification is simulated (demo one-time code: `123456`).

## Run locally
Open `index.html` in a browser. No build step, no dependencies.

## Put it on GitHub
```bash
cd shivyog-matrimony-demo
git init
git add .
git commit -m "ShivYog Matrimony demo"
git branch -M main
git remote add origin https://github.com/<your-username>/shivyog-matrimony-demo.git
git push -u origin main
```

## Deploy on Vercel
1. Go to vercel.com, sign in, click **Add New > Project**, and import the GitHub repo.
2. Framework preset: **Other**. Build command: leave empty. Output directory: leave empty (root).
3. Click **Deploy**. Vercel gives you a public URL.

## Change the theme
Edit the colour variables at the top of the `<style>` block in `index.html` (`--primary`, `--deep`, `--bg`).

## Demo walkthrough
1. Join: any SYID of 5 to 14 letters/digits, any email, code `123456`, tick consent.
2. Create a profile and save to see ranked matches with "why" reasons.
3. Send interest to a profile that already liked you for an instant mutual match, or use "simulate their acceptance".
4. Try Report (3 reports hide a profile), Pause, Show my data, Delete my data.

## Before going live (not in this demo)
Real SYID verification via the SY portal or Ashram IT, a managed database, real email codes,
photo upload, and a privacy/legal review (India DPDP Act 2023 and rules for members abroad).
