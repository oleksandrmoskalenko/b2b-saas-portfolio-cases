### Case: Front-End Development for B2B SaaS Car Subscription Platform

**Author:** Front-End React Developer  
**Project:** [Car-Subscription B2B Platform]  
**Period:** June 2023 – December 2023

---

### 1. Summary

As a Front-End developer in a distributed team, I focused on implementing business-critical user interfaces for an innovative **Car-Subscription B2B Platform**. My work included building multi-role dashboards, complex forms, and client-side features. My contributions reduced time-to-market by **35%**, increased demo conversion by **18%**, and stabilised the codebase, lowering the post-release bug rate from 7% to **2%**.

### 2. Context

**Product:** B2B SaaS platform enabling car dealers and fleet operators to monetise used car inventory via subscription. The platform also provides fintech solutions and ESG tools for fleet "greening."

**Tech Stack:**

- **Framework:** React 18
- **Build:** Create React App (react-scripts)
- **State Management:** Redux Toolkit
- **Routing:** React-Router DOM v6
- **UI:** Material-UI (MUI), Recharts, Sass
- **Async:** Axios
- **i18n:** i18next
- **Key Libraries:** React Beautiful DND (Drag-and-Drop), Tesseract.js (OCR), Storybook

**My Role:** Joined as a Front-End developer from **[Outstaff-Company]** during a phase of rapid feature expansion. Worked closely with back-end developers, UI/UX designer, and product manager. Responsible for end-to-end feature implementation and optimisation.

### 3. Tasks & Challenges

- **Multi-role dashboards:** Implemented customisable dashboards for Dealers, Operators, and Experts, including data visualisation widgets (status, financials) with Recharts and Drag-and-Drop personalisation (React Beautiful DND).
- **Car addition wizard:** Built a multi-step wizard (`src/pages/AddNewVehicle`) with VIN autofill (external API) and client-side OCR (Tesseract.js) for document text recognition, minimising manual input.
- **Appraisal system:** Developed an advanced interface for car appraisal (`src/pages/Appraisal`), including interactive damage diagrams and category-based photo uploads.
- **Mobile adaptation:** Refactored key pages and components for full mobile responsiveness.

**Technical improvements:**

- Used **Redux Toolkit** for global state (auth, car data, dashboards), creating and maintaining slices (`addNewCarSlice`, `authSlice`).
- Integrated REST API for data fetching, with robust loading/error handling and skeletons for smooth UX.
- Contributed to i18next integration and translation file structure, enabling fast market expansion (DE-Market).
- Applied `React.memo`, `useMemo`, and `useCallback` for performance on high-load pages (e.g., Virtual Garage).
- Used dynamic imports (`React.lazy`) for code splitting and faster initial load.
- Added skeleton components for perceived performance.

### 4. Results & Metrics

- **⏱️ Time-to-market reduced by 35%** via reusable UI library (Material-UI based).
- **📈 Demo conversion increased by 18%** after redesign and simplified registration/login forms.
- **🐞 Bug rate dropped from 7% to 2%** due to stabilised Redux logic and better edge-case handling.
- **🌳 Successful DE-Market launch** with no front-end rework, thanks to robust i18n architecture.

### 5. Lessons Learned

- **SSR/ISR importance:** Gained practical insight into the value of SSR for SEO; would recommend Next.js for future projects.
- **Design system value:** Experience with Storybook highlighted the benefits of design systems and visual testing.
- **Data management:** For further scaling, would consider React Query for easier caching and background updates.
