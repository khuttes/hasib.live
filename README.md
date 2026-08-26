# 🛡️ Hasib.live — Cybersecurity Portfolio & Security Engineering Website

> A professional, interactive cybersecurity portfolio website for **Md. Hasib Islam**, focused on web and API security, network attack-surface assessment, security automation, defensive AI research, and client-facing security consulting.

[![Live Website](https://img.shields.io/badge/Website-hasib.live-00e5a8?style=for-the-badge)](https://hasib.live)
[![Security](https://img.shields.io/badge/Focus-Cybersecurity-00d9ff?style=for-the-badge)](#-services)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#-technology-stack)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827)](#-technology-stack)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](#-technology-stack)

---

## 📌 About the Project

**Hasib.live** is a single-page cybersecurity portfolio and client-conversion website designed to present security expertise, services, projects, workflow, security techniques, an audit estimator, frequently asked questions, and direct communication options in one professional interface.

The website combines a **cybersecurity-themed visual design** with interactive components so visitors can explore services and projects, estimate an audit, watch security-related video content, and start a WhatsApp conversation.

The project was also reviewed and repaired to improve interaction reliability, browser compatibility, accessibility, and graceful failure handling.

---

## ✨ Key Features

### 🧑‍💻 Professional Portfolio

- Cybersecurity professional introduction
- Security engineering positioning
- Web and API penetration-testing focus
- Network security and attack-surface assessment
- Security automation
- Defensive AI integration
- Technical skills and capabilities
- Project portfolio

### 🔐 Security Services

The website presents client-facing security services including:

- Web Application Security Audits
- API Security Assessment
- Network Attack Surface Assessment
- Security Engineering
- Security Tooling & Automation
- AI Threat Modeling & Consulting
- Security hardening and defensive recommendations

### 🧮 Security Audit Estimator

Visitors can interact with the audit estimator to provide information about:

- Security assessment type
- Target/project size
- Assessment scope/depth
- Estimated assessment timeline
- Direct WhatsApp inquiry generation

The estimator is intended as a **preliminary planning tool**, not a contractual quotation.

### 📊 Interactive Project Portfolio

The projects section includes:

- Project cards
- Category filtering
- AI/security project classification
- Technical specification modal
- Project descriptions
- Technology/tag presentation

### 🖥️ Interactive Cyber Terminal

The website includes a visual cybersecurity terminal interface with interactive commands for navigating or displaying portfolio information.

### 🎬 YouTube Integration

The website contains a YouTube video/player experience with:

- Embedded YouTube player
- Privacy-enhanced `youtube-nocookie.com` embedding
- Player controls
- Autoplay/mute configuration
- Error detection
- Graceful fallback when embedding is unavailable

If YouTube embedding is blocked by a browser, network, privacy extension, or video restriction, the website provides an alternative link to watch the video directly on YouTube.

### 📱 Responsive Navigation

The website supports:

- Desktop navigation
- Mobile navigation menu
- Mobile menu auto-close after navigation
- Responsive layouts
- Mobile-friendly CTA actions
- Accessibility state for the navigation menu

### 💬 Direct Contact

Visitors can contact through:

- Email
- WhatsApp
- Direct security-audit CTA
- Inquiry form
- WhatsApp-generated inquiry message

### ❓ FAQ Section

The FAQ section provides answers related to:

- Security assessments
- Testing scope
- Reporting
- Retainer/ongoing security support
- Audit estimation
- Client engagement

### 🎨 Cybersecurity Visual Design

The interface uses:

- Dark cybersecurity aesthetic
- Glassmorphism panels
- Neon-inspired accent styling
- Animated background elements
- Cyber terminal visuals
- Responsive cards
- Interactive hover effects
- Scroll/reveal animations
- Security-focused typography

---

# 🧩 Website Sections

The website is organized into the following major sections:

| Section | Purpose |
|---|---|
| **Hero / About** | Introduces the cybersecurity professional and core capabilities |
| **Capabilities** | Presents technical skills and security expertise |
| **Services** | Explains client-facing security services |
| **Workflow** | Shows the security assessment process |
| **Security Overview** | Presents security techniques and assessment methodology |
| **Audit Estimator** | Provides an interactive preliminary assessment estimator |
| **Projects** | Displays security/AI projects with filtering and technical details |
| **YouTube** | Provides security-related video content |
| **FAQ** | Answers common client questions |
| **Contact** | Provides direct email and WhatsApp communication |

---

# 🛠️ Technology Stack

The website is primarily implemented as a **single HTML file** containing the page structure, styling references, and JavaScript functionality.

### Core

- HTML5
- JavaScript
- Tailwind CSS
- CSS animations
- SVG icons

### External Resources

The website uses external resources/services including:

- Tailwind CSS CDN
- Google Fonts
- YouTube IFrame API
- YouTube privacy-enhanced embeds
- WhatsApp click-to-chat
- External portfolio/social links where configured

> Because some resources are external, complete functionality can depend on the visitor's network connection, browser privacy settings, ad blockers, and third-party service availability.

---

# 📁 Project Structure

A simple deployment structure is recommended:

```text
hasib-live/
│
├── index.html
├── README.md
└── assets/
    ├── images/
    ├── icons/
    └── documents/
```

If the project remains completely self-contained, the primary website can also be deployed with only:

```text
index.html
README.md
```

---

# 🚀 Running Locally

## Option 1 — Open Directly

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/hasib-live.git
cd hasib-live
```

Then open:

```text
index.html
```

in a modern web browser.

---

## Option 2 — Run a Local Web Server

Using Python:

```bash
python3 -m http.server 8000
```

Open:

```text
http://127.0.0.1:8000
```

Using PHP:

```bash
php -S 127.0.0.1:8000
```

Then visit:

```text
http://127.0.0.1:8000
```

Using Node.js:

```bash
npx serve .
```

---

# 🌐 GitHub Pages Deployment

This project is suitable for GitHub Pages because the website is a client-side HTML/CSS/JavaScript application.

### 1. Create a repository

Create a GitHub repository, for example:

```text
hasib-live
```

### 2. Add the website

Copy the website into the repository:

```text
index.html
README.md
```

### 3. Commit the files

```bash
git add .
git commit -m "Initial release of Hasib.live cybersecurity portfolio"
git push origin main
```

### 4. Enable GitHub Pages

From the repository:

```text
Settings
→ Pages
→ Deploy from a branch
→ main
→ / (root)
→ Save
```

GitHub will then provide a public website URL.

---

# 🔧 Important Configuration

Before publishing, review these values in `index.html`:

### Personal Information

Check:

- Name
- Email address
- Phone number
- WhatsApp number
- Website URL
- YouTube URL
- Social/portfolio links

### YouTube Video

The website currently contains a YouTube video integration. Verify that:

- The video ID is correct.
- The video is publicly available.
- Embedding is permitted.
- The video link points to the intended content.

### WhatsApp

Verify the WhatsApp destination number before publishing.

The WhatsApp URL format is:

```text
https://wa.me/COUNTRYCODEPHONENUMBER
```

Do not include spaces or the `+` symbol in the `wa.me` number.

---

# 🧪 Quality & Reliability Review

The project was reviewed for common single-page website problems.

### Checks performed

- Internal navigation targets
- JavaScript initialization
- Interactive buttons
- Mobile menu
- Project filtering
- Project modal
- Audit estimator
- WhatsApp interaction
- YouTube integration
- Canvas animation
- Scroll progress
- Reveal animations
- Browser API fallbacks
- Accessibility states
- JavaScript-disabled behavior

### Important repairs

#### YouTube initialization

The YouTube IFrame API initialization order was corrected so the callback function is available when the API initializes.

#### Broken internal navigation

The Security navigation target was corrected so it points to the existing security section.

#### Canvas safety

Mouse/particle calculations were hardened against invalid zero-distance calculations.

#### DOM safety

Optional elements are checked before JavaScript attempts to manipulate them.

#### Browser API fallback

The website now has graceful behavior when `IntersectionObserver` or optional animation functionality is unavailable.

#### Mobile navigation accessibility

The menu now maintains an `aria-expanded` state and closes after a navigation link is selected.

#### JavaScript fallback

A `<noscript>` message is included for users who disable JavaScript.

---

# 🔒 Security Considerations

This website is a **portfolio/presentation website**, not a backend security-testing platform.

It does not by itself perform unauthorized penetration testing against visitor systems.

The website's security-related content is intended to present professional cybersecurity services and capabilities.

### Recommended production practices

Before using the website commercially:

- Serve it exclusively over HTTPS.
- Keep external dependencies updated.
- Avoid exposing private API keys in client-side JavaScript.
- Never place passwords or secrets in `index.html`.
- Validate any future backend/API inputs server-side.
- Configure appropriate HTTP security headers on the hosting platform.
- Consider a Content Security Policy compatible with the required external resources.
- Add a privacy policy if collecting visitor information.
- Use a proper backend/service if client inquiries need server-side storage.

---

# ♿ Accessibility

The project includes several accessibility-oriented features:

- Semantic HTML elements
- Navigation labels
- Button labels
- `aria-label` for mobile navigation
- `aria-expanded` state
- `aria-controls`
- Dialog semantics for project modal
- Keyboard-friendly native FAQ `<details>` elements
- Reduced-motion awareness
- Visible focus/interaction states where applicable
- `noscript` fallback

Accessibility should still be tested with real keyboard, screen-reader, and browser accessibility tools before production release.

---

# 📱 Responsive Design

The website is designed for:

- Desktop
- Laptop
- Tablet
- Mobile

Responsive behavior includes:

- Mobile navigation
- Responsive grids
- Flexible typography
- Responsive project cards
- Mobile-friendly CTA buttons
- Adaptive hero layout
- Responsive estimator and contact sections

---

# 🎯 Target Audience

The website is designed for potential:

- Startup founders
- Business owners
- Web application teams
- API developers
- SaaS companies
- Organizations requiring security assessments
- Development teams
- Technology companies
- Clients seeking penetration testing
- Organizations seeking security consulting

---

# 💼 Client Conversion Flow

The website is structured around a simple visitor journey:

```text
Visitor
   ↓
Hero / Professional Introduction
   ↓
Capabilities
   ↓
Security Services
   ↓
Security Workflow
   ↓
Security Techniques
   ↓
Audit Estimator
   ↓
Projects / Technical Evidence
   ↓
FAQ
   ↓
Contact
   ↓
WhatsApp / Email Inquiry
```

This structure is intended to move a visitor from **awareness → trust → technical understanding → service selection → contact**.

---

# 📈 Future Improvements

Potential future versions could add:

- Backend contact form
- Email notification system
- Database-backed inquiry management
- CMS integration
- Blog/security research section
- Case-study pages
- Client testimonials
- Downloadable security reports
- Automated appointment booking
- Real-time security assessment quotation system
- Analytics
- SEO metadata optimization
- Open Graph/social preview cards
- Structured data/schema markup
- PWA support
- Offline asset caching
- Self-hosted fonts and CSS for reduced third-party dependency
- Automated CI/CD deployment
- Automated HTML/CSS/JavaScript testing

---

# 🧑‍💻 Development

Recommended workflow:

```bash
git clone https://github.com/YOUR-USERNAME/hasib-live.git
cd hasib-live
```

Make changes to:

```text
index.html
```

Test locally:

```bash
python3 -m http.server 8000
```

Then commit:

```bash
git add .
git commit -m "Update website"
git push
```

---

# 📄 Project Audit

A separate project audit was performed on the supplied website.

The audit covered:

- Functional behavior
- Navigation
- JavaScript
- Interactive components
- YouTube integration
- Estimator
- Project system
- WhatsApp flow
- Responsive behavior
- Accessibility
- Graceful fallbacks

The repaired project should be used as the deployment version rather than the original uncorrected file.

---

# 📜 License

If this repository is intended to represent a personal professional portfolio, you may choose a license appropriate for your intended use.

For a personal portfolio, a simple proprietary notice can be used:

```text
© Md. Hasib Islam. All rights reserved.
```

If you want others to freely modify and redistribute the source, consider adding an open-source license such as MIT.

---

# 👤 Author

**Md. Hasib Islam**

Cybersecurity Professional focused on:

- Web Security
- API Security
- Network Security
- Penetration Testing
- Bug Bounty Research
- Security Automation
- Defensive AI
- Security Engineering

---

# 🔗 Links

- 🌐 Website: https://hasib.live
- 📺 YouTube: https://youtu.be/dfdhAwSDOgw
- 💬 WhatsApp: configured in the website's contact/estimator functionality
- 📧 Email: configured in the website's contact section

---

# ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

For security-related questions, consulting, vulnerability assessment, or collaboration, use the contact options provided on the website.

---

## ⚠️ Disclaimer

This portfolio presents cybersecurity services and security expertise for authorized and defensive purposes.

Any penetration testing, vulnerability assessment, security research, scanning, or security testing should only be performed against systems for which the tester has explicit authorization.

---

**Built with HTML, JavaScript, Tailwind CSS, cybersecurity engineering, and a focus on professional client experience.**
