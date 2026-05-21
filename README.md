# omnify-assessment
Assessment
# Omnify AI Service Store — Redesign Assessment

[cite_start]A high-fidelity HTML/CSS reimagining of the Omnify online registration experience[cite: 2, 4, 6]. [cite_start]This project transforms a traditional, filter-heavy booking process into an AI-first, intuitive storefront optimized to reduce cognitive friction and build deep trust for parents enrolling their kids in local activities[cite: 4, 5, 8, 9].

---

## 🚀 Live Project Deliverables

[cite_start]This repository contains all five required assessment deliverables, implemented entirely from scratch using clean semantic HTML5 and custom modular CSS3[cite: 45, 46, 47, 50, 51]:

1. [cite_start]**AI-First Storefront Discovery (`screen1-ai-store.html`)** [cite: 46]
   * [cite_start]Replaces rigid drop-down filters with an open, natural-language prompt box, instant predictive match meters, and an interactive AI recommendation strip[cite: 5].
2. [cite_start]**Guided Registration & Checkout Flow (`screen2-guided-registration.html`)** [cite: 46]
   * [cite_start]Demonstrates how conversation context seamlessly maps into pre-populated forms, flags smart sibling bundle discounts, and highlights optimal, personalized class schedules[cite: 8].
3. [cite_start]**AI Decision-Support Modal (`screen3-ai-decision-modal.html`)** [cite: 47]
   * [cite_start]A targeted intercept designed to proactively resolve a parent's point of highest anxiety: contrasting a "Trial Class" versus a "Monthly Membership" using an automated "AI Verdict" and contextual chat[cite: 8].
4. [cite_start]**B2B Marketing & Storytelling Assets** [cite: 50, 52]
   * [cite_start]**Asset 1 (`marketing1-landing-hero.html`):** A landing page hero mapping high-impact business value metrics through a clear "Before vs. After" contrast matrix[cite: 52].
   * [cite_start]**Asset 2 (`marketing2-product-storyboard.html`):** A sequential, 6-step product storyboard detailing the fluid, end-to-end user enrollment journey[cite: 52].
5. [cite_start]**AI Tools & Process Note (`process-note-ai-tools.html`)** [cite: 51]
   * [cite_start]A detailed project log outlining the technical execution, framework trade-offs, and microcopy iterations handled during the development window[cite: 51, 53].

---

## 🎨 Design System & Aesthetic Direction

Moving away from standard tech-SaaS blues and cold interfaces, this project relies on a **"Warm Editorial"** design framework modeled after modern parenting brands and boutique concierge services:

* **Typography System:** * Headline Accent: **Fraunces** (an optical-size serif loaded with character and warmth) to bring personality to headings, prices, and high-impact UI beats.
  * Body & Chrome UI: **DM Sans** (a clean, highly legible geometric sans-serif) for functional metadata, forms, and labels.
* **Intentional Color Palette:**
  * **Deep Teal (`#1B4D4A`)** — Establishes a foundation of trust, modern safety, and premium calm.
  * **Coral (`#E8623A`)** — Directs user attention via energetic, intentional focal points for primary CTAs and interactive highlights.
  * **Warm Cream (`#FAF7F2`)** — Serves as a soft, welcoming canvas that prevents the clinical aesthetic of pure white web layouts.
* **Humanizing AI Elements:** The system avoids using literal, robotic icons to represent artificial intelligence. Instead, it utilizes a subtle star/spark motif (`✦`) to signify supportive, non-intrusive background assistance.

---

## 💡 Core Product Thinking & UX Decisions

* [cite_start]**Natural Language Processing vs. Traditional UI Filters:** Parents often do not know the exact industry vocabulary (e.g., "Level 2 Swim Group")[cite: 8]. [cite_start]Allowing them to express themselves in plain language ("my 7-year-old loves water but has never taken formal lessons") allows the AI to parse intent and surface structured matches automatically[cite: 7].
* **Algorithmic Match Externalization:** Integrating percentage counters (e.g., `96% Match`) visually validates the engine's reasoning to the end user, transforming arbitrary recommendations into earned, data-backed choices at a single glance.
* [cite_start]**Context Preservation (Zero Duplicate Typing):** To compress the traditional drop-off funnel, information provided by the parent during initial text interactions passes straight into the registration state, filling child profiles and contact forms automatically to turn a 5-minute form into a 30-second checkout confirmation[cite: 5].

---

## 🛠️ Technical Stack & AI Workflow

* **Architecture:** 100% semantic HTML5 and vanilla CSS3 layouts using flexbox and grid components. The code is kept dependency-free (no heavy external frameworks like Bootstrap or Tailwind) to maximize execution speed and lighthouse rendering times.
* [cite_start]**AI Collaboration Tooling:** Developed in tandem with **Claude (Anthropic)** to iterate microcopy states, stress-test usability parameters against parent personas, and accelerate layout setups[cite: 51].
* **Aesthetic Assets:** Employs precise CSS color gradients, native styling parameters, and inline emojis to guarantee responsive UI layouts render instantly without the performance hit of heavy image assets.

---

## 📁 Local Execution Instructions

To interact with the high-fidelity screens locally on your computer, clone this repository and launch any index or screen file inside a standard web browser:

```bash
# Clone the project repository
git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)

# Navigate into the project folder
cd YOUR_REPOSITORY_NAME

# Open the primary discovery view in your default browser
open screen1-ai-store.html
