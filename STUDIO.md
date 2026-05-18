# ionstudioapps — Studio

## Mission

Build focused tools that make everyday work feel lighter. We ship software that removes friction from how people think, collaborate, and get things done.

---

## Products

### wheeltodo
A wheel-spin task manager for iOS, Android, and web. Instead of staring at an endless to-do list, you spin a wheel and commit to one thing. Built on Next.js and Expo.

### rocky
An AI team assistant for Slack that connects your Notion workspace, Google Calendar, and team memory. Ask it anything about your tasks, schedule, or team — it figures out the rest. Built on Node.js and Claude.

---

## Team

### Sua Kim
**Data / AI / Server**
- GitHub: [alexsuakim](https://github.com/alexsuakim)
- Email: alexsuakim@gmail.com
- Figma: alexsuakim@gmail.com

### Amithi Liyanagamage
**Full Stack / UI/UX / Client**
- GitHub: [amithia](https://github.com/amithia)
- Email: aliyanagamage@gmail.com
- Figma: a.amithi01@gmail.com

### Johanna Schwabe
**Creative Director / Social Media / Project Manager / Design**
- GitHub: [johannaschwabe](https://github.com/johannaschwabe)
- Email: johannaschwabe01@gmail.com

### Paoli
**PR / Marketing / Event Management / HR**
- GitHub: [paolilm](https://github.com/paolilm)
- Email: paolamarkart@gmail.com

### Jade Kang
**Marketing / Design**
- Email: lilykang0331@gmail.com

---

## Brand Identity

### Tone of Voice
- Friendly but sharp
- Direct — we say what things do, not what they feel like
- Slightly playful (the wheel spin is intentional)
- Confident without being corporate
- Human — written by people who actually use the products

### Brand Concepts

**"One thing at a time"**
The core philosophy behind wheeltodo. Productivity isn't about doing more — it's about doing the right thing next. The wheel forces a decision and removes the paralysis of choice.

**"Your team, amplified"**
Rocky doesn't replace how your team works — it plugs into the tools you already use (Slack, Notion, Calendar) and makes the whole thing smarter. No new dashboards, no context switching.

**"Built in the open"**
We build tools we use ourselves. Progress is shared, decisions are explained, and the community is part of the process.

### UI Concept: One palette — two states of mind

> *Let the user choose how the app should meet them today.*

The same colour palette expresses two distinct emotional modes. Users pick the one that matches where they are right now.

| Mode | Name | Feel | Background |
|------|------|------|------------|
| ☀️ Gentle Boost | **Warm start** | Lighter, warmer, gently uplifting | Cream / off-white |
| 🌙 Grounding Mode | **Slow down** | Calming, grounding, emotionally regulating, safe during overwhelming moments | Deep dark purple (`#1E1B2E` range) |

The wheel uses the same 8 colours in both modes — warm and bright in Gentle Boost, muted and desaturated in Grounding Mode. The palette doesn't change; the world around it does.

This isn't just a dark/light mode toggle — it's an intentional emotional design choice that lets the app meet the user where they are.

#### ⚠️ Accessibility consideration (Sua)
The muted, low-contrast palette is intentional — but needs to be checked against accessibility standards for users with colour blindness or low vision. Apple and Google won't reject the app for this, but it's a real inclusivity concern. This applies to other parts of the app too, not just the palette.

**To do (when we get to it):**
- [ ] Run palette through a contrast checker (WCAG AA minimum: 4.5:1 for text)
- [ ] Test both modes with a colour blindness simulator (e.g. Stark in Figma)
- [ ] Audit existing app screens for accessibility issues
- [ ] Consider adding an optional high-contrast mode

### Visual Direction
- Clean and minimal — space to breathe
- Playful accents — the wheel, motion, colour
- Not corporate, not childish — somewhere between a studio and a game

### Colour Palette

**A new palette: warm, muted, breathable.**

| Name | Hex | Use |
|------|-----|-----|
| Peach | `#EDB590` | Primary accent |
| Coral | `#E59880` | Hover / active states |
| Honey | `#F0D29D` | Background tints |
| Sage | `#BCD4A5` | Success / positive |
| Mint | `#9DC4BC` | Secondary accent |
| Lavender | `#ADA8CC` | Focus / highlight |
| Lilac | `#D4A5C8` | Tags / labels |
| Blush | `#EDBDAC` | Soft backgrounds |
| Ink | `#2A2520` | CTAs, titles, body text — charcoal instead of pure black |

### Typography
> TBD — add font names and weights here

### Logo
> TBD — add logo files to `/assets/logo/`

---

## Marketing

### Target Audiences

**wheeltodo**
- Individuals overwhelmed by traditional to-do lists
- Students and young professionals
- People who respond to gamification and momentum

**rocky**
- Small teams (5–15 people) on Slack + Notion
- Startups and indie studios
- Teams that want AI assistance without switching tools

### Social Channels

| Platform | Handle | Owner | Status |
|----------|--------|-------|--------|
| Instagram | TBD | Jade / Johanna | — |
| TikTok | TBD | Jade / Johanna | — |
| Twitter/X | TBD | Sua | — |
| LinkedIn | TBD | Paoli | — |

### Launch Checklist

**App Store / Play Store**
- [ ] App Store copy (title, subtitle, description, keywords)
- [ ] Play Store copy
- [ ] Screenshots (iPhone, iPad, Android)
- [ ] Preview video

**Product Hunt**
- [ ] Tagline
- [ ] Description
- [ ] First comment (maker story)
- [ ] Gallery assets
- [ ] Hunter outreach

**Launch Week Content**
- [ ] Countdown posts
- [ ] Feature reveal series
- [ ] Behind-the-build post
- [ ] Demo video (wheel spin + rocky answering a question)

### Ongoing Content Ideas
- Weekly "what did you spin today?" social challenge
- Short devlogs — what shipped this week
- "How we use rocky" — real workflow walkthrough
- User spotlights once launched

### Partnerships
- [ ] Productivity YouTubers / newsletter writers
- [ ] Notion community (rocky is a natural fit)
- [ ] Student / university clubs for wheeltodo
- [ ] Indie hacker communities (IH, Buildspace alumni)

---

## Assets

> Store all brand assets in `/assets/`

```
assets/
├── logo/
├── screenshots/
│   ├── wheeltodo/
│   └── rocky/
├── social/
└── press-kit/
```
