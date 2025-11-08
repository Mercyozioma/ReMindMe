# ReMindMe 

**ReMindMe** is a self-messaging productivity app that **helps you to capture, organize, and recall your personal notes, links, screenshots, and voice reminders in one unified place**. Instead of scattering reminders across multiple apps like WhatsApp, Slack, Telegram, or email drafts, **ReMindMe** brings everything together, automatically organizes it, and notifies you at the right time or context.

---

## What the Product Does
ReMindMe automatically; 
- Captures messages, links, screenshots, and voice notes you send to yourself  
- Categorizes and tags each note (e.g., Task, Idea, Media)  
- Resurfaces notes at the right time with smart reminders (time-based or event-based)  
- Integrates with apps you already use: WhatsApp, Slack, Telegram, Gmail, and Google Calendar  
- Keeps your personal memory organized without changing your natural workflow

---

## Why It Matters
We all have the habit of sending messages to ourselves to remember ourselves of things later. But these notes often get lost across multiple apps. ReMindMe **turns this scattered habit into an organized, searchable memory system**, so you never lose track of your ideas, tasks, or media.

---

## Who It's For
- _Anyone who frequently sends self-messages to remember things_
- _Students and lifelong learners_    
- _Busy professionals_

---

## Key Features
| Feature | Description | Technology / Tools |
|---------|------------|------------------|
| Capture | Quickly send messages, links, screenshots, or voice notes | React Native frontend, Node.js API |
| Organize | Automatic tagging and categorization of notes | Node.js, PostgreSQL, AI categorization engine |
| Recall | Smart reminders based on time or location | Firebase Cloud Messaging, Redis caching |
| Integration | Connect with WhatsApp, Slack, Telegram, Gmail, Google Calendar | OAuth2, platform APIs |
| Search | Find notes by keyword, type, date, or source | PostgreSQL full-text search, indexed queries |
| Archive | Notes automatically archived after completion | PostgreSQL, backend scheduler |

---

## How It Works
This is how the app works;
1. Open ReMindMe or use voice input, e.g., **_“Remind me to call Mark at 4 PM.”_** 
2. The note is then stored, auto-tagged, and categorized.  
3. Smart notifications alert you at the right time.  
4. Completed notes are archived for later search and reference.

---

## Example User Journey
- Mercy sees a post idea on LinkedIn and shares it to her WhatsApp **_“Saved Messages.”_**
- She also sends herself a Slack note: **_“Engineers feedback by Friday.”_** 
- Later, she opens ReMindMe and finds both items already listed under:  
  - Links to Review  
  - Tasks This Week  
- She sets a reminder for the Slack note, and ReMindMe notifies her automatically in real time.  

---

## Key Screens
- **Home Feed:** This is the stream of all self-messages, labeled and timestamped  
- **New Reminder:** Quick entry for text, voice, or attachments  
- **Smart Recall Dashboard:** Categorized memory board (Tasks, Ideas, Screenshots, Voice Notes)  

---

## Visuals
View Interactive Figma Diagram:**  
[ReMindMe Architecture on Figma](https://www.figma.com/design/x1LpliDs0SSlYyNN9pm2ng/HNG-PROJECTS?node-id=0-1&t=g3ueDqgxZMjfuC3P-1)
