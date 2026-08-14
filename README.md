# LTD Media — Proposal Builder (Web App)

This is your proposal builder packaged as a real, deployable web app.
No app store needed — it runs in any browser at a URL you control.

---

## What you have

- A complete React app in this folder.
- Three builders: Business, Political Campaign, and Shows & Network.
- Client-ready 2-page proposals with your branding.
- Print / Save-as-PDF built in (works for both paper and email).

---

## How to run it on your own computer first (optional, to test)

You need Node.js installed (free, from nodejs.org). Then, in this folder:

1. Open a terminal in this folder.
2. Run: `npm install`  (this downloads what the app needs — one time)
3. Run: `npm run dev`
4. Open the link it prints (usually http://localhost:5173)

That's the app running locally. Change nothing — this is just to see it live.

---

## How to put it on the web (free, real URL)

The simplest path is **Vercel**. It's free for an app this size.

### Step 1 — Put the code on GitHub
1. Make a free account at github.com.
2. Create a new repository (call it `ltd-proposal-builder`).
3. Upload this whole folder to it. (GitHub's website has an "upload files"
   button, or use GitHub Desktop — the app — if you prefer clicking over typing.)

### Step 2 — Connect Vercel
1. Make a free account at vercel.com — sign in with your GitHub account.
2. Click "Add New Project."
3. Pick your `ltd-proposal-builder` repository.
4. Vercel auto-detects it's a Vite app. Just click "Deploy."
5. Wait about a minute. You get a live URL like
   `ltd-proposal-builder.vercel.app`.

That URL is your app. It works on any phone or computer browser.
Every time you update the GitHub code, Vercel redeploys automatically.

### Step 3 (optional) — Your own domain
If LTD wants `proposals.ltdmedia.net`, Vercel lets you add a custom
domain in the project settings. You (or whoever manages ltdmedia.net's
DNS) point a subdomain at Vercel. Free.

---

## Making it private (so it's not public on the open web)

Right now anyone with the URL can open it. If you want only you and
other reps to use it:

- Vercel has password protection (Settings → Deployment Protection).
  On the free plan this is limited; a paid plan ($20/mo) gives full
  password/login control for a team.
- For a competition demo, public is fine. Add protection later if it
  becomes a real internal tool.

---

## See NEXT-STEPS.md for the bigger decisions

Saving proposals, Slack integration, and client-vs-internal use are
covered there — those are real features but they change the app from
"static tool" to "app with a backend," which is a bigger step.
