# MindMirror — Not a Chatbot. A Presence.

> 1 billion people live with unmet mental health needs. Most solutions are static — apps you open and close. MindMirror is different. It comes to you, notices you, and stays with you.

---

## 🧠 What is MindMirror?

MindMirror is a **real-time video AI companion** built on TruGen AI. It doesn't wait for you to describe how you feel — it already has a sense of it. Through your camera and microphone, it reads your facial expressions, body posture, voice tone, and energy level, then responds with genuine warmth and care.

It is not a therapist. It is not a chatbot. It is something new — **a presence that pays attention.**

---

## ✨ Key Features

### 🎥 Real-Time Emotion Detection
Using TruGen's Hawkeye-1 vision model, MindMirror continuously reads:
- Facial expressions and micro-movements
- Eye contact and gaze patterns
- Voice tone, pace, and energy level

### 🔄 Three Adaptive Modes
| Mode | Trigger | What Happens |
|------|---------|--------------|
| **Grounding Mode** | Anxiety, panic, overwhelm | Live breathing exercises with haptic sync |
| **Companion Mode** | Loneliness, low mood, withdrawal | Interactive games, stories, warm conversation |
| **Reflection Mode** | User wants to talk | CBT-style reframing, gentle journaling prompts |

### 🛠️ Real-World Tool Integrations
- **Word Game API** — interactive games to lift mood in Companion Mode
- **Crisis Alert Webhook** — silently fires when serious distress is detected, logs to monitoring dashboard
- **Google Sheets Logger** — every session is automatically logged with mood, mode used, and summary

### 🧰 Physical Hardware Layer
- **Mood Lamp** — Arduino-powered RGB lamp that shifts color based on detected emotion in real time
- **Haptic Feedback Pad** — palm-sized pad that pulses in sync with breathing exercises, making grounding physical and felt

### 🧬 Memory Across Sessions
MindMirror remembers your triggers, what helped you before, your patterns, and your progress. Every session picks up with genuine continuity — it knows you.

User's Browser
│
▼
TruGen iFrame (video agent, camera, mic)
│
▼
TruGen Backend (Huma-1 Avatar + Hawkeye-1 Vision + Memory)
│
▼ Webhooks
Backend Server
│
├──► Google Sheets (Session Logging)
├──► Webhook.site (Crisis Alert Monitor)
└──► Arduino (Mood Lamp + Haptic Pad)

Or clone and open locally:

```bash
git clone https://github.com/yourusername/MindMirror
open mindmirror.html
```

---

## 🗺️ Roadmap

| Phase | What's Coming |
|-------|--------------|
| Phase 2 | Longitudinal mood tracking dashboard, multimodal stress ball input |
| Phase 3 | Apple Watch / Fitbit biometric integration |
| Phase 4 | Bridge to licensed therapists, peer support groups |
| Phase 5 | Full smart home integration — ambient lighting, sound, temperature |

---

## 💬 The Pitch

> *"There are 1 billion people globally with unmet mental health needs. Most solutions are static — apps you open and close. MindMirror is the first agent that comes to you, notices you, and stays with you — not as a therapist, but as something new: a presence that actually pays attention. And for the first time, that presence isn't just on your screen — it's in the room with you."*

---
---

## 🏗️ Architecture
