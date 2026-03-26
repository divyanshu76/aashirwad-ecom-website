# ASHIRWAD — FINAL MASTER FIX + BRAND UPDATE (PRODUCTION READY)

## ⚠️ ABSOLUTE RULE

* DO NOT redesign UI
* DO NOT change layout
* ONLY fix + improve functionality + apply branding

---

# 🏷️ BRAND NAME UPDATE (VERY IMPORTANT)

## CHANGE EVERYWHERE:

❌ Aashirwad
✔ Ashirwad

Apply in:

* Navbar
* Footer
* Logo text
* Admin panel
* Loading screen
* Page titles

---

# ⏳ LOADING SCREEN FIX

## REQUIREMENTS:

* Text: Ashirwad
* Subtitle: Hampers

## ADD:

* smooth loading bar animation
* progress line should move (not static)

---

# 📱 MOBILE NAVBAR FIX

## PROBLEM:

search & cart icon misaligned

## FIX:

* align icons to right
* use flex properly

CSS:

.navbar {
display: flex;
justify-content: space-between;
align-items: center;
}

.nav-icons {
display: flex;
gap: 12px;
}

---

# 📱 MOBILE ADMIN PANEL FIX

## PROBLEM:

tabs not visible / not working

## FIX:

* make tabs horizontally scrollable

CSS:

.admin-tabs {
display: flex;
overflow-x: auto;
white-space: nowrap;
}

---

## ALSO FIX:

* clicking tabs should switch sections properly
* ensure JS event binding works on mobile

---

# 🎞️ HERO BANNER FIX

## PROBLEM:

one banner not showing + text unclear

## FIX:

* ensure all slides render properly
* add overlay for readability

CSS:

.hero::before {
content: "";
position: absolute;
background: rgba(0,0,0,0.2);
}

---

## IMAGE RULE:

* always use valid image URL
* no empty slides

---

# 🛍️ RELATED PRODUCTS FIX (CRITICAL)

## PROBLEM:

"You may also like" empty

## FIX:

1. filter by same category
2. exclude current product
3. limit: 4

IF no match:
→ show random products

---

## MUST SHOW ALWAYS

Even if:

* 1 product exists
  → show fallback products

---

# 🛒 PRODUCT PAGE FLOW

## AFTER PRODUCT DETAILS:

SHOW:

✔ Related products
✔ Trending products

---

# 🏷️ NEW CATEGORY ADD

## MENU ADD:

Wedding Items
→ Sehra
→ Kalgi
→ Mala

---

## SHOP BY CATEGORY ADD:

* Wedding Items block
* with image (Pinterest-style aesthetic)

---

# 🖼️ IMAGE RULE

* use only URL images
* high quality aesthetic images

---

# 📍 CONTACT DETAILS UPDATE

Email:
[ashirwadhampers@gmail.com](mailto:ashirwadhampers@gmail.com)

Phone:
+91 6284387804

Address:
New I.D.H Market, Amritsar, Punjab, India

---

# 🔄 REFRESH FIX

Add:

window.onload = () => {
window.scrollTo(0, 0);
};

history.scrollRestoration = "manual";

---

# 📦 PRODUCT DISPLAY FIX

* ensure all products render
* ensure images show
* ensure categories match

---

# ⚡ DATA SYNC

* admin changes → reflect instantly
* use localStorage everywhere

---

# 🎬 SCROLL ANIMATION

* smooth fade
* no jitter

---

# 🎯 FINAL GOAL

Make website:

✔ fully working
✔ mobile perfect
✔ brand consistent (Ashirwad)
✔ product recommendations working
✔ hero banner working
✔ admin working

WITHOUT changing design
