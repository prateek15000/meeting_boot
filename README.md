# MeetingBot - AI Meeting NoteTaker

![MeetingBot - AI Meeting NoteTaker](https://meetingbot3.s3.us-east-1.amazonaws.com/FULL+STACK.png)

## Upcoming Features

- [ ] Integrations
   - [ ] Notion Integration
   - [ ] Linear Integration
   - [ ] Salesforce Integration
   - [ ] Hubspot Integration
- [ ] For past meetings:
    - [ ] Users should be able to search through their meetings
    - [ ] Date based filtering (ex: March 17 to April 1)
    - [ ] Custom date range filtering (ex: last week, last month, last quarter)
    - [ ] Meeting duration filtering (ex: less than 30 mins)
    - [ ] Participant-based filtering
- [ ] 100+ languages transcript translation (similar to Fireflies.ai)  
      Users will be able to view their transcripts in over 100 languages using Google Cloud Translation API.
- [ ] Workspaces Creation
    - [ ] Users can create a workspace
    - [ ] Users can invite other people to their workspace
    - [ ] Role-based access control

## Contributing

Any contributions are welcome!  
Pick a feature from the list above (or reach out if you have another idea) and open a PR 🤛

---

# Overview

**MeetingBot** is an open-source meeting intelligence platform that automatically joins your video calls on **Zoom, Google Meet, and Microsoft Teams** to provide **AI-powered transcription, summaries, and insights**.

The platform includes:
- Real-time calendar sync
- AI-driven meeting analysis
- Action item detection
- Smart integrations with productivity tools

This project demonstrates how to build a **complete SaaS** application with **AI, automation, and integrations** using technologies such as **Next.js, OpenAI, Pinecone, AWS, Stripe, and more**.

---

# Features

- 🤖 Automatic AI bot deployment to Zoom, Google Meet, and Microsoft Teams
- 📝 Meeting transcription with speaker identification and diarization
- 🧠 AI-generated meeting summaries and action items using OpenAI
- 📅 Real-time Google Calendar synchronization
- 💬 Chat with your meetings using conversational AI powered by Pinecone
- 🔍 Semantic search across all meeting transcripts and summaries
- 🔗 Sync action items to Jira, Asana, and Trello
- 💬 Native Slack bot integration with `@meetingbot` commands
- 💳 Stripe subscription management (three-tier system)
- 🔒 Secure authentication and session management with Clerk
- 🎨 Modern responsive UI (Next.js 15, Tailwind CSS 4, Shadcn UI)
- 📊 Meeting dashboard with audio playback and detailed insights
- 📅 Upcoming and past meetings with filtering and navigation
- 💭 Chat interface for individual and global meeting conversations
- ☁️ Automated bot scheduling with AWS Lambda and EventBridge
- 🛡️ Webhook validation with Svix for enterprise-grade security
- 🗄️ AWS S3 storage for audio files and user profile images
- 🎯 Custom bot personalization (name & avatar)
- 📧 Automated post-meeting notifications via Resend
- 🔔 Real-time notifications using Sonner toast system
- 🌙 Dark mode support with Next Themes
- ⚙️ State management via React Context hooks
- 🗄️ Prisma ORM + PostgreSQL for data persistence

---

# Technologies and Frameworks

- **Frontend:** Next.js 15, TypeScript, Tailwind CSS 4, Shadcn UI  
- **Backend:** Node.js, AWS Lambda, AWS S3, AWS EventBridge, Prisma ORM  
- **Database:** PostgreSQL  
- **AI & Search:** OpenAI API, Pinecone Vector Database  
- **Auth & Payments:** Clerk, Stripe  
- **Integrations:** Slack Bolt Framework, Resend, Svix  
- **State Management:** React Context, @tanstack/react-query  
- **UI Enhancements:** Sonner Toasts, React H5 Audio Player, Next Themes

---

# Installation & Setup

Follow these steps to run MeetingBot locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/cooldude6000/meeting-bot69.git
   cd meeting-bot69
