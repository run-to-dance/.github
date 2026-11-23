# Run To Dance — Next-Generation Social Dance Platform

Welcome to the official GitHub organization of **Run To Dance**, a multi-tenant SaaS platform created specifically for the global social dance community. Run To Dance streamlines event management for organizers of tango marathons, bachata festivals, salsa congresses, and West Coast Swing intensives, while delivering a seamless, frictionless ticket purchasing and check-in experience for dancers worldwide.

----

## 🌟 Vision & Domain Focus

Social dance events operate under fundamentally different logistics than traditional sports competitions or single-seat concerts. Organizing a multi-day dance weekend requires managing dynamic ticket passes, coordinating international artist lineups, balancing gender/role ratios, and processing hundreds of attendees at venue doors under low-light and poor network conditions.
Run To Dance eliminates administrative friction by replacing generic forms and complex spreadsheets with a purpose-built digital ecosystem:
* **Focused on Social Dancing:** Engineered specifically for festivals, marathons, and weekend intensives, bypassing the heavy scoring and heat-sheet complexities of competitive ballroom sports.
* **Balanced Dance Floor:** Automatically enforces gender and role ratios (Lead/Follow) to ensure a healthy dance experience for all attendees.
* **Zero-Friction Checkout:** Allows dancers to register and purchase passes instantly without forcing them to create platform accounts or remember passwords.
* **Resilient Field Operations:** Empowers on-site volunteers with mobile tools that function seamlessly even when internet connectivity drops.

---

## 🛠 Platform Capabilities Run To Dance unites event creation, marketing, registration, waitlist handling, and gate management into a unified workspace. 

### For Event Organizers

| Capability | Overview & Business Value | 
| :--- | :--- |
| **Multi-Tenant Management** | Manage multiple organizations, events, and venues under a unified administrative workspace with strict team role isolation. |
| **Visual Event & Pass Builder** | Configure flexible pass packages (Full Pass, Party Pass, Single Milonga) and dynamic registration forms tailored to each event's specific needs. | 
| **Automated Role Balancing** | Define maximum allowable role imbalances (Lead/Follow ratio). The platform automatically routes surplus registrations to an automated queue. | 
| **Automated Waitlist Management** | Automatically releases waitlisted passes as matching roles register or paired sign-ups occur, maintaining optimal dance floor balance without manual intervention. | 
| **Artist & Lineup Catalog** | Maintain a reusable library of international instructors, DJs, and orchestras with photos, bios, and social media links across all organization events. | 
| **Event Template Cloning** | Duplicate past events in one click—preserving pass structures, form schemas, and settings while starting fresh with a clean attendee list. | 
| **Multi-Currency Cash Counter** | Track door sales across multiple physical currencies with real-time change calculation and automated cashier balancing. |

### For Dancers & Participants

* **Guest Checkout:** Purchase passes in under two minutes via an intuitive, mobile-optimized registration flow. 
* **Instant Digital Tickets:** Receive secure transaction confirmations and encrypted digital tickets containing unique QR pass tokens delivered directly via email.
* **Role-Specific Pass Access** Clear visibility into pass inclusions, schedules, and role requirements prior to registration.

## 🚀 Product Roadmap & Release Strategy

The development of the Run To Dance platform is structured across four progressive phases, expanding from core ticketing to complete offline field autonomy and AI-powered automation.

### Phase 1: MVP Core (Foundational Registration &amp; Sales) * Multi-tenant organization setup and owner account initialization. 
* Event Master creation module (titles, descriptions, dates, custom URL slugs, and status toggles).
* Configurable registration form schema and non-interactive pass matrix configuration.
* Public Guest Checkout widget for account-free pass selection. * Automated ticket generation with unique QR pass tokens and transactional email delivery.

### Phase 2: Release-1 (Role Balancing &amp; Operations)
* Automated Lead/Follow balance tracking with configurable threshold constraints. 
* Automated Waitlist queue handling and instant release logic upon matching role entry.
* Reusable organization Artist &amp; Lineup catalog (instructors, DJs, orchestras).
* One-click event cloning for recurring marathons and festivals. 
* Integrated digital payment processing and platform fee management.

### Phase 3: Release-2 (Field Operations &amp; Offline Autonomy)
* Offline-first Progressive Web App (PWA) for gate volunteers and on-site staff.
* Rapid camera-based QR code ticket scanning with sub-50ms local verification.
* Dynamic wristband pairing: link anonymous barcode wristbands to attendee profiles on the fly upon arrival.
* Local ticket sales at venue doors with multi-currency change calculation.
* Gatekeeper security mode isolating check-in workflows from financial administration.

### Phase 4: Release-3 (AI Intelligence &amp; Global Ecosystem) 
* AI-assisted event generation: create event drafts, descriptions, and ticket structures from natural text prompts.
* Automated multilingual translation for international event landing pages with Edge caching.
* Embeddable, style-isolated Web Component widgets for external organizer websites.
* Integrated social media announcement tools and viral share kits.
* White-label branding controls and platform super-admin monitoring tools.

---

## 🌐 Ecosystem Architecture Overview Run To Dance is architected as an ultra-performant, edge-first web application designed for global speed and offline reliability:
1. **Client Layer:** Modular web interfaces built with modern reactive components and native web standards, optimized for dark-mode venue environments and mobile devices.
**Edge Services:** Global edge processing handling API routing, security rate limiting, media optimization, asset delivery, and instant language localization.
**Data &amp; Security Layer:** High-performance data engine utilizing strict organization-level data isolation, encrypted participant information, and blind indexing for rapid search.
**Field Execution Client:** Lightweight mobile PWA leveraging client-side offline storage and background sync to maintain continuous check-in throughput during network outages. 

---

## 🤝 Contributing &amp; Community Run To Dance is developed with a commitment to performance, elegance, and user empowerment.
**Issues &amp; Discussions:** Feel free to open issues or join discussions regarding feature requests, event workflows, or integration feedback.
**Code of Conduct:** We foster a respectful, inclusive environment for all dancers, organizers, and developers. 

---

*Powered by the Run To Dance Team. Connecting dancers and organizers worldwide.*