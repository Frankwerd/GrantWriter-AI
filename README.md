# GrantWriter AI Frount End

**NOTICE: This project is a work-in-progress and is not yet complete. The code is provided as-is for demonstration and portfolio purposes.**

## 📖 About the Project

GrantWriter AI is a browser extension concept designed to serve as an AI co-pilot for grant proposal writing and management. The goal is to streamline the grant application process by leveraging AI to analyze funding opportunities, automate form-filling, and assist in tailoring proposal narratives to specific funders.

This repository contains the front-end and client-side logic for the browser extension, including the user interface components, content scripts for interacting with web pages, and the background service worker.

## ✨ Core Features (Current & Planned)

*   **Floating Action Button (FAB):** Injects a draggable button onto web pages for easy access.
*   **Side Panel UI:** A comprehensive user interface that opens in a side panel, allowing users to interact with the extension's features without leaving the current page.
*   **AI-Powered RFP Analysis:** Extracts key details from a Request for Proposal (RFP) webpage, such as funder priorities, eligibility, and deadlines.
*   **Master Organization Profile:** Users can create and save a detailed profile of their organization, including history, capabilities, and past projects. This profile serves as the master data source.
*   **AI-Assisted Autofill:** Analyzes web forms on grant application portals and intelligently fills in fields using data from the user's master profile.
*   **Proposal Tailoring:** (In Development) A feature to generate tailored proposal narratives by combining the master profile data with the analyzed RFP details.
*   **Guided First-Run Tutorial:** An interactive tour to guide new users through the initial setup and core features of the extension.

## 🛠️ Technology Stack

*   **Frontend:** HTML, CSS, JavaScript
*   **Browser Extension APIs:** `chrome.runtime`, `chrome.storage`, `chrome.scripting`
*   **AI Integration:** Google Gemini
*   **Core Libraries:** Chart.js (for data visualization in the popup)

## 🚀 Current Status

This project is currently in a developmental stage. Key functionalities like the side panel, AI-based RFP analysis, and the autofill engine are partially implemented. The UI is functional, but the backend integration and some advanced features like proposal tailoring are not yet complete. This repository is intended to showcase the architectural concept and front-end implementation.
