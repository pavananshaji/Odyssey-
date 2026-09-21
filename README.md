# COLLEGO

**One app for your entire college life.**

## Problem Statement

Students hear about hackathons and college events too late, or never. A hackathon is announced through posters and group chats, the registration deadline passes, and a student finds out afterwards.

The problem we solve is wider than just events. 
Attendance, notes, timetables and event information all live in different,scattered and completely disorganized places, so students miss registrations and opportunities, and organizers cannot reach the people they built the event for. making it a loss for both parties.

## Project Description

COLLEGO is one app where a student manages their whole college life and also sees what is happening at other colleges.

- **Your college space:** attendance, timetable, notes and exam resources in one place.
- **Explore other colleges:** find hackathons and events happening outside your own college.
- **Never miss an opportunity:** a hackathon notice board with registration status (open, closing soon, live, ended) so students see the deadline before it passes.
- **Registration:** pick a hackathon, fill a short form and get a registration slip.

**What makes it useful:** one place instead of scattered WhatsApp groups and forms, and deadlines shown to students before registration closes.

**Business model:** colleges are the main paying customers (subscriptions, transaction fees and ads to reach students). Student advertisers pay a subscription, and students pay a small amount.

### Current status

Update this list to match what your team actually built.

- [ ] Landing and pitch website
- [ ] Hackathon notice board with status filters
- [ ] Registration form and registration slip (front end)
- [ ] Real database and login
- [ ] Attendance, timetable and notes screens

## Google AI Usage

> Fill this section with what your team actually used. Do not list a tool that was not used.

### Tools / Models Used

- [Name the Google AI tool or model, for example the exact Gemini model or Google AI Studio]

### How Google AI Was Used

[Explain clearly where the AI is integrated in the project and what it does. Describe the real feature, the input it takes and the output it gives.]

## Tech Stack used

- **Front end:** React with Vite (JavaScript), CSS
- **Version control:** Git and GitHub
- **Hosting:** Netlify
- **Database and login:** [Supabase or Firebase, if you used one. Delete this line if not.]
- **AI assistants used while building:** Claude (planning, research and interface drafting), [add the Google AI tool here if used]

## GitHub repo link of the project

[https://github.com/pavananshaji/Odyssey-](https://github.com/pavananshaji/Odyssey-)
## Team

- [Hadhi Mohammed K P](https://github.com/their-username)
- [Muhammed Sherief](https://github.com/their-username)
- [Pavanan](https://github.com/pavananshaji)
- [Sooraj](https://github.com/their-username)

## Proof of Google AI Usage

Proof is in the `/proofs` folder.

- None,we only used Claude.🤫️

## Screenshots

Screenshots are in the `/screenshots` folder.

- `screenshots/home.png`: landing page
- `screenshots/hackathons.png`: hackathon notice board
- `screenshots/registration.png`: registration form
- `screenshots/registration-slip.png`: registration slip

## Demo Video

Demo video (maximum 3 minutes): [Watch Demo](https://drive.google.com/file/d/1PcC11SxIMa6iLDQTFSM5iVjvOYex9HDt/view?usp=sharing)

Paste the Google Drive shareable link above and check that anyone with the link can view it.

## Installation Steps

**Requirements:** [Node.js](https://nodejs.org) (LTS version) and Git.

1. Clone the repository:
   ```
   git clone https://github.com/pavananshaji/Odyssey-.git
   ```
2. Go into the project folder:
   ```
   cd Odyssey-
   ```
3. Install the dependencies:
   ```
   npm install
   ```
4. Start the development server:
   ```
   npm run dev
   ```
5. Open the address printed in the terminal, usually `http://localhost:5173/`.

**Environment variables (only if your project uses a database or an AI API):** create a `.env` file in the project root and add your keys there. Never commit this file to GitHub.

```
VITE_SUPABASE_URL=your-project-url
VITE_SUPABASE_ANON_KEY=your-anon-key
VITE_GEMINI_API_KEY=your-api-key
```

**Build for production:**

```
npm run build
```

The output is in the `dist` folder, which you can deploy to Netlify.
