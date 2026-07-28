SWIFT BLADE HAIR — WEBSITE GUIDE
=================================
Plain-English instructions for Felix (or anyone helping him).
The same guide (with ready-to-use ChatGPT prompts) is built into the
bottom of the site itself — scroll past the footer or click
"Site Guide for Felix" in the footer.

---

WHAT'S IN THIS FOLDER
----------------------
  index.html            — The website. This is the whole site in one file.
  style.css             — All the colors, fonts, and layout.
  logo.png              — Your logo (web-sized copy).
  felix-salon.jpg       — The salon photo used in the About section.
  favicon.png           — The little icon browsers show in the tab.
  apple-touch-icon.png  — The icon iPhones use if someone saves the site.
  README.txt            — This file.

Keep all of these together in one folder — index.html needs its
neighbors to look right.

You can open index.html in any browser right now to preview the site.
Double-click it or drag it into Chrome, Firefox, or Safari.

---

LAUNCH CHECKLIST (DO ONCE, IN ORDER)
-------------------------------------
1. PREVIEW — double-click index.html. That's the site.

2. MAKE IT YOURS — use ChatGPT for any change (see "How to edit" below,
   or the guide built into the bottom of the site).

3. GET YOUR PERMANENT SQUARE BOOKING LINK
   Square Dashboard → Appointments → Online Booking → copy your booking
   page link (looks like squareup.com/appointments/...).
   The Book buttons currently point at your OLD Square website's booking
   page, which disappears in step 6 — swap in the permanent link first.
   (Ask ChatGPT: "Change every booking link from
   'swiftbladehair.com/s/appointments' to [your new link].")

4. PUT IT ONLINE, FREE
   Go to netlify.com/drop and drag this whole folder onto the page.
   Live in about 30 seconds. Make a free Netlify account so you can
   keep the site and update it later. Total cost: $0/month.

5. CONNECT SWIFTBLADEHAIR.COM
   Netlify → Domain settings → Add custom domain → swiftbladehair.com,
   then follow Netlify's DNS instructions at your domain registrar
   (wherever you pay for the domain — likely Square or GoDaddy).
   Takes 15 minutes to 24 hours. Your old site keeps working until the
   switch finishes — no gap.

6. CANCEL ONLY THE SQUARE ONLINE (WEBSITE) PLAN
   Once swiftbladehair.com shows the new site.
   KEEP SQUARE APPOINTMENTS — that's your booking, payments, and client
   list. Nothing changes for your clients.

7. UPDATE YOUR LISTINGS
   Point Instagram/TikTok bio links at the site, and make sure Square
   and your Google Business Profile both show 711 W Lake St — some
   listings still show the old Franklin Ave address.

---

HOW TO EDIT THE SITE (WITH CHATGPT)
------------------------------------
You don't need to know code:

1. Open index.html in Notepad (Windows) or TextEdit (Mac).
   Select all, copy.
2. Go to chat.openai.com and paste this prompt:

     I have a personal salon website as a single HTML file. I want to
     [describe your change]. Please give me the complete updated
     index.html file with that change made. Keep everything else
     exactly the same. Here is the current file:

     [paste the file]

3. Copy ChatGPT's updated file, paste it back into Notepad over the
   old contents, save. Double-click index.html to check it.
4. Publish: log into Netlify → your site → Deploys → drag this folder
   in again.

Tips:
  - Always say "keep everything else exactly the same."
  - Save a backup copy of index.html before every change.
  - If ChatGPT gives you only part of the file, ask for the complete file.

The bottom of the site has ready-made prompts for common changes:
hours, services, prices, photos, phone number, tagline, new sections.

---

THINGS YOU'LL PROBABLY WANT TO CHANGE
--------------------------------------
  YOUR PHONE NUMBER
    Search for: (952) 917-9269

  YOUR ADDRESS
    Search for: 711 W Lake St
    (It also lives in the maps links and the SEO data near the top
    of index.html — tell ChatGPT to update it "everywhere it appears,
    including the Google Maps links and the hidden SEO data.")

  YOUR HOURS
    Thursday – Sunday 11am – 6pm / Monday – Wednesday Closed.
    Hours appear in the hours table, the hero, the SEO data, AND the
    little "Open now / Closed" badge is computed in the script at the
    bottom of index.html — tell ChatGPT to update all of them.

  THE BOOKING LINK
    Search for: swiftbladehair.com/s/appointments
    Replace with your permanent Square booking link (see checklist
    step 3). It appears in several places — replace all of them.

  THE TAGLINE
    Find: "Sharp cuts. Real vibes. Minneapolis made."
    It also scrolls in the ticker band under the hero — update both.

  SERVICES
    Look for the <ol class="services-grid"> section in index.html.

---

HOW TO ADD OR SWAP PHOTOS
--------------------------
1. Put your photo in this folder, named something simple (salon.jpg).
2. Ask ChatGPT: "Replace the salon photo (felix-salon.jpg) with
   salon.jpg. Keep everything else the same."
3. Portrait photos (taller than wide) look best in the About spot.

Note: logo.png here is a web-optimized copy of your logo (fast to
load). Keep your original full-resolution logo file safe somewhere
for print/merch use.

---

COLORS (in case you want to change them)
-----------------------------------------
Open style.css and look for the :root block near the top.

  --neon:   #39FF14   (your neon green — glows, accents, the ticker swords)
  --gold:   #C9A026   (the gold accent — main buttons)
  --bg:     #030303   (near-black background)
  --cream:  #F0EDE6   (main text color)
  --muted:  #8b857a   (secondary/faint text)

To change a color: replace the hex code (the # followed by 6
letters/numbers). Free picker: htmlcolorcodes.com

---

FONTS
-----
The site uses three Google Fonts (loaded automatically, no download):

  Cormorant SC    — The big display font (headings, ticker)
  Cormorant       — Italic serif (tagline, about lead text)
  Instrument Sans — Clean body font (navigation, labels, body copy)

To change fonts, pick one at fonts.google.com, copy its <link> tag,
replace the one in the <head> of index.html, then update the names
in the :root block of style.css.

---

QUESTIONS?
----------
If you get stuck, any web developer can look at these files and
understand exactly what's going on. The code is standard HTML and CSS —
no frameworks, no build tools, no mysteries.

Good luck, Felix.
Swift Blade. ⚔
