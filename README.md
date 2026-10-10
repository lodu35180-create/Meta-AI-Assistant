# Meta AI Assistant – Landing Page Clone

A responsive, pixel-perfect static clone of the official **Meta AI** landing page built with modern HTML5, Tailwind CSS, and Vanilla JavaScript in a single self-contained file.

---

## 📌 Overview

This project recreates the visual language, ethereal gradients, glassmorphism aesthetics, interactive mockups, and mobile preview cards of Meta AI's official product launch site. It showcases the versatility of Meta AI powered by Llama models across devices (web, mobile, smart glasses) and the Meta family of apps (WhatsApp, Instagram, Facebook, Messenger).

---

## ✨ Features

- **Ethereal Atmospheric Design:** Custom radial and conic gradients mirroring Meta AI’s signature glowing orbs and gradient rings.
- **Glassmorphic Navigation Bar:** Sticky top navigation bar with blur effect (`backdrop-filter: blur(16px)`), brand iconography, navigation links, and dynamic CTAs.
- **Interactive Hero Section:**
  - Phone frame with Dynamic Island chrome.
  - Realistic chat stream demonstrating prompt-to-response generation and simulated generative AI image carousels.
  - Floating prompt chip with micro-animations.
  - App Store, Google Play, and web trial badges.
- **Dynamic Feature Showcase:**
  - Interactive vertical accordion selector (Intelligent conversations, Custom image creation, Organization, Interactive learning).
  - Synchronized live device preview card that updates prompts, preview images, and AI responses in real time without page reload.
- **Chat Experience Tabbed Matrix:**
  - Tab navigation for *Full-feed chat*, *Attachments & files*, *Voice chat*, and *Photo edits*.
  - Dual phone mockups illustrating contextual text conversation (Kyoto travel itinerary) and multimodal visual analysis (salmon salad macro & calorie breakdown).
- **Ambient Ecosystem & Hardware:**
  - Feature banner card for **Ray-Ban Meta Smart Glasses** with dark photo overlay and quick action link.
  - Desktop web browser card previewing `https://meta.ai`.
  - App ecosystem grid cards for Facebook, WhatsApp, Instagram, and Messenger.
- **Meta AI for Business:** Dedicated section highlighting enterprise customer support response times, lead generation, and workflow scaling.
- **Interactive FAQ Accordion:** Expandable questions covering access instructions, model information, free tier availability, and `/imagine` generation syntax.
- **Open Source & Hardware Hub:** Highlighting Ray-Ban Meta smart wearables and Meta's open-source Llama foundation models.
- **Responsive Footer:** Multi-column layout with product links, research docs, company privacy guidelines, social icons, and language picker.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic web page structure and accessible UI |
| **Tailwind CSS (CDN)** | Utility-first responsive styling and layout system |
| **Vanilla JavaScript** | Accordion toggles, tab controls, dynamic card rendering |
| **Lucide Icons** | SVG icons across navigation, features, and phone mockups |
| **Google Fonts (Inter)** | Typography matching Meta's native design system |

---

## 🚀 Getting Started

Because the entire website is built into a single `.html` file with CDN dependencies, there are no build steps, Node packages, or bundlers required.

### Option 1: Direct File Open
1. Download or clone this repository.
2. Locate the file:
   ```text
   index.html
   ```
3. Double-click or open `index.html` in any modern web browser (Google Chrome, Safari, Mozilla Firefox, Microsoft Edge, Brave).

### Option 2: Run via Local Server (VS Code / Python)
For the best experience (e.g. testing with Live Server):

```bash
# Using Python 3 built-in HTTP server
python -m http.server 3000
```
Then visit:
```
http://localhost:3000
```

---

## 📁 File Structure

```text
├── index.html        # Complete webpage (HTML structure, CSS styles, JavaScript logic)
└── README.md         # Documentation and project overview
```

---

## ⚙️ JavaScript Interactions Included

1. **Feature Selector Switcher:** Listens for clicks on `.feature-item` elements, highlights the active tab, and replaces the right-hand preview panel's prompt, response, badge, and image assets dynamically.
2. **Chat Modes Tabs:** Allows switching between *Full-feed chat*, *Attachments*, *Voice*, and *Photo edits* with active state styles and contextual helper text updates.
3. **Accordion FAQ:** Handles single or multi-item expandable accordion menus with smooth CSS transitions and SVG caret rotation.

---

## 📱 Responsive Breakpoints

- **Mobile (< 640px):** Single-column layout, optimized phone mockups, hidden desktop links, stacked badges.
- **Tablet (640px – 1024px):** 2-column app ecosystem cards and dual-stacked showcase sections.
- **Desktop (≥ 1024px):** Side-by-side hero split, full sticky glassmorphic navigation, dual phone side-by-side display, and expanded footer grid.

---

## 📄 License & Disclaimer

This project is created strictly for educational and portfolio demonstration purposes as a visual recreation of the Meta AI landing page. All Meta brand trademarks, product names, logos, and related imagery belong to **Meta Platforms, Inc.**
