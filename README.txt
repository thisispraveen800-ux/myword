# 🎂 Birthday Surprise — Setup Guide

## FOLDER STRUCTURE
```
birthday_project/
├── index.html           ← PAGE 1: Login Page
├── gallery.html         ← PAGE 2: Photo Collage
├── celebrate.html       ← PAGE 3: Gift Box + Cake + Celebration
├── birthday_premium.html ← PAGE 4: Full Birthday Website
├── photos/              ← CREATE THIS FOLDER — add your photos here
│   ├── photo_1.jpg
│   ├── photo_2.jpg
│   ├── ...up to photo_50.jpg
└── README.txt           ← This file
```

---

## STEP 1 — ADD YOUR PHOTOS
1. Create a folder called `photos` inside `birthday_project/`
2. Add up to 50 photos named exactly:
   photo_1.jpg, photo_2.jpg, ... photo_50.jpg
3. They will auto-load into the collage background.
   (If no photos found, beautiful colored gradient placeholders show instead)

---

## STEP 2 — ADD YOUR LEFT PANEL PHOTO (Login Page)
In `index.html`, find this line:
```html
<div class="lp-photo-placeholder">
```
Replace the entire div with:
```html
<img class="lp-photo" src="your-special-photo.jpg">
```

---

## STEP 3 — ADD YOUR OWN MUSIC (Optional)
Replace the SoundHelix demo links with your own MP3 files:

In `index.html`:   <source src="YOUR-SONG-1.mp3">
In `gallery.html`: <source src="YOUR-SONG-2.mp3">
In `celebrate.html`: <source src="YOUR-SONG-3.mp3">

Recommended: use romantic/soft music for login, upbeat for gallery, 
happy birthday melody for celebration.

---

## HOW TO OPEN
Just open `index.html` in any browser. 
⚠️ For photos to work, open from a LOCAL SERVER or just open directly
   (most browsers allow local file access).

Best option: Right-click index.html → Open with Chrome/Edge/Firefox

---

## PASSWORD
The password is: **9515618291**
(Wrong password shows: "Password is 10 digits — keep trying Gunduuuu 🥺💜")

---

## FLOW
1. index.html → Enter password → 
2. gallery.html → Photos + label (10s timer or double-click) →
3. celebrate.html → Click gift box → Cake + Crackers + Notifs →
   → Click "Open Your Surprise" →
4. birthday_premium.html → Full birthday website

---

## CUSTOMIZE NAMES
In `celebrate.html`, find the corner notification divs and edit the names:
- "Happy Birthday Bangaram"
- "Happy Birthday Nana"  
- "Happy Birthday Chandana"
- "Happy Birthday Gundu"
- "Happy Birthday Bujjju"
etc.

---

## TIPS
- Open on a laptop/desktop for full effect
- Use Chrome for best audio/animation support
- The music buttons are top-right of each page
- All pages are fully mobile responsive too!

Made with 💜 just for her.
