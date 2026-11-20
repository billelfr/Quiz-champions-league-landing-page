# Quiz Champions League — Landing Page
**AWS Student Builder Group Algeria**

A high-contrast, dark-tech esports tournament landing page built for the **Quiz Champions League** algorithmic and cloud trivia competition.

---

## 🚀 Quick Start

### 1. Run Development Server
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser. Changes to `index.html` or styling will hot-reload instantly.

### 2. Build for Production
```bash
npm run build
```
Generates a minified, production-ready static bundle in the `dist/` directory.

### 3. Preview Production Build
```bash
npm run preview
```

---

## 🎨 Design System & Palette

Engineered according to the **Terminal Arena / Cyber-Esports** design specification:
- **Canvas Base**: `#161D26`
- **Surface Elevation / Insets**: `#0F141A` (darker), `#1B232E` (cell)
- **Primary Cyber Accent**: `#3FA9F5` (electric cyan), `#2A97E3` (hover)
- **Warning / Cutoff Alert**: `#FF4D4D` (neon coral)
- **Grid Hairlines**: `#2A3441`, `#374151`
- **Typography**: `JetBrains Mono`, `Space Mono`, `Material Symbols Outlined`

Reference documents are preserved in:
- `docs/DESIGN.md`: Full design tokens, elevation hierarchy, and component specs.
- `docs/screen.png`: Visual design capture.

---

## 📝 Section Directory & Content Customization

The entire page structure in `index.html` is segmented with clear comments so you can easily update the content:

| Section | ID | Description / Content to Edit |
| :--- | :--- | :--- |
| **01. Top Header** | `<header>` | Chapter title, logo icon, navigation links, and Register CTA button. |
| **02. Hero / Overview** | `#overview` | Competition title, telemetry tag, intro paragraph, animated cycling keywords (`THINK.`, `SOLVE.`, `WIN.`), metrics (playoff seats, phases, eligibility), and playoff threshold status box. |
| **03. How It Works** | `#how` | 4 tournament progression stages (Registration, Table Ranking, Knockout Bracket, Arena Tools). |
| **04. Try a Challenge** | `#try` | 5 challenge formats (MCQ, interactive console with mock AWS CLI, scenarios, research, and practical debugging). |
| **05. Rules** | `#rules` | 3 competition rules (Focus bounds, fault tolerance, search directives) and organizing team notice. |
| **06. League Table** | `#leaderboard` | Live standings simulation table with Top 16 qualifier badges and the critical playoff cutoff line. |
| **07. Final CTA** | `#join` | Full-width cyan registration banner and chapter verification block. |
| **08. Footer** | `<footer>` | Chapter disclaimer, navigation index, regional node coordinates, and copyright. |

---

## ⚡ Interactive Features Included
- **Sticky Navigation**: Smooth scrolling to each section with automatic header offset compensation.
- **Animated Text Cycler**: Dynamic CSS keyframe animation transitioning between tournament taglines.
- **Interactive MCQ Preview**: Clickable options (A, B, C, D) with instantaneous evaluation feedback.
- **Embedded Terminal Console**: Real-time CLI mock responding to commands like `aws s3 ls`, `hint`, `help`, and `clear`.
- **Collapsible FAQ Accordion**: Monospaced accordion with dynamic `+` / `-` symbol toggle.
- **Interactive Toast Feedback**: Notification banners when clicking registration and community action triggers.
