<div align="center">

<!-- Official Site Logo -->
<img src="https://meghomeguards.gov.in/sites/default/files/logo_1_bigger.png" alt="Directorate of Civil Defence & Home Guards Logo" width="700px" style="margin-bottom: 20px;"/>

# 🏛️ Directorate of Civil Defence & Home Guards
### Government of Meghalaya, India

*Empowering citizens, ensuring safety, and coordinating disaster response across the state of Meghalaya.*

---

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-blue.svg?style=for-the-badge)](#)

</div>

---

## 🌐 Project Overview

Welcome to the modernized portal of the **Directorate of Civil Defence & Home Guards, Government of Meghalaya**. This repository contains a fully responsive, semantic, and highly optimized version of the official citizen services portal. It serves as an informative hub for the state's safety frameworks, emergency response structures, local administrative branches, notifications, acts, and statistical resources.

---

## ⚡ Key Highlights & Features

- **🎨 Unified Government Color Palette:** Custom warm brown theme (`#d3bca9` primary background and `#3b2212` text/nav accent) applied consistently across navigation headers, mega-menus, card headers, and footers.
- **📱 Dynamic Multi-Scale Header Logos:** Header logos (`logo_left.png`, `logo_right.png`, `logo_center.png`) adapt dynamically across mobile ($320\text{px}$–$375\text{px}$), tablet ($768\text{px}$), and desktop ($1024\text{px}$) viewports using flexbox distribution.
- **🎨 Dynamic Style Switcher:** Supports multiple accessibility themes, including a standard layout, a modern Grey Theme, and a high-contrast Black Theme for visually impaired users.
- **♿ Accessibility Control Panel:** Dedicated A+/A/A- text size changer, screen reader links, skip-to-content anchors, and fully standard HTML5 markup compliant with WCAG accessibility guidelines.
- **🗺️ Intuitive Mega-Menu Navigation:** Smooth, multi-level hover-triggered nested drop-down navigation, styled dynamically to display sub-options horizontally on large viewports.
- **🛠️ Modern Citizen Services Portal (`services.html`):** Redesigned Services page featuring 50/50 height-balanced cards for *Home Guards* and *Civil Defence*, circular icon badges, and a 24x7 *Quick Access & Emergency Support* callout block.
- **📦 Single-Card Architecture:** Optimized CSS rules (`custom.css`) to eliminate multi-layer nested card borders across *Links*, *Downloadable Forms*, and *Notice Board* blocks.
- **🌐 Centered & Responsive Footer:** Mobile media queries ($<768\text{px}$) center Contact Us and Quick Links sections and format bottom legal menus into an evenly spaced, wrapped row (`justify-content: space-evenly`).

---

## 🚀 Recent Modernization Updates (GIGW & Responsiveness Overhaul)

We have performed extensive patches and layout compliance improvements across the portal:
- **📱 Fully Responsive Navbar**: Redesigned breakpoints and transition queries (`custom.css`) to ensure the navigation header collapses properly without wrapping or breaking across mobile (`320px` to `370px`), tablet (`768px+`), and laptop (`1024px` to `1190px`) screen widths.
- **🛠️ Services Page Modernization (`services.html`)**: Converted plain text lists into 50/50 height-balanced 2-column cards, removed color underline strips from section headings, and added a dedicated Emergency Support block.
- **📦 Card Nesting & Layout Fixes**: Stripped duplicate background borders from inner region blocks (`.region-notice-alert`, `.news-box2`, `.ntrtnw`) to ensure every sidebar and homepage card renders as a single, clean card frame with a theme-matching "More +" pill button (`margin-top: auto`).
- **🗺️ Integrated Sitemap (`sitemap.html`)**: Added a nested structured sitemap list detailing all accessibility pages, wings, and medals. The sitemap matches the site design and includes standard floats and sidebar positioning.
- **🎨 Unified Photo Card Transitions**: Configured `old_photos.html` and `new_photos.html` category items so the entire `.field-item` card (border, shadow, translation) animates together on hover rather than just the image alone.
- **♿ WCAG Accessibility & Contrast Compliance**:
  - Replaced browser-default blue outline rings on focus with a custom **Accessible Keyboard Focus Outline** (`2px solid #55331C` for standard style, bright yellow `#ffff00` for high-contrast dark mode). Focus indicators only show during keyboard navigation (`:focus-visible`), keeping mouse clicks clean.
  - Stripped invalid trailing comment artifacts (`//--><!]]>`) on all text resizer scripts.
  - Set explicit `tabindex` and semantic HTML structures across tables and headers.

---

## 📂 Site Map & Repository Structure

Below is a directory walkthrough representing the local portal architecture:

| 📄 Page Filename | 📝 Description |
| :--- | :--- |
| [`index.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/index.html) | **Main Portal Landing Page** – Features the hero banner, news slides, style toggles, search functions, and quick links. |
| [`about_us.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/about_us.html) | **Directorate Profile** – Outlines the organizational chart, leadership, and operational overview. |
| [`objectives.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/objectives.html) | **Core Missions** – Highlights the goals, core philosophies, and responsibilities of the personnel. |
| [`civil_defence.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/civil_defence.html) | **Civil Defence Overview** – Detailed brief on emergency response systems in Meghalaya. |
| [`civil_defence_acts.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/civil_defence_acts.html) | **Acts & Legislations** – Reference point for official legal texts, acts, and constitutional mandates. |
| [`home_guard.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/home_guard.html) | **Home Guards Overview** – Briefing on local security assistance, guard rules, and state commands. |
| [`district_offices.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/district_offices.html) | **Civil Defence Offices** – Complete directory of addresses, contacts, and emails for all district CD divisions. |
| [`district_offices_hg.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/district_offices_hg.html) | **Home Guards Offices** – Directory listings for local HG district commands. |
| [`basic_statistics.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/basic_statistics.html) | **Data & Statistics** – Visual tables documenting personnel counts, training metrics, and rescue stats. |
| [`notice_board.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/notice_board.html) | **Notice Board & Circulars** – Downloadable PDFs, recruitment circulars, and tender listings. |
| [`news.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/news.html) | **Press & Media** – Highlights of activities, safety drills, community events, and state awards. |
| [`services.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/services.html) | **Citizen Charters & Services** – Details on public training registrations, enrollment forms, and emergency dispatch services. |
| [`sitemap.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/sitemap.html) | **Sitemap Page** – A hierarchically structured navigation index for all wings, documents, and medals. |
| [`accessibility.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/accessibility.html) | **Accessibility Statement** – General state compliance document defining accessible usage criteria. |
| [`accessibility_options.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/accessibility_options.html) | **Accessibility Options** – Setup options page outlining resizers, styling helpers, and screen reading settings. |
| [`disclaimer.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/disclaimer.html) | **Disclaimer Notice** – Legal disclosures regarding state-hosted data, resources, and links. |
| [`whos_who.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/whos_who.html) | **Who's Who Directory** – Executive department directory mapping leadership officials and contacts. |
| [`photo_gallery.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/photo_gallery.html) | **Photo Gallery Categories** – Main entry page directing users to modern/old image collection sub-directories. |
| [`old_photos.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/old_photos.html) | **Historical Photos** – Photo library archiving historic state commands, guards, and services. |
| [`new_photos.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/new_photos.html) | **Modern Activity Photos** – Highlighting current active trainings, rescue drills, and state events. |
| [`programmes_schemes.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/programmes_schemes.html) | **State Schemes** – Outlines state-sponsored civic initiatives, training schemes, and relief projects. |
| [`recruitment.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/recruitment.html) | **Recruitment Center** – Direct access listings for volunteer enrollment notices and candidate lists. |
| [`rti.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/rti.html) | **RTI Act Details** – General guidelines, contacts, and downloadable forms for RTI submissions. |
| [`tenders.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/tenders.html) | **Tender Center** – Quick access link/page for active department tenders and quotes. |
| [`internal_complaints.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/internal_complaints.html) | **Internal Complaints Committee** – Setup data and contact directory for sexual harassment redressal cells. |
| [`awards_excellence.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/awards_excellence.html) | **Excellence Awards** – Honors and details regarding recipients of Meghalaya Day Excellence Awards. |
| [`awards_dg_mha.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/awards_dg_mha.html) | **DG MHA Awards** – Commendation Disc recipients designated by the Ministry of Home Affairs. |
| [`awards_dg_meghalaya.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/awards_dg_meghalaya.html) | **DG Meghalaya Awards** – Commendation Disc recipients designated by the state Directorate. |
| [`medal_distinguished.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/medal_distinguished.html) | **Distinguished Service Medal** – Directory of President's Medal for Distinguished Service recipients. |
| [`medal_gallantry.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/medal_gallantry.html) | **Gallantry Medals** – Recipient directory for Home Guards & Civil Defence Medal for Gallantry. |
| [`medal_meritorious.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/medal_meritorious.html) | **Meritorious Service Medal** – Recipient directory for Meritorious Service Medals. |
| [`medal_governor.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/medal_governor.html) | **Governor's Medal** – Recipient directory for Meghalaya Governor's CD & HG Medal. |
| [`medal_cm_disaster.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/medal_cm_disaster.html) | **CM's Disaster Medal** – Recipient directory for Chief Minister's Disaster Response Medal. |
| [`medal_meritorious_service.html`](file:///c:/Users/KIIT0001/OneDrive/Desktop/NIC/Home%20Guards/medal_meritorious_service.html) | **Fire Service Meritorious Medal** – Recipient directory for Fire Service Medal for Meritorious Service. |


---

## 💻 Local Development & Setup

This website is a static client-side portal and does not require complex compilation servers, database engines, or external language runtimes. 

### Quick Start (VS Code Live Server)
1. Open this workspace in **Visual Studio Code**.
2. Install the **Live Server** extension.
3. Click the `Go Live` button in the status bar or right-click `index.html` and choose **Open with Live Server**.

### Python Local Server
Alternatively, you can run a local server using Python. Run the following command from the root directory:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your web browser.

### Node.js HTTP Server
Or via npm:
```bash
npx http-server -p 8000 .
```

---

## 🔗 Associated Portals & Resources

| Portal / Authority Logo | Description / Link |
| :---: | :--- |
| [![National Portal of India](https://meghomeguards.gov.in/sites/default/files/styles/footer_logo/public/footer-004.jpg?itok=gLb2GYeT)](https://india.gov.in/) | **[National Portal of India](https://india.gov.in/)** – The official gateway to single-window information and services provided by the Indian government. |
| [![Vidya Lakshmi Portal](https://meghomeguards.gov.in/sites/default/files/styles/footer_logo/public/footer-006.jpg?itok=1VI0HVCJ)](https://www.vidyalakshmi.co.in/Students/) | **[Vidya Lakshmi Portal](https://www.vidyalakshmi.co.in/Students/)** – A centralized portal for students seeking education loans and scholarships. |
| [![Government of Meghalaya](https://meghomeguards.gov.in/sites/default/files/styles/footer_logo/public/footer-005.jpg?itok=AcixQw1i)](http://meghalaya.gov.in/megportal/) | **[Government of Meghalaya](http://meghalaya.gov.in/megportal/)** – State-level administrative hub and primary portal for departments, schemes, and official resources. |
| [![Education for all in India](https://meghomeguards.gov.in/sites/default/files/styles/footer_logo/public/footer-003.jpg?itok=VubnXAa1)](http://www.educationforallinindia.com/) | **[Education for all in India](http://www.educationforallinindia.com/)** – Information channel for the Sarva Shiksha Abhiyan (SSA) educational initiative. |
| [![NCERT](https://meghomeguards.gov.in/sites/default/files/styles/footer_logo/public/footer-002.jpg?itok=fqnUKBXW)](http://ncert.nic.in/) | **[NCERT](http://ncert.nic.in/)** – National Council of Educational Research and Training, defining curriculum frameworks and academic publications. |
| [![MHRD](https://meghomeguards.gov.in/sites/default/files/styles/footer_logo/public/footer-001.jpg?itok=yqfZPqPP)](http://mhrd.gov.in/) | **[MHRD (Ministry of Education)](http://mhrd.gov.in/)** – National ministry overseeing human resource development and national education standards. |

---

## 🛡️ Disclaimer

**NOTE !!**

> This repository is a frontend template representing the portal design for the Directorate of Civil Defence & Home Guards, Government of Meghalaya. Third-party style sheets, JavaScript libraries, icons, and official logos are retrieved dynamically from official government servers or validated CDNs to ensure compliance with the original content layout.
