> Real-time human escalation via SMS, Slack, and Voice for AI agents that get stuck, confused, or need approval.

🚧 **This project is under active development.**  
We’re onboarding early adopters now via **prepaid access to the $149 Pilot plan** — if you want to be one of the first 100 to build on HITL, claim your spot below.

---

## 🚀 What Is HITL?

HITL (Human-in-the-Loop) is a lightweight middleware layer for AI agents.

Whenever your AI agent (e.g. LangChain, AutoGen, OpenAI) encounters uncertainty, failure, or needs a human decision, it can:

✅ Escalate to a human in real-time  
✅ Wait for a human reply via SMS, Slack, or voice  
✅ Continue its workflow with that input  

It’s an "AI ↔ Human ↔ AI" feedback loop for autonomy with safety.

---

## 👥 Who This Is For

- **AI Developers** building autonomous agents with LangChain, AutoGen, or OpenAI
- **Teams** deploying AI into critical or regulated workflows
- **Startups** looking to bridge the gap between LLM automation and human control
- **Consultants** needing deployable HITL guardrails for clients

---

## 📦 Features (MVP in Development)

| Feature                        | Status         |
|-------------------------------|----------------|
| Python SDK                    | ✅ Live         |
| SMS + Slack Escalations       | ✅ Live         |
| Voice Escalation (Twilio)     | 🛠️ In progress  |
| CLI Dashboard (`hitl dash`)   | ✅ Live         |
| CLI History (`hitl hist`)     | ✅ Live         |
| Stripe Checkout (Pilot Only)  | ✅ Live         |
| Cross-Channel Usage Access    | ✅ CLI/SMS/Slack|
| Webhook & Zapier Support      | 🧪 Beta         |

---

## 💻 Quick Start

Install the SDK:
```bash
pip install hitl
````

Trigger an escalation from your AI agent:

```python
from hitl import escalate

