# The Care Next Door — Landing Page

Plain HTML/CSS/JS. No build step, no framework. This is a static site.

## Files
- `index.html` — the whole page
- `assets/` — poster, logo, and flyer images
- `fonts/AlteHaasGroteskBold.ttf` — the header font, embedded via @font-face

## Fonts
- **Headers** use Alte Haas Grotesk (the file in `/fonts`), a free font by Yann Le Coroller.
  It's fine to embed and ship as-is.
- **Body text** uses Source Sans 3 (loaded from Google Fonts), chosen as a free stand-in
  for Myriad. Myriad Pro is Adobe's proprietary font — embedding the actual Myriad file
  on a public website requires an Adobe Fonts web-license, which the desktop font file
  you have does not include. If NBCDI has (or gets) an Adobe Fonts subscription with a
  proper web project kit for Myriad, swap the Google Fonts link and `--font-body` variable
  for Adobe's kit code and Myriad will render correctly everywhere without any licensing risk.

## To edit
Open `index.html` in any text editor. Styles are in a `<style>` block near the top,
content further down.

## To go live on Vercel
1. Create a free account at vercel.com
2. Install the CLI: `npm install -g vercel`
3. From this folder, run: `vercel`
4. Follow the prompts (accept defaults — it's a static site)
5. Run `vercel --prod` to publish it as your production URL.

## Still placeholder / needs your input
- Watch section: YouTube video ID (search `REPLACE_WITH_YOUTUBE_ID` in index.html)
- "Watch the Trailer" / "Watch the Full Film" buttons currently point to `#`
- EveryAction/NGP VAN screening form is wired up and live as-is
