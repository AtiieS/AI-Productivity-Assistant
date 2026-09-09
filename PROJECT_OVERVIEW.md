# Project Overview — AI Workplace Productivity Assistant (Nexa)

## Purpose

Nexa is an AI-powered workplace productivity assistant that automates repetitive business tasks. It demonstrates real-world business value through effective AI integration, strong prompt engineering, ethical AI practices, and measurable productivity improvements.

## Target Users

- Office administrators
- Project managers
- HR professionals
- Healthcare administrators
- Students
- Small business owners
- Corporate employees

## Core Workflows

### 1. AI Chatbot
A conversational workplace assistant that answers questions, generates professional responses, rewrites documents, explains complex topics, brainstorms ideas, and drafts messages. Supports suggested prompts, copy-to-clipboard, loading animations, and session-based context.

### 2. Research Assistant
Accepts articles, reports, research papers, website text, or topics. Generates an executive summary, key insights, important statistics, advantages, challenges, recommendations, actionable next steps, complexity level, and estimated reading time. Users choose between Beginner, Professional, or Executive summary depth.

### 3. Task Planner
Accepts tasks, deadlines, meeting times, priorities, and estimated durations. The AI prioritizes tasks as Urgent, Important, or Low Priority and generates a daily schedule, weekly planner, time blocks, break suggestions, productivity tips, and estimated completion times. Overdue tasks are highlighted and schedule optimization is suggested.

### 4. Meeting Summarizer
Accepts lengthy meeting notes or transcripts. Extracts an executive summary, key discussion points, decisions made, action items, assigned responsibilities, deadlines, risks, and follow-up tasks. Results can be exported or copied to clipboard.

## Pages

| Page | Description |
|---|---|
| Dashboard | Welcome message, productivity score, tasks completed, time saved, recent activities, quick actions, and feature cards. |
| AI Chatbot | Interactive chat interface with suggested prompts and copy support. |
| Research Assistant | Paste-and-analyze workflow with summary level selection. |
| Task Planner | Task list with priorities, AI-optimized schedule, and productivity tips. |
| Meeting Summarizer | Paste notes and generate a structured meeting brief. |
| Prompt Library | Reusable, tested system prompts for every workflow. |
| Productivity Analytics | Charts and metrics for tasks, research, meetings, AI conversations, and time saved. |
| Settings | Profile, theme toggle, AI preferences, and ethical AI commitment. |
| About | Value proposition, responsible AI principles, and impact metrics. |

## Design System

- **Colors:** White base with pink, rose, and fuchsia accents across a 10-shade brand ramp.
- **Typography:** Inter (body), Plus Jakarta Sans (headings), JetBrains Mono (prompts).
- **Components:** Glassmorphism cards with backdrop blur, soft shadows, and pink-tinted borders.
- **Animations:** Fade-in, slide-up, slide-in, pulse, shimmer, and bounce keyframes.
- **Layout:** Collapsible sidebar navigation, sticky top bar, responsive grid from mobile to desktop.
- **Theme:** Light and dark mode with full contrast compliance.

## Technology

| Layer | Technology |
|---|---|
| Frontend | React 18 + TypeScript |
| Build tool | Vite 5 |
| Styling | Tailwind CSS 3 (custom theme) |
| Icons | Lucide React |
| Backend | Supabase (provisioned) |
| Deployment | Vercel / Netlify (static `dist/` output) |

## Prompt Engineering Approach

Each workflow uses a dedicated system prompt that defines the AI's role, tone, output structure, and guardrails:

- **Chatbot** — Professional, ethical, concise; asks clarifying questions.
- **Research** — Senior analyst producing structured summaries with risks and action items.
- **Task Planner** — Executive coach balancing urgency and burnout prevention.
- **Meeting Summarizer** — Corporate assistant extracting decisions, ownership, and deadlines.

## Ethical AI Commitment

1. Review AI-generated content before use.
2. Never enter confidential or sensitive information.
3. Respect privacy and minimize data collection.
4. Users remain responsible for final decisions.
5. Promote fairness, transparency, and accountability.
6. Clearly label all AI-generated outputs.

## Measurable Impact

The application targets an 85–90% productivity improvement across four common workplace tasks:

- Email writing: 10 min → 1 min (90%)
- Meeting summaries: 30 min → 2 min (93%)
- Research: 60 min → 10 min (83%)
- Task planning: 20 min → 2 min (90%)

## Build & Verify

```bash
npm install
npm run dev        # development
npm run build      # production build
npm run lint       # lint
npm run typecheck  # type check
```

The project builds cleanly and passes all lint and type checks.
