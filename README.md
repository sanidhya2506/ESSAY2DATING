# 📄 Essay2Dating 
### *Fall in love with a story, not a profile.*

---

## 🌐 Live Demo
The project is live and can be accessed here:  
👉 **[Essay2Dating – Live Project](https://sanidhya2506.github.io/ESSAY2DATING/index.html)**

> **Note:** This project has evolved from a Google Sheets MVP to a robust **Firebase Authentication** system for secure, verified user access.

---
## 📄 Research DOI

**Essay2Dating — (HCI Research Artifact)**

🔗 **DOI:** https://doi.org/10.5281/zenodo.18181271  

📚 *This repository represents a research software artifact archived on Zenodo to support transparency, long-term preservation, and scholarly citation.*

### 📖 Citation
If you use this work, please cite it as:
> Sanidhya Sharma. *Essay2Dating*. Zenodo. https://doi.org/10.5281/zenodo.18181271

---

## 🧠 What is Essay2Dating?
**Essay2Dating** is a minimalist, text-first dating experiment designed to solve "swipe fatigue." In a world of filtered photos and 150-character bios, we return to the depth of long-form prose. Here, connections are built on the architecture of a person's mind, not the pixels of their profile picture.

The platform encourages **slow dating**, self-reflection, and intentionality.

---

## ✨ Core Philosophy
* **No Swipes:** We prioritize reading over scrolling.
* **No Filters:** Character is the only metric that matters.
* **No Photos:** Fall in love with a story, not a profile.
* **Verified Character:** Real-world credibility through the "Vouch" system.
* **Anti-Ghosting:** High-intent entry barrier ensures meaningful conversations.

---

## 📄 The Workflow
The platform features a secure, gated user journey:

### 1. 🏠 Home (`index.html`)
The gateway. Introduces the "Slow Dating" manifesto. Now features a **Firebase Auth Modal** allowing users to Login via Google or Email/Password.

### 2. 📝 Write (`write.html`)
Verified members can submit their "Dating Essay." This is where users share their core beliefs, joys, and flaws. Access is restricted to logged-in users only.

### 3. 🤝 Vouch (`reference.html`)
Social proof is mandatory. Friends submit a character reference linked to the user's email. This appears at the bottom of the essay to verify the author's real-world personality.

### 4. 📚 The Reading Room (`read.html`)
A dynamic gallery of souls. It fetches stories from the database and renders them in an elegant, editorial layout. Users stay anonymous until they choose to accept a connection request.

---

## 🛠️ Technical Architecture
This project is built using a modern **Serverless Architecture** to handle user data and security.

* **Frontend:** HTML5, CSS3 (Custom Minimalist UI), Vanilla JavaScript (ES6+ Modules).
* **Authentication:** **Firebase Auth** (Google OAuth 2.0 & Email/Password with Verification).
* **Database:** **Firebase Firestore** (NoSQL) for real-time storage of essays and vouches.
* **Security:** Email verification gates and protected routes to ensure a high-quality community.
* **Deployment:** GitHub Pages.

---

## 🎨 Design Principles
* **Editorial Aesthetic:** High-contrast typography (System fonts) and generous white space.
* **Content-First:** No distracting UI elements; the text is the hero.
* **Privacy by Design:** No tracking. No public profiles. Contact details are hidden until mutual consent.

---

## 📦 Project Structure
```text
Essay2Dating/
│
├── index.html        # Landing Page & Auth Logic
├── write.html        # Essay Submission (Protected)
├── reference.html    # Character Reference Form
├── read.html         # The Reading Room (Data Feed)
├── README.md         # Documentation
└── LICENSE           # MIT License
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
