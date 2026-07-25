# Tea

**Autonomous Call Tracking & Task Automation System**

AutoTrack is an AI-powered meeting automation platform that transcribes calls, extracts action items, generates summaries, and automates follow-up tasks.

## Features

* Real-time meeting transcription
* AI-generated summaries and action items
* Sentiment and context analysis
* Automated emails, reminders, and CRM updates
* Approval-based task execution
* Audit logs and role-based access
* Support for Meet, Zoom, and Microsoft Teams

## Tech Stack

* **Frontend:** Next.js, TypeScript, Tailwind CSS
* **AI:** GPT, Claude, or open-source LLMs
* **Transcription:** Whisper or AssemblyAI
* **Integrations:** Gmail, Google Calendar, Salesforce, HubSpot, Jira, Slack

## Setup

```bash
git clone <repository-url>
cd autotrack

npm install
npm run dev
```

Open:

```text
http://localhost:3000
```

## Project Structure

```text
autotrack/
├── app/
│   ├── components/
│   ├── dashboard/
│   ├── schedule/
│   ├── layout.tsx
│   └── page.tsx
├── public/
├── package.json
└── next.config.ts
```

## Main Pages

* `/` — Landing page
* `/schedule` — Schedule meetings
* `/dashboard` — Monitor calls, transcripts, and tasks

## Workflow

```text
Meeting
   ↓
Live Transcription
   ↓
AI Analysis
   ↓
Action Item Extraction
   ↓
Task Approval
   ↓
Automatic Execution
```

## Use Cases

* Sales call follow-ups
* CRM updates
* Support ticket creation
* Meeting summaries
* Calendar scheduling
* Team productivity tracking

## License

Licensed under the MIT License.
