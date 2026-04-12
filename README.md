# Popclub-Chatbot-Voiceflow

A modern, responsive web replica of a rewards and payments platform landing page, integrated with a Voiceflow AI chatbot for interactive customer support.

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/next.js-%23000000.svg?style=for-the-badge&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=white)

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

---

## Features

**AI-Powered Chatbot**
A Voiceflow widget is injected at the layout level, providing real-time customer interaction and support across all pages without per-page configuration.

**Modern UI/UX**
Styled with Tailwind CSS, featuring a dark-themed aesthetic with vibrant accent colors and a consistent design language throughout.

**Interactive Components**
Responsive accordions, cards, and buttons built with `shadcn/ui` and Radix UI primitives for accessible, composable interactivity.

**SEO Optimized**
Built on Next.js 14 with the App Router, ensuring fast page loads and straightforward meta tag management.

**Reusable Component Architecture**
Header, Footer, Hero, and Testimonial sections are each built as self-contained, reusable components for easy maintenance and extension.

---

## Tech Stack

| Category | Technology |
| :--- | :--- |
| Framework | Next.js 14, React |
| Language | TypeScript |
| Styling | Tailwind CSS, Tailwind Merge, Class Variance Authority |
| UI Components | Radix UI, shadcn/ui |
| Icons | Lucide React |

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ritvikamin/Popclub-Chatbot-Voiceflow
   ```

2. Navigate to the project directory:

   ```bash
   cd Popclub-Chatbot-Voiceflow/final
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

The application will be available at `http://localhost:3000`.

---

## Usage

This project is a front-end interface for a rewards platform. The Voiceflow chatbot widget is injected globally via a `dangerouslySetInnerHTML` script block in `layout.tsx`, making it available on every page.

**Key routes:**

- `/` — Main landing page with Hero and How-It-Works sections
- `/faq` — Interactive FAQ page using accordion components
- `/contact` — Contact form layout

---

## Project Structure

```
Popclub-Chatbot-Voiceflow/final/
├── app/                  # Next.js App Router pages and layouts
├── components/
│   ├── ui/               # Base shadcn/ui components
│   └── ...               # Feature-level components (Header, Footer, Hero, etc.)
├── lib/                  # Utility functions (cn wrapper and helpers)
├── package.json          # Project dependencies
└── tailwind.config.js    # Tailwind theme configuration
```

---

## License

This project is currently unlicensed.

---

Repository: [github.com/ritvikamin/Popclub-Chatbot-Voiceflow](https://github.com/ritvikamin/Popclub-Chatbot-Voiceflow)
