# EdgeCast - Crypto Prediction Platform

Welcome to the **EdgeCast Frontend** repository!

EDGECAST is a gamified crypto prediction platform where users stake any amount to guess future prices.


### App link

https://edge-cast-app.vercel.app/

### Demo video link 

https://drive.google.com/file/d/1oMuvdHvAmuuV_aG60I96CmICK89uFdvP/view?usp=sharing

---

### Pitchdeck link 
https://www.canva.com/design/DAG0KAST2RY/t3lKaRvO8smoy7JQDPNRYg/view?utm_content=DAG0KAST2RY&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h036385765e

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Environment Variables](#environment-variables)
- [Deployment](#deployment)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [FAQ](#faq)

---

## Overview

EdgeCast Frontend serves as the main interface for users of the EdgeCast platform. It connects to backend APIs, renders data dynamically, and enables users to interact with platform features efficiently.

EdgeCast aims to deliver a seamless, high-performance, and scalable solution for content delivery and real-time data visualization.

---

## Features

- **Responsive Design**: Works seamlessly on desktops, tablets, and mobiles.
- **Modern UI**: Built using component-based architecture for maintainability and scalability.
- Smart Contract Integration: Built on BlockDag network
- **API Integration**: Connects to backend services for live data.
- **Customizable**: Easily extendable for new features and integrations.
- **Optimized Performance**: Leveraging best practices in frontend development.
- **Routing**: Fast navigation using client-side routing ( ).
 
- **Error Handling**: User-friendly error pages and notifications.
- **Authentication**: (If present) Supports user login and protected routes.
- **Theming**: Easily switch between light/dark modes (if implemented).
- **Accessibility**: Follows accessibility guidelines for a better user experience.

---

## Tech Stack

- **Language:** JavaScript, Solidity
- **Framework:** ReactJs, Express JS, Tailwind CSS
- **Build Tools:** Webpack, Babel, npm/yarn, Vite (frontend)
- **Deployment:** Vercel
- **Other Tools:** 
  - ESLint & Prettier for code quality and formatting
  - GitHub Actions (for CI/CD, if configured)

---

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm or yarn

### Installation

```bash
git clone https://github.com/zayn-tech-info/edge-cast-frontend.git
cd edge-cast-frontend
npm install
```

### Running Locally

```bash
npm run dev
```

The app will be available at `http://localhost:3000`.

### Building for Production

```bash
npm run build
npm start
```

---

## Project Structure

The following is a typical structure for a frontend project. Actual structure may vary:

```
edge-cast-frontend/
├── public/         # Static assets
├── src/            # Source code (components, pages, utils)
│   ├── components/ # Reusable UI components
│   ├── pages/      # Route pages (for Next.js)
│   └── ...         
├── package.json    # Project metadata and scripts
├── next.config.js  # Next.js configuration (if applicable)
└── README.md       # Project documentation
```

### Key Folders

- **/public**: Static files (images, favicon, etc.) accessible from the root URL.
- **/src/components**: Reusable React components.
- **/src/pages**: Page components for routing (Next.js).
- **/src/utils**: Utility functions and helpers.
- **/src/styles**: CSS or SASS/LESS files.

---

## Environment Variables

To connect to APIs or configure deployment, you may need to set environment variables.

Create a `.env.local` file in the root directory and add variables like:

```
NEXT_PUBLIC_API_URL=https://api.edgecast.com
NEXT_PUBLIC_ANALYTICS_ID=your-analytics-id
```

(Refer to project code or documentation for required variables.)

---

## Deployment

EdgeCast Frontend is deployed on [Vercel](https://vercel.com). For production deployment:

1. Push your changes to the `main` branch.
2. Vercel will build and deploy automatically if connected to your GitHub repository.
3. For custom domains or environment variables, configure them in your Vercel dashboard.

---

## Testing

Automated testing is encouraged for reliability.

- **Unit Tests**: Place tests in `src/__tests__` or alongside components.
- **Testing Library**: Likely using Jest and React Testing Library.
- **Run tests:**

```bash
npm test
```

---

## Contributing

Contributions are welcome! Please open issues and submit pull requests for bug fixes or new features.

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request.

### Coding Guidelines

- Use clear, descriptive commit messages.
- Follow existing code style (see `.eslintrc` or `.prettierrc`).
- Write unit tests for new features.

---

## License

This project currently does not specify a license. Please contact the repository owner for usage permissions.

---

## Contact

- **Owner:** [zayn-tech-info](https://github.com/zayn-tech-info)
- **Project URL:** [https://github.com/zayn-tech-info/edge-cast-frontend](https://github.com/zayn-tech-info/edge-cast-frontend)
- **Live Demo:** [edge-cast-frontend.vercel.app](https://edge-cast-frontend.vercel.app)

For questions or feedback, feel free to open an issue in the repository.

---

## FAQ

**Q: Is this project open source?**  
A: Currently, no license is specified. Contact the owner for details.

**Q: What backend does EdgeCast use?**  
A: This repository is frontend-only. Backend details are managed in separate repositories.

**Q: How do I report a bug or request a feature?**  
A: Please open an issue using GitHub's issue tracker.

**Q: Can I use this code for my own project?**  
A: Please check with the owner regarding permissions.

---
