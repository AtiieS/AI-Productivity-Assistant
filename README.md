# AI Workplace Productivity Assistant — Nexa

A modern, responsive web application that uses AI to automate repetitive workplace tasks. Built for office administrators, project managers, HR professionals, healthcare administrators, students, small business owners, and corporate employees.

## Features

- **Dashboard** — Productivity score, tasks completed, time saved, recent activity, and quick-action shortcuts to every tool.
- **AI Chatbot** — Interactive workplace copilot that drafts emails, summarizes documents, explains topics, and brainstorms ideas. Includes suggested prompts, copy-to-clipboard, and a typing animation.
- **Research Assistant** — Paste articles, reports, or topics and receive an executive summary, key insights, and recommendations. Choose between Beginner, Professional, or Executive summary levels.
- **Task Planner** — Add tasks with deadlines and priorities. The AI organizes them into an optimized daily schedule with time blocks, break suggestions, and productivity tips. Overdue tasks are highlighted.
- **Meeting Summarizer** — Paste meeting notes or transcripts to extract an executive summary, key discussion points, decisions, action items, assigned responsibilities, deadlines, and risks. Export or copy results.
- **Prompt Library** — A curated collection of reusable, professionally engineered system prompts for every AI workflow.
- **Productivity Analytics** — Visual dashboard with tasks completed, research requests, meetings summarized, AI conversations, estimated time saved, and weekly/monthly trends.
- **Settings** — Profile, light/dark theme toggle, AI preference controls, and an ethical AI commitment section.
- **About** — Value proposition, responsible AI principles, and productivity improvement metrics.

## Design

- **Color palette** — White and pink (brand pink, rose, and fuchsia accents).
- **UI style** — Glassmorphism cards, smooth animations, micro-interactions, and a clean professional layout.
- **Typography** — Inter for body text, Plus Jakarta Sans for headings, JetBrains Mono for code/prompt blocks.
- **Responsive** — Optimized for desktop, tablet, and mobile with a collapsible sidebar.
- **Dark / Light mode** — Full theme toggle with persistent visual contrast.
- **Accessibility** — WCAG-aware contrast ratios, labeled controls, and keyboard-friendly navigation.

## Tech Stack

- **Frontend** — React 18, TypeScript, Vite
- **Styling** — Tailwind CSS 3 with custom theme configuration
- **Icons** — Lucide React
- **Backend** — Supabase (provisioned and available for data persistence)
- **Deployment** — Vercel or Netlify ready (static build output in `dist/`)

## Getting Started

```bash
# Install dependencies
npm install

# Start the development server
npm run dev

# Build for production
npm run build

# Preview the production build
npm run preview

# Run linting
npm run lint

# Run type checking
npm run typecheck
```

## Project Structure

```
├── index.html              # HTML entry point with font imports
├── src/
│   ├── App.tsx             # Main application with all pages and components
│   ├── main.tsx            # React root
│   ├── index.css           # Tailwind layers, glassmorphism, animations
│   └── vite-env.d.ts       # Vite type declarations
├── tailwind.config.js      # Custom pink color palette, fonts, animations
├── postcss.config.js       # PostCSS + Tailwind + Autoprefixer
├── vite.config.ts          # Vite config with @/ path alias
└── package.json
```

## Prompt Engineering

The app demonstrates advanced prompt engineering with reusable system prompts:

| Workflow | Prompt Summary |
|---|---|
| AI Chatbot | Experienced workplace productivity assistant — accurate, professional, ethical, concise. Asks clarifying questions when needed. |
| Research Assistant | Senior research analyst — summarizes into executive summary, key insights, recommendations, risks, and action items. |
| Task Planner | Executive productivity coach — organizes tasks by urgency and importance, generates burnout-aware schedules. |
| Meeting Summarizer | Corporate meeting assistant — extracts summary, decisions, action items, deadlines, and responsible persons. |

## Ethical AI

- AI-generated content should always be reviewed before use.
- Do not enter confidential or sensitive company information.
- Respect user privacy — no unnecessary data collection.
- AI responses may contain errors; users remain responsible for final decisions.
- Promote fairness, transparency, and accountability.
- All AI-generated outputs are clearly labeled.

## Productivity Impact

| Task | Before | After | Improvement |
|---|---|---|---|
| Writing emails | 10 min | 1 min | 90% |
| Meeting summaries | 30 min | 2 min | 93% |
| Research | 60 min | 10 min | 83% |
| Task planning | 20 min | 2 min | 90% |

**Estimated overall productivity improvement: 85–90%**

## License

This project is portfolio-ready and intended for demonstration purposes.
