# Domi App — SIRF PHONE se banana aur publish karna (koi computer nahi chahiye)

Achhi khabar: aapke paas sirf phone hai to bhi ye sab ho sakta hai। Bas
tareeka thoda alag hoga। Neeche diye steps ko order mein follow karein।

---

## ABHI AAPKO KYA KARNA HAI — Step 1: GitHub par account banayein

1. Phone ke Chrome browser mein jaayein: **github.com**
2. "Sign up" dabayein, apna email, password, username dalkar account banayein
   (bilkul free hai)
3. Email verify karein (jo email GitHub bhejega usme click karein)

## Step 2: Naya "Repository" banayein

1. GitHub mein login karke, upar "+" icon dabayein → **"New repository"**
2. Naam dein: `domi-app` (ya jo bhi pasand ho)
3. "Public" select rakhein
4. **"Create repository"** dabayein

## Step 3: Files upload karein

1. Jo `domi-pwa.zip` maine niche diya hai, usko phone mein download aur
   **extract/unzip** karein (phone mein file manager app se ho jaata hai, ya
   "Files" app mein unzip option hota hai)
2. GitHub ke repository page par, **"Add file" → "Upload files"** dabayein
3. Extract ki hui saari files select karke upload karein:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
4. Neeche "Commit changes" dabayein

## Step 4: GitHub Pages ON karein (ye aapki website live karega)

1. Repository ke andar, **"Settings"** tab dabayein
2. Left side mein **"Pages"** dhoondein aur dabayein
3. "Branch" ke neeche `main` select karein, folder `/ (root)` rakhein
4. **"Save"** dabayein
5. 1-2 minute wait karein, phir page reload karein — upar ek green link
   dikhega jaise: `https://aapkaUsername.github.io/domi-app/`

**Ye link hi aapki live website hai — isko browser mein khol kar test kar
sakte hain!**

---

## Step 5: Ise "App" ki tarah phone mein install karein (PWA)

1. Us link (`https://aapkaUsername.github.io/domi-app/`) ko Chrome mein
   khोlें
2. Upar-right corner mein 3-dot menu dabayein
3. **"Add to Home screen"** ya **"Install app"** dabayein
4. Confirm karein

**Bas! Ab aapke phone ki home screen par Domi ka apna icon hoga, bilkul ek
real app jaisa — click karke poori screen mein khulega, bina browser bar
ke।** Isko koi bhi apne phone mein isi link se install kar sakta hai।

Ye already ek "real app jaisa experience" hai — kai badi companies (jaise
Twitter/X, Starbucks) ye hi PWA tareeka istemal karte hain।

---

## Agar Play Store par bhi daalna hai (optional, agla step)

Agar aap chahte hain ki Domi Google Play Store par bhi list ho (taaki log
"Play Store" mein search karke inhi milein), to:

1. Phone browser mein jaayein: **pwabuilder.com**
2. Apni GitHub Pages wali link (`https://aapkaUsername.github.io/domi-app/`)
   waale box mein paste karein aur "Start" dabayein
3. Ye automatically check karega aur ek **"Package for Android"** button
   dikhayega — usko dabayein
4. Ek `.aab` file download hogi (ye phone mein hi ho jaata hai)
5. Ab **play.google.com/console** par jaayein (phone browser se hi):
   - Account banayein — **$25 one-time fee** (card/UPI se pay ho jaata hai)
   - "Create app" dabakar naam-description bharein (maine ye pehle se
     `play-store-listing.txt` mein likh diya hai, copy-paste kar dein)
   - Wahi `.aab` file upload karein jo pwabuilder se mili
   - Screenshots wahi lagayein jo maine banaye the
     (`screenshot-feed.png`, `screenshot-explore.png`, `screenshot-profile.png`)
   - Privacy Policy ke liye, apni GitHub Pages wali link mein hi
     `domi-privacy-policy.html` bhi upload kar dena, aur uska link yahan daal
     dena
   - Submit karein — Google 1-3 din mein review karke live kar dega

---

## Kaunsa step pehle karein?

**Sabse pehle sirf Step 1-5 karein** (GitHub + install as app) — ye free hai,
turant ho jaata hai, aur turant test kar sakte hain apne phone par. Play
Store wala hissa baad mein karna, jab sab kuch sahi chal raha ho.

Kisi bhi step par screen samajh na aaye, uska screenshot bhej dena — main
exact bata dunga aage kya dabana hai.
