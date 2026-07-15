# Eliahna Studios — Privacy Policy (Pinterest app)

Static privacy policy page branded for **Eliahna Studios** / **eliahnnastudios**, ready for Pinterest developer app validation.

## Use this URL in Pinterest

After hosting (see below), paste one of these into the Pinterest app **Privacy policy URL** field:

- `https://YOURUSER.github.io/eliahnnastudios/`
- `https://eliahnnastudios-privacy.netlify.app/`
- `https://eliahnnastudios.YOURDOMAIN.com/privacy/`

The path or hostname must include **eliahnnastudios** (Pinterest rejected generic free-policy URLs that did not reference your brand).

## Fastest free host: Netlify Drop (no code required)

1. Open [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `eliahnnastudios-privacy` folder onto the page
3. After it deploys, open **Domain settings** → change site name to  
   `eliahnnastudios-privacy` (or anything with `eliahnnastudios` in it)
4. Your public URL will look like:  
   **`https://eliahnnastudios-privacy.netlify.app`**
5. Paste that URL into Pinterest as the Privacy Policy URL

## GitHub Pages (URL contains eliahnnastudios)

```bash
cd eliahnnastudios-privacy
git init
git add .
git commit -m "Eliahna Studios privacy policy"
# Create a public repo named: eliahnnastudios
# Then:
git branch -M main
git remote add origin https://github.com/YOURUSER/eliahnnastudios.git
git push -u origin main
```

In the repo: **Settings → Pages → Deploy from branch `main` / root**

Privacy policy URL:

`https://YOURUSER.github.io/eliahnnastudios/`

## Before you submit to Pinterest

1. Open the live URL in a private browser window — it must load over **HTTPS** with no login.
2. Update the contact email in `index.html` if `privacy@eliahnnastudios.com` is not a real inbox you monitor.
3. Paste the live URL into the Pinterest app form.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Full Privacy Policy page |
| `404.html` | Simple not-found page |
