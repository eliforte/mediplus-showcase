# MediPlus — Medical Scheduling with AI Consultation Assistants

> Public summary. The source code is private; this repository describes what was built, how, and with which stack.

MediPlus is a web platform for clinics to manage appointments and support doctors during consultations with AI. Patients are pre-registered and scheduled, and during the consultation AI agents transcribe the conversation and draft the clinical conduct and a diagnostic hypothesis, which the doctor reviews and exports as a PDF.

**My role:** Full-stack development, including the AI agents and their integration.

## Key features

- **Scheduling** — patient pre-registration, booking, confirmation, cancellation and remarks.
- **Doctor dashboard** — list of appointments and consultations with empty and loading states.
- **AI consultation assistants** — agents for transcription, clinical conduct and diagnostic hypotheses, built on the OpenAI API.
- **PDF output** — preview and export of the consultation conduct.

## Tech stack

| Layer | Technologies |
|---|---|
| Frontend | Next.js, React, TypeScript, Tailwind CSS, shadcn/ui + Radix UI, Zustand, React Hook Form, Zod, React PDF |
| Backend | Node.js API |
| Data | PostgreSQL |
| AI | OpenAI (transcription and agents) |
| Infra | Docker Compose, GitHub Actions |
