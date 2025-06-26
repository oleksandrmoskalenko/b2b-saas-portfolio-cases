### Case: Front-End Development for B2B Talent Marketplace

**Author:** Front-End React Developer  
**Project:** [Remote-Talent Marketplace]  
**Period:** January 2024 – March 2025

---

### 1. Summary

As a Front-End developer, I implemented a full redesign and expanded the functionality of the B2B **Remote-Talent Marketplace**. I focused on building key components, optimising performance, and delivering new user flows. My work reduced time-to-interview by **42%**, increased conversion by **21%**, and raised average order value by **15%** through a dynamic pricing calculator.

### 2. Context

**Product:** B2B marketplace enabling international SMB clients to hire remote IT specialists from **[UA-Tech-Hub]** with flexible pricing (from one day to full-time). The platform features a candidate catalogue, booking tools, and task management.

**Tech Stack:**

- **Framework:** Next.js 14 (App Router)
- **State Management:** Redux Toolkit, Redux Persist
- **UI:** Material-UI (MUI), Ant Design, Framer Motion
- **Styling:** Sass (SCSS)
- **API:** REST, Strapi (Headless CMS)
- **Key Libraries:** Swiper, react-infinite-scroll-component, Stripe.js

**My Role:** Throughout the project, I worked as a Front-End developer implementing the new design, developing core components, and supporting occasional contributors. My responsibilities covered the full development cycle—from component creation to deployment.

### 3. Tasks & Challenges

- **Specialist catalogue and candidate card (`/specialists`):** Built a high-performance catalogue with infinite scroll and advanced client-side filtering (Redux Toolkit).
- **Pricing table and calculator (`/pricing`):** Developed an interactive pricing table and real-time calculator for the basket, supporting flexible packages and discounts.
- **Interview basket & booking wizard:** Redesigned the interview basket and implemented a step-by-step booking wizard, including form validation and Stripe integration.
- **Promo pages:** Independently delivered several "turnkey" promo pages (e.g., Black Friday, Summer Sale, Voucher Page) with full logic, layout, and animation.

**Technical improvements:**

- Established a reusable UI component library for consistent design and faster feature delivery.
- Used Next.js dynamic imports and image optimisation for performance.
- Applied memoisation (`useMemo`, `useCallback`) in complex components.
- Managed state with Redux Toolkit and persisted user sessions/basket with redux-persist.
- Enhanced UX with Framer Motion animations on key pages/components.

### 4. Results & Metrics

- **⏱️ Time-to-interview reduced by 42%** after new basket and booking wizard release.
- **📈 Conversion "Visit → Add to Interview" up by 21%** due to improved catalogue and candidate cards.
- **🐞 Bug rate on production dropped from 6% to 1.8%** after component unification and logic stabilisation.
- **💰 Average order value increased by 15%** via intuitive dynamic pricing calculator.

### 5. Lessons Learned

- **Responsibility & growth:** This project strengthened my technical decision-making and ownership of implementation.
- **Next.js strengths:** Gained deep practical experience with Next.js for fast, SEO-optimised sites.
- **UI kit value:** Building a UI kit "on the fly" proved critical for scaling and consistency; would formalise this with Storybook in future projects.
- **Further optimisation:** For future iterations, would add structured data (JSON-LD) for SEO and consider RTK Query for server state management.
