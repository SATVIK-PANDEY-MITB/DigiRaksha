# DigiRaksha 🛡️

> A digital safety ecosystem for tourists, destinations, and authorities.

DigiRaksha is a responsive React and TypeScript landing website presenting a proposed tourist safety platform. The project transforms the concept into a clear product story through an interactive one-page experience, implementation roadmap, feasibility analysis, impact model, and monetization strategy.

## 📊 Project Snapshot

| Metric | Value |
| --- | ---: |
| Primary framework | React 19 |
| Language | TypeScript 5.8 |
| Build tool | Vite 6 |
| Package manager | npm |
| Application type | Single-page responsive website |
| Main components | 16 reusable and section files |
| Content sections | 11 |
| Core solution modules | 6 |
| Roadmap phases | 4 |
| Supported navigation views | Desktop and mobile |

## 🎯 Product Vision

DigiRaksha combines:

- **Digital Trip IDs** secured through blockchain-backed identity records.
- **A tourist mobile application** with one-tap emergency assistance.
- **AI anomaly detection** for early risk identification.
- **IoT wearables and connectivity** for continuous monitoring.
- **An authorities dashboard** for coordinated incident response.
- **A complete ecosystem** connecting tourists, local businesses, and government stakeholders.

The current repository implements the **product presentation and business-case interface**. AI processing, blockchain records, IoT data, live APIs, authentication, databases, and backend services are part of the proposed future architecture rather than an implemented backend.

## ✨ Included Features

- Fixed and scroll-aware responsive header with active-section highlighting.
- Hero section with clear product positioning and calls to action.
- Six-solution capability cards covering Digital Trip ID, tourist app, AI detection, IoT wearables, authorities dashboard, and ecosystem integration.
- Four-step "How It Works" journey from registration to incident response.
- Three stakeholder impact views for tourists, authorities, and destinations.
- Feasibility analysis highlighting smartphone adoption, QR infrastructure, and government alignment.
- Four-phase implementation roadmap from foundation to ecosystem growth.
- Business model and team presentation sections.
- Contact section with project communication details.
- Animated section transitions and scroll-to-top navigation.
- Mobile navigation with responsive layout and accessible menu controls.

## 🛠️ Technology Stack

| Layer | Technology | Version / Detail |
| --- | --- | --- |
| Frontend | React | 19.1.1 |
| Language | TypeScript | 5.8.x |
| Build system | Vite | 6.2.x |
| DOM rendering | React DOM | 19.1.1 |
| Type definitions | Node.js types | 22.14.0 |
| React tooling | Vite React plugin | 5.0.0 |
| Styling | CSS and responsive utility classes | Custom component styling |
| Icons | Custom SVG components | Inline React SVG elements |
| Animation | CSS transitions and Intersection Observer | Scroll-triggered effects |

## 🏗️ Architecture

```text
Browser
  └── React 19 single-page application
       ├── Shared header, footer, and navigation
       ├── 11 presentation sections
       ├── Reusable cards and animation wrappers
       └── SVG icon component library
```

The application has no server-side runtime, API layer, database, authentication system, or persistent data store. Deployment is currently focused on a static frontend build.

## 📁 Project Structure

```text
DigiRaksha-main/
├── App.tsx                  # Application composition and section order
├── index.tsx                # React application entry point
├── index.html               # HTML shell and application mount point
├── metadata.json            # Project presentation metadata
├── package.json             # Dependencies and npm scripts
├── tsconfig.json            # TypeScript compiler configuration
├── vite.config.ts           # Vite and React configuration
├── components/
│   ├── AnimatedWrapper.tsx  # Scroll animation wrapper
│   ├── FeatureCard.tsx      # Reusable feature card
│   ├── Footer.tsx           # Footer navigation and content
│   ├── Header.tsx           # Responsive navigation and active sections
│   ├── Hero.tsx             # Primary product introduction
│   ├── icons.tsx            # Shared SVG icon definitions
│   ├── ScrollToTop.tsx      # Scroll-to-top control
│   ├── SectionWrapper.tsx   # Shared section layout
│   └── sections/            # Problem, solution, tech, impact, and roadmap content
└── package-lock.json        # Locked npm dependency versions
```

## 🚀 Getting Started

### Prerequisites

- Node.js 20 or newer
- npm 10 or newer

### Installation

```bash
git clone https://github.com/anchit-goel/digiraksha.git
cd digiraksha
npm install
```

### Development

```bash
npm run dev
```

The development server is typically available at:

```text
http://localhost:5173
```

### Production Build

```bash
npm run build
```

The optimized production files are generated in the `dist/` directory.

### Preview Production Build

```bash
npm run preview
```

## 📈 Roadmap

| Phase | Period | Deliverable |
| --- | --- | --- |
| 1 | Q1–Q2 2025 | Tourist app, authorities dashboard, and blockchain-based Digital Trip ID foundation |
| 2 | Q3 2025 | AI anomaly detection and risk-scoring integration |
| 3 | Q4 2025 | IoT wearable support, mesh network, and expansion to five additional cities |
| 4 | 2026 | Gamification, vendor partnerships, and broader government collaboration |

## 🔐 Current Scope Limitations

The frontend currently contains a marketing and proposal experience. It does not yet provide:

- User authentication or account management.
- Real blockchain transactions or identity verification.
- AI model inference or anomaly detection.
- Real-time IoT device data.
- Emergency SOS backend processing.
- Database persistence or API authorization.
- Live maps, notifications, or location services.
- Production deployment configuration.

## 🧪 Verification

Run the following commands from the project root:

```bash
npm install
npm run build
npm run preview
```

The build command verifies that TypeScript and Vite can compile the complete application. The repository currently has no automated test suite.

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch.
3. Implement a focused, well-tested change.
4. Run the production build.
5. Open a pull request with a clear description of the change.

Before contributing to backend or platform functionality, first define the API contract, data model, authentication approach, and deployment architecture.

## 📜 License

No license file is currently included in this repository. Before publishing or distributing the project, add an appropriate open-source license and update this section with its terms.

## 👥 Project Status

**Status:** Frontend prototype and product presentation website.

**Primary use case:** SIH Hackathon project presentation and stakeholder demonstration.

**Recommended next step:** Convert the roadmap into separate backend, AI, blockchain, IoT, and deployment milestones with explicit technical requirements and acceptance criteria.
