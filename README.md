# Regent's Allyship — putting it live on GitHub + Vercel

Two files, no build step, no code to run. You upload them to GitHub, point Vercel at the repo, and it gives you a public link. Everything below can be done from a phone browser.

## What's in here
- `index.html` — the quiz. This is what people land on.
- `resources.html` — the resources page. The quiz links to it at the end.

The quiz already links to the resources page (the "Explore the resources" button), so as long as both files sit in the same place, it all connects on its own.

## Step 1 — Put the files on GitHub
1. Go to github.com and sign in (make an account if you don't have one, it's free).
2. Tap the + (top right), then "New repository".
3. Name it something like `regents-allyship`. Set it to Public. Tap "Create repository".
4. On the next page tap "uploading an existing file".
5. Upload BOTH `index.html` and `resources.html`. Keep the names exactly as they are.
6. Tap "Commit changes".

## Step 2 — Connect Vercel
1. Go to vercel.com and tap "Sign up". Choose "Continue with GitHub" so the two are linked.
2. On the Vercel dashboard tap "Add New" then "Project".
3. Find `regents-allyship` in the list and tap "Import".
4. Don't change any settings. Vercel sees plain HTML and needs no build. Tap "Deploy".
5. Wait about a minute. You'll get a live link like `regents-allyship.vercel.app`.

That link is the thing you share. The QR code points at it too.

## Step 3 — The QR code
Once you have the Vercel link, send it to me and I'll generate a QR code in the brand colours that points to it, ready for posters and email. (A QR has to encode the real URL, so it has to come after the site is live.)

## Editing later, from your phone
Want to change a question or a reflection? You don't need any tools.
1. On GitHub, open `index.html`, tap the pencil icon.
2. The quiz text lives in the `QUESTIONS` list near the top. Edit the words between the quote marks.
3. Tap "Commit changes". Vercel redeploys automatically in under a minute.

## Custom address (optional)
If you'd rather it lived at something like `allyship.regents.ac.uk`, your IT team can point that name at Vercel in a few minutes. Vercel's "Domains" tab walks through it. Worth doing if this becomes a permanent campus resource rather than a Pride-month link.

---
A couple of things to check before you share it widely:
- I refreshed two links to their current homes: UK Black Pride now points to ukblackpride.org.uk, and PFLAG communities of colour to pflag.org/communities-of-color. Worth a quick tap to confirm they resolve for you.
- The Rose in both pages is the traced rosette, not your brand team's official SVG. If you can get the real file, it'll drop straight in.
