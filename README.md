# Coffee Street ☕

> A modern, aesthetic, and welcoming digital storefront for **Coffee Street Café & Roastery**.

Welcome to the official repository for the **Coffee Street** website. This project is a multi-page, information-rich web experience built to showcase Coffee Street's handcrafted beverages, artisanal bakery items, community news, origin stories, and direct customer communication channels.

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Website Pages & Features](#-website-pages--features)
- [Contact Details & Alternative Channels](#-contact-details--alternative-channels)
- [Project Structure](#-project-structure)
- [Tech Stack](#-tech-stack)
- [Getting Started & Local Setup](#-getting-started--local-setup)
- [Browser Compatibility](#-browser-compatibility)
- [Credits & Acknowledgments](#-credits--acknowledgments)

---

## 🌟 Overview

**Coffee Street** is crafted to provide a warm, inviting atmosphere online that mirrors the experience of walking into our café. The website delivers:

- An elegant preview of handcrafted coffees, teas, blended frappuccinos, and bakery items.
- Roasting roast profile guides for coffee enthusiasts brewing at home.
- News updates on weekly events, latte art workshops, and community initiatives.
- An interactive feedback system with direct and alternative contact details for customer inquiries.

---

## 📑 Website Pages & Features

### 1. Home (`index.html`)
- **Hero Section:** Warm welcome banner with social media links (Instagram, Facebook, Twitter) and smooth scroll navigation.
- **Story & Events Showcase:** Embedded media highlights featuring community activities, promotions, and fundraisers.
- **Animated Section Headers:** Smooth typography animations powered by [Anime.js](https://animejs.com/).
- **Promotional Pop-up:** Interactive promotional modal ("Buy 1 Free 1" offer) with dismiss controls.
- **Global Footer & Navigation:** Intuitive navigation bar and dropdowns for quick access to all pages.

### 2. Our Menu (`2-menu/menu.html`)
- **Video Header:** Atmospheric looping video header.
- **Drinks Collection:**
  - *Coffees:* Americano, Cappuccino, Caramel Macchiato
  - *Teas:* Black Tea, Chai Tea, Fruity Tea
  - *Blended Frappuccinos:* Caffe Vanilla, Caramel Brulee, White Choc Mocha
  - *Cold Drinks:* Fruity Refreshes, Organic Juices
- **Desserts & Bakery:** Fresh cakes, vanilla scones, croissants, sandwiches, and the signature **Coffee Street Blend**.
- **Coffee at Home (Roast Profiles):** Detailed tasting notes and profiles for Light Roast, Medium Roast, and Dark Roast beans.
- **Interactive UI:** Smooth hover-zoom animations on product photography.

### 3. News & Events (`3-news/news.html`)
- **Interactive Slideshow:** Carousel featuring weekly events, weekend custom latte art sessions, and new branch announcements.
- **Community & Safety Announcements:** Guidance on health, hygiene, and safe contactless delivery.
- **Live Covid-19 Statistics Widget:** Dynamic statistics tracker fetching real-time data from the `disease.sh` API.

### 4. About Us (`4-about/about.html`)
- **Brand Origin Story:** How Coffee Street grew from a humble sunset conversation over a cup of coffee into a beloved community roastery.
- **Animated Typography:** Sequential letter-reveal animations introducing the brand's philosophy.
- **Visual Storytelling:** High-resolution imagery depicting our craft and cafe ambiance.

### 5. Feedback & Support (`5-feedback/feedback.html`)
- **Dynamic Word Carousel:** Rotating aesthetic taglines (*Chill, Aesthetic, Exotic, Safe*).
- **Interactive Feedback Form:** Client-side form validation for name, email address, category selection, and message input.
- **Customer Alternative Contact Field:** Optional alternative contact input allowing visitors to leave an alternate phone number or email address.
- **Direct Contact Directory:** Prominently displays all official primary and alternative contact channels.

---

## 📞 Contact Details & Alternative Channels

We are always here to connect with our customers, partners, and community members:

| Channel | Primary Detail | Alternative Channel |
| :--- | :--- | :--- |
| **Email** | `hello@coffeestreet.com` | `support@coffeestreet.com` |
| **Phone** | `+60 3-7732 5060` | `+60 12-345 6789` |
| **Hotline** | `1300-88-7873` (Toll-Free) | `+60 3-7732 5060` |
| **Operating Hours** | Monday – Sunday: 8:00 AM – 10:00 PM | Public Holidays: 9:00 AM – 8:00 PM |
| **Mailing Address** | Coffee Street Roastery & Café<br>Lot 12, ABC Business Centre<br>Subang Jaya, 47500 Selangor Darul Ehsan<br>Malaysia | — |

---

## 📁 Project Structure

```text
Coffee-Street/
├── index.html                   # Homepage
├── index.css                    # Homepage styles
├── index.js                     # Homepage interactivity & navigation
├── README.md                    # Project documentation
│
├── 2-menu/                      # Our Menu page
│   ├── menu.html
│   ├── menu.css
│   ├── menu.js
│   ├── fonts/                   # Montserrat & Gaegu web fonts
│   ├── icon/                    # UI icons (social, arrows)
│   ├── image/                   # Drinks, bakes, and roast imagery
│   ├── logo/                    # Coffee Street logos
│   └── video/                   # Looping background video
│
├── 3-news/                      # News & Events page
│   ├── news.html
│   ├── news.css
│   ├── news.js                  # Slideshow & live API data fetch
│   ├── fonts/
│   ├── icon/
│   ├── image/
│   └── logo/
│
├── 4-about/                     # About Us page
│   ├── about.html
│   ├── about.css
│   ├── about.js                 # Anime.js animations
│   ├── fonts/
│   ├── icon/
│   ├── image/
│   └── logo/
│
├── 5-feedback/                  # Feedback & Contact page
│   ├── feedback.html            # Feedback form & contact details
│   ├── feedback.css             # Form styling & layout
│   ├── feedback.js              # Real-time form validation
│   ├── fonts/
│   ├── icon/
│   └── logo/
│
├── fonts/                       # Global font family assets
├── icon/                        # Global icon assets
├── image/                       # Global promotional imagery
├── logo/                        # Brand logo files
└── video/                       # Hero background video assets
```

---

## 🛠 Tech Stack

- **HTML5:** Semantic markup structure across all pages.
- **CSS3:** Custom typography, keyframes, transitions, flexbox, and grid layouts.
- **JavaScript (ES6+):** Dynamic DOM manipulation, form validation, and event handling.
- **jQuery 3.5.1:** Simplified DOM traversal, event handling, and navigation transitions.
- **Anime.js 2.0.2:** High-performance animation engine for smooth text and line transitions.
- **External REST API:** `disease.sh` API for real-time statistical data.

---

## 🚀 Getting Started & Local Setup

### Prerequisites
A modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari).

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aminnurrasyid/kopisenja.git Coffee-Street
   cd Coffee-Street
   ```

2. **Open in browser:**
   - Double click on `index.html` to open it directly in your web browser.
   
   *OR*

3. **Serve with a local static server (recommended):**
   - **Using Python 3:**
     ```bash
     python -m http.server 8080
     ```
     Then navigate to `http://localhost:8080` in your browser.

   - **Using Node.js (`serve`):**
     ```bash
     npx serve .
     ```

   - **Using VS Code Live Server:**
     Right-click `index.html` and click **"Open with Live Server"**.

---

## 🌐 Browser Compatibility

Tested and supported across modern evergreen browsers:
- Google Chrome (latest)
- Microsoft Edge (latest)
- Mozilla Firefox (latest)
- Apple Safari (latest)

---

## 👥 Credits & Acknowledgments

- Originally conceived as an academic web design project (INFO 2302) by:
  - Amin Nur Rasyid
  - Farisya Aqilah
  - Hilda Fadzir
  - Abdul Haziq
  - Muhammad Ihsan
- Modernized and enhanced under the **Coffee Street** brand.
