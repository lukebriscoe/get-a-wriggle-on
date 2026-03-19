# Get a Wriggle On! — Backlog

## In progress / current MVP
- [x] Kanban board (To Do → Done)
- [x] Add / delete tasks
- [x] Confetti on task completion + "Mission Complete" celebration
- [x] Daily auto-reset (date-based, with midnight check)
- [x] Emoji picker per task
- [x] Progress bar in header
- [x] localStorage persistence
- [x] iPad-optimised touch UI

---

## Near-term ideas

### Speed challenge / time tracking
- Record timestamp when a task is moved to Done
- Show time taken next to each completed task
- "Personal best" tracking — store fastest time per task in localStorage
- Head-to-head mode: two kids race to complete the same board (split-screen or separate URLs with a shared leaderboard via a small backend)

### Mini games / rewards
- Unlock a mini-game (e.g. a simple reaction game or word puzzle) once all tasks are done
- Spin-the-wheel reward screen (extra screen time, choose dinner, etc.)
- Daily "bonus challenge" card (e.g. "Do 10 jumping jacks for +1 star")

### Personalisation
- Choose a character / avatar per kid (animal, superhero, etc.)
- Custom board name per child ("Ella's Get a Wriggle On!")
- Background themes: space, jungle, underwater, etc.
- Task card colour customisation

### Streaks & achievements
- Daily streak counter ("7 days in a row!")
- Badge/trophy cabinet for milestones
- Weekly summary screen (how many tasks completed this week)

### Multi-child support
- Profile switcher on the home screen (each child has their own task list + progress)
- Shared family leaderboard

---

## Product / launch ideas (UK & beyond)

### Core product direction
- Turn into a PWA (installable to iPad home screen — works offline, feels native)
- Family subscription model: free tier (1 child, default tasks) + paid (multi-child, games, themes)
- Onboarding flow: "Set up your morning in 2 minutes" with suggested task templates by age group

### Growth & distribution
- App Store (React Native port) — reaches parents who search "kids routine app"
- School newsletter / parent Facebook group seeding — organic word of mouth
- Partner with family influencers / parenting bloggers for launch
- ProductHunt launch

### Monetisation options
- Freemium SaaS (monthly/annual family subscription)
- One-time purchase (simpler, lower friction for families)
- White-label for schools / nurseries

### Tech scale-up
- Backend (Node/Supabase) for cross-device sync — important for families with multiple devices
- Parent dashboard: view kids' completion history, set tasks remotely
- Push notifications / morning reminder alarm