response = escalate(
    message="The AI needs human input to choose between option A or B.",
    context={"agent_id": "xyz123", "critical": True}
)
```

---

## 📊 Check Usage & History

From **anywhere** you can check your plan, usage, and escalation logs:

| Channel | Command or Keyword        |
| ------- | ------------------------- |
| CLI     | `hitl dash`, `hitl hist`  |
| SMS     | Text `"dash"` or `"hist"` |
| Slack   | DM `"dash"` or `"hist"`   |
| Voice   | Info is read aloud        |

---

## 💸 Early Access Pricing (Pilot Plan Only)

We are currently offering **one prepaid access tier** during development:

| Plan      | Price              | Escalations | Channels    | Voice | Notes                                    |
| --------- | ------------------ | ----------- | ----------- | ----- | ---------------------------------------- |
| **Pilot** | **\$149 one-time** | 150 total   | Slack + SMS | ✅     | Includes early Voice access + beta badge |

> 🔐 All other plans (Starter, Pro, Team) are **future roadmap** — Pilot users will get priority migration and perks.

> 🔁 No overage billing — just re-up manually after 150.

👉 [🎟️ Claim Pilot Access – \$149 One-Time](https://buy.stripe.com/aFa3cw3n7eBY5Omh2Idwc00)

---





# 🚦 HITL – Human-in-the-Loop AI Middleware

**When your AI agents get stuck, HITL will escalate to you (or your team) in real time via Slack, SMS, or Voice—so workflows never fail silently.**

> 🛠️ **⚠️ PRE-LAUNCH EARLY ACCESS**
> HITL is still in **active development**.
>
> * We’re gathering **early supporters** & feedback
> * Pre-ordering Pilot helps fund development & gives you **priority access** when we launch

---

## 🧐 Why HITL?

AI agents are powerful but brittle. When they hit low confidence or a decision point, they:

❌ Hallucinate
❌ Break workflows
❌ Lose user trust

✅ **HITL fixes this.**
When your AI is stuck, it will **pause**, **escalate to you or your team in real time**, get your input, and **resume seamlessly**.

---

## 🚀 How It Will Work

1️⃣ **AI detects low confidence or a decision point**
2️⃣ **AI escalates to you (or your team)** via Slack, SMS, or Voice call
3️⃣ **You respond → AI resumes workflow**

---

## 🛠️ Current Status

HITL is **NOT LIVE YET**.

We’re building the core:

| Feature                          | Status             |
| -------------------------------- | ------------------ |
| Python SDK for Slack/SMS         | 🛠️ In development |
| CLI dashboard (`hitl dash`)      | 🛠️ In development |
| Voice escalation (Twilio)        | 🛠️ Planned        |
| Cross-channel escalation history | 🛠️ Planned        |
| Stripe payment & upgrades        | 🛠️ Planned        |
| Team routing & admin dashboard   | 🛠️ Planned        |

**By joining Early Access or pre-ordering Pilot:**
✅ You’ll help shape the roadmap
✅ You’ll be first in line when Beta launches
✅ Pilot buyers will get **priority onboarding** when features go live

---

## 🔧 What’s Coming

* **Simple Python SDK** to escalate AI decisions
* **Slack & SMS integration** for real-time notifications
* **Voice call support** for critical workflows
* **Cross-channel dashboard** to view usage & history anywhere
* **Hybrid pricing model** with Pilot early-access perks

---

## 💰 Early Access & Pilot Pre-Orders

HITL is still pre-launch. You can:

* ✅ **Join the Early Access waitlist** *(free)*
* ✅ **Pre-order Pilot access (\$149)** *(to support development & lock in priority Beta access)*

| Plan        | Status             | Price          | Notes                |
| ----------- | ------------------ | -------------- | -------------------- |
| **Trial**   | Coming after Beta  | Free (5 total) | Limited beta access  |
| **Pilot**   | **Pre-order now**  | \$149 one-time | Early supporter tier |
| **Starter** | Coming post-launch | \$49/mo        | Live usage           |
| **Pro**     | Coming post-launch | \$149/mo       | Scaling teams        |
| **Team**    | Coming post-launch | \$499/mo       | Enterprise           |

---

### 🚀 How to Join Early Access

1️⃣ **Want updates but not ready to pre-order?**
📩 [Join the Early Access Waitlist](https://form.typeform.com/to/lGGTZRf6)

2️⃣ **Want to support development + get priority Beta access?**
🔗 [Pre-order Pilot for \$149](https://buy.stripe.com/aFa3cw3n7eBY5Omh2Idwc00)

---

## ✅ Community & Feedback

Since this is **pre-launch**, we’re building with the community.

* 💬 **Join our [Discord Community](https://discord.gg/De9MhRXM)** *(for discussion & updates)*
* 🐦 **Follow us on [X (Twitter)](https://x.com/hitlmiddlewear)** *(progress updates)*
* 📩 **Have ideas? Email us at [hitl@cyberservices.com](mailto:hitl@cyberservices.com)**

---

## 📈 Roadmap

✅ Concept validation
🚧 SDK & Slack/SMS escalation in dev
🚧 Voice integration planned
🚧 Dashboard + history logging planned
🚧 Beta launch (date TBD)

**Want to influence the roadmap?**
📩 [Give feedback & vote on features](https://form.typeform.com/to/lGGTZRf6)

---

## ❗ Important Disclaimer

⚠️ **Nothing is live yet.**

HITL is in **pre-launch Early Access**.

* By **joining Early Access**, you’re helping shape the product
* By **pre-ordering Pilot**, you’re supporting development & locking in early access when Beta launches
* No immediate usable product will be delivered today

---

### TL;DR

**HITL = AI agent safety net (coming soon).**

We’re still building. You can:

* ✅ Join the Early Access waitlist
* ✅ Pre-order Pilot to support development & secure priority Beta access

🔗 [Pre-order Pilot](https://buy.stripe.com/aFa3cw3n7eBY5Omh2Idwc00) | 📩 [Join Early Access Waitlist](https://form.typeform.com/to/lGGTZRf6)

---

### 🔗 Quick Links

* **Early Access Waitlist** → [Typeform](https://form.typeform.com/to/lGGTZRf6)
* **Pilot Pre-Order** → [Stripe Checkout](https://buy.stripe.com/aFa3cw3n7eBY5Omh2Idwc00)
* **Post-Payment Onboarding** → [Typeform](https://form.typeform.com/to/B9S3NLsy)
* **GitHub Repo** → [HITLMiddleware](https://github.com/hitlcyberservices/HITLMiddleware)
* **Discord** → [Join Here](https://discord.gg/De9MhRXM)
* **Twitter/X** → [Follow Updates](https://x.com/hitlmiddlewear)
* **Email** → [hitl@cyberservices.com](mailto:hitl@cyberservices.com)

---

