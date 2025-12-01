# 🎨 Ajay's Portfolio - Minimal Design

![Project Status](https://img.shields.io/badge/status-live-success.svg)
![License](https://img.shields.io/badge/license-BSD%203--Clause-blue.svg)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat&logo=vuedotjs&logoColor=4FC08D)
![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=flat&logo=vuetify&logoColor=white)
![AOS](https://img.shields.io/badge/AOS-Animate_On_Scroll-blueviolet)

## 📖 About

**AjaysPortfolioMinimalDesign** is a lightweight, responsive personal portfolio website. 

Unlike complex modern web apps that require heavy build tools, this project leverages the power of **Vue.js** and **Vuetify** directly in the browser. It focuses on clean aesthetics, smooth scrolling animations, and ease of maintenance.

**Live Demo:** [https://ajays-portfolio-minimal-design.vercel.app](https://ajays-portfolio-minimal-design.vercel.app)

### ✨ Key Features

-   **💎 Minimalist Aesthetic:** Clean lines and plenty of whitespace using the Vuetify Material Design framework.
-   **⚙️ Config-Driven:** Easily update your bio, links, and projects by editing the `config.js` file.
-   **🎭 Smooth Animations:** Elements fade and slide into view using the **AOS** (Animate On Scroll) library.
-   **📱 Fully Responsive:** seamless experience across mobile, tablet, and desktop devices.
-   **⚡ Zero Build Step:** No `npm install`, `webpack`, or `vite` required. It runs natively in the browser.

## 🛠️ Tech Stack

-   **Frontend Engine:** [Vue.js](https://vuejs.org/) (Script inclusion)
-   **UI Framework:** [Vuetify](https://vuetifyjs.com/)
-   **Animations:** [AOS](https://michalsnik.github.io/aos/)
-   **Icons:** Material Design Icons
-   **Deployment:** Vercel (Static)

## 🚀 Getting Started

Since this project uses static libraries, running it is incredibly simple.

### Prerequisites

-   A modern web browser (Chrome, Firefox, Safari, Edge).
-   A code editor (VS Code) for making edits.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ajaykumarreddy-k/AjaysPortfolioMinimalDesign.git](https://github.com/ajaykumarreddy-k/AjaysPortfolioMinimalDesign.git)
    cd AjaysPortfolioMinimalDesign
    ```

2.  **Run the site:**
    -   Simply **double-click** `index.html` to open it in your browser.
    -   **Recommended:** Use the "Live Server" extension in VS Code to avoid any local CORS issues with loading images or scripts.

## ⚙️ Configuration

To customize the portfolio for yourself:

1.  Open `config.js` (or check the script section in `index.html` where data is defined).
2.  Update the objects for `profile`, `projects`, and `links` with your own information.
3.  Replace the `ajayportfolio-removebg-preview.png` with your own photo.

## 📂 Project Structure

```text
AjaysPortfolioMinimalDesign/
├── index.html              # Main application entry point
├── config.js               # (Optional) Data configuration file
├── style.css / styles      # Custom overrides
├── aos.js & aos.css        # Animation library files
├── vuetify.js & css        # UI Framework files
├── vue.js                  # Vue core framework
├── materialdesignicons...  # Icon fonts
└── assets/                 # Images and icons
