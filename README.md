# 🤖AI Interview Agent (with Vapi Voice Integration)

An AI-powered, voice-interactive interview assistant built with [Vapi.ai](https://vapi.ai), OpenAI, Supabase, and Next.js. The app conducts real-time voice interviews, generates tailored questions, analyzes candidate responses, and produces a comprehensive performance report with scoring and hiring recommendations.

---

## What It Does

- **Voice-based Interviews**  
  Real-time interviews using **Vapi.ai** (GPT-4 + TTS + STT).

- **Conversational AI Flow**  
  Friendly opening, question-by-question interaction, dynamic feedback.

- **Performance Report**  
  AI evaluates answers and generates:
- Skill scores (technical, communication, problem-solving, etc.)
- Strengths and weaknesses summary
- Final score and hiring recommendation

- **Automatic Feedback Storage**  
  Results are saved in **Supabase** for later viewing.

---

## Stack

| Tool                      | Purpose                                       |
| ------------------------- | --------------------------------------------- |
| **Next.js 15**            | Frontend framework                            |
| **React 18**              | UI rendering                                  |
| **Vapi.ai Web SDK**       | Voice interface (speech input/output + GPT-4) |
| **OpenAI API (via Vapi)** | Question generation + feedback analysis       |
| **Supabase**              | Realtime database & auth                      |
| **Radix UI**              | Dialogs, tooltips, and interactive UI         |
| **Tailwind CSS v4**       | Styling                                       |
| **Sonner**                | Notifications                                 |
| **Moment.js**             | Date formatting                               |

---

## Live Demo

> 🔗 [Try it now on Vercel](https://ai-interview-agent-peach.vercel.app/)

---
