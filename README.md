# 📄 Essay2Dating 
### *Fall in love with a story, not a profile.*

---

## 🌐 Live Demo
The project is live and can be accessed here:  
👉 **[Essay2Dating – Live Project](https://YOUR-USERNAME.github.io/essay2dating)**

> **Note:** This is a serverless MVP using Google Sheets as a Headless CMS and Google Forms for data collection.

---

## 🧠 What is Essay2Dating?
**Essay2Dating** is a minimalist, text-first dating experiment designed to solve "swipe fatigue." In a world of filtered photos and 150-character bios, we return to the depth of long-form prose. Here, connections are built on the architecture of a person's mind, not the pixels of their profile picture.

The platform encourages **slow dating**, self-reflection, and intentionality.

---

## ✨ Core Philosophy
* **No Swipes:** We prioritize reading over scrolling.
* **No Filters:** Character is the only metric that matters.
* **No Photos:** Fall in love with a story, not a profile.
* **Vouched for:** Credibility through the eyes of friends.

---

## 📄 The Workflow
The project consists of four interconnected pages that form a complete user journey:

### 1. 🏠 Home (`index.html`)
The gateway. It introduces the "Slow Dating" manifesto and directs users to either join the movement or browse the archives.

### 2. 📝 Join (`create.html`)
Users submit a 300+ word essay about their thoughts, flaws, and obsessions. Data is captured via **Google Forms**, ensuring a secure and structured submission process.

### 3. 🤝 Vouch (`reference.html`)
Social proof is mandatory. Friends or colleagues submit a "vouch" for the user, adding a layer of trust and third-party perspective that self-descriptions often lack.

### 4. 📚 The Reading Room (`profile.html`)
A dynamic feed that fetches data directly from a **Google Sheet** via the CSV API. It renders essays into an elegant, editorial layout using the **Intersection Observer API** for scroll-animated reveals.

---

## 🛠️ Technical Architecture
This project demonstrates how to build a fully functional, data-driven web app without a traditional backend (Serverless/No-Code Backend).

* **Frontend:** HTML5, CSS3 (Custom Minimalist UI), Vanilla JavaScript.
* **Database (Headless CMS):** Google Sheets API.
* **Data Collection:** Google Forms (Embedded via Iframes).
* **Deployment:** GitHub Pages.
* **Interactions:** * **CSV-to-JSON Parsing:** Custom JS to fetch and display sheet data.
    * **Mobile Navigation:** Responsive "Hamburger" menu for mobile users.
    * **Connection System:** Mailto-integration for direct, consent-based connection requests.

---

## 🎨 Design Principles
* **Editorial Aesthetic:** High-contrast typography and generous white space.
* **Content-First:** No distracting UI elements; the text is the hero.
* **Fully Responsive:** Designed to feel like a digital book on mobile devices.

---

## 📦 Project Structure
```text
Essay2Dating/
│
├── index.html       # Landing Page & Manifesto
├── create.html      # Profile Creation (The Essay)
├── reference.html   # Social Proof (The Vouch)
├── profile.html     # The Reading Room (The Feed)
├── README.md        # Documentation
└── LICENSE          # MIT License
```
---

## 🚀 Why This Project Matters

- Challenges swipe-based dating culture
- Encourages honesty and self-reflection
- Introduces social proof via references
- Demonstrates strong **product thinking**
- Shows how meaningful MVPs can be built without backend complexity

Ideal as:
- A **portfolio project**
- A **startup MVP concept**
- A **product design case study**
- A **frontend-only experiment with real-world relevance**

---

## 🔮 Possible Future Enhancements

- Mutual consent-based contact reveal
- Essay filtering by values or interests
- Anonymous browsing mode
- Accessibility improvements
- Backend-powered messaging (optional)

---

## 👤 Author

**Sanidhya Sharma**  
Product Concept • Frontend • Minimal Design

---

## 🖤 Final Thought

Essay2Dating is not about dating faster.  
It’s about **understanding better**.

> *Read first. Feel later. Connect honestly.*
