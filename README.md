
# 🚦 HITL – Human-in-the-Loop AI Middleware

> 🧠 Add fail-safes to your AI agents in 60 seconds — no more silent failures or silent breakdowns.

**HITL (Human-in-the-Loop)** is an SDK & CLI middleware that gives your AI agents the power to **escalate to a real human in real-time** via SMS, Slack, or Voice. Instead of hallucinating or breaking, your agent pauses, alerts a human, gets help — and continues the job.

---

## ⚠️ PRE-LAUNCH: EARLY ACCESS

We're building HITL *with* the dev community. Join now to shape the roadmap and get early access to our Pilot tier with bonus perks.

---

## 🚀 What Is HITL?

HITL (Human-in-the-Loop) brings **real-time human input** to any AI workflow.

🔁 **When your agent hits a wall** — low confidence, unhandled error, or decision fork — it can:

- ✅ **Escalate** to a human in real time  
- ✅ **Wait** for input (SMS, Slack, or Voice)  
- ✅ **Continue** its task using that input  

> Think: **AI → Human → AI** — the missing loop for reliable autonomy.

---

## 🧐 Why HITL?

Autonomous agents are powerful, but brittle. They hallucinate, get stuck, or fail silently.

**HITL is your AI safety net:**

- 🧠 **Smarter:** Let agents pause & ask for help when unsure  
- 🛡️ **Safer:** Bring human oversight to critical decision points  
- ✅ **Reliable:** Keep workflows moving, even when AI fails  
- 💬 **Cross-Channel:** Escalate via Slack, SMS, or Voice  

---

## 👥 Who Should Use HITL

- 👨‍💻 **AI Developers:** Using LangChain, OpenAI, or AutoGen  
- 🚀 **Startups/Teams:** Running customer-facing or regulated workflows  
- 🧩 **Consultants:** Adding real-time guardrails to client deployments  

---

## 🧪 Quickstart (Coming Soon)

### Install the SDK
````markdown


```bash
pip install hitl
````

### Escalate from your AI agent

```python
from hitl import escalate

response = escalate(
    message="The AI needs human input to choose between A or B.",
    context={"agent_id": "agent_007", "critical": True}
)
```

### CLI & Cross-Channel Commands (Planned)

* `hitl dash` → View usage, tier, and upgrade options
* `hitl hist` → View escalation history
* SMS: Reply `"dash"` or `"hist"`
* Slack: DM `"dash"` or `"hist"`
* Voice: Listen to usage, history, and escalate live

---

## 💸 Early Access — Preorder the Pilot Plan

### 🎟️ **Pilot Tier – \$149 One-Time**

| Plan      | Price              | Escalations | Channels    | Voice | Notes                                           |
| --------- | ------------------ | ----------- | ----------- | ----- | ----------------------------------------------- |
| **Pilot** | **\$149 one-time** | 150 total   | Slack + SMS | ✅     | Early Voice access, Beta badge, no overage fees |

> 🔐 [**Pre-order Pilot on Stripe →**](https://buy.stripe.com/aFa3cw3n7eBY5Omh2Idwc00)

**Coming Soon:**

* Trial: Free (5 total escalations)
* Starter: \$49/mo
* Pro: \$149/mo
* Team: \$499/mo

---

## 🗺️ Roadmap

| Feature                         | Status          |
| ------------------------------- | --------------- |
| ✅ Stripe payments               | ✅ Live          |
| 🛠️ Python SDK (Slack/SMS)      | 🛠️ In progress |
| 🛠️ CLI dashboard (`hitl dash`) | 🛠️ In progress |
| 🔜 Voice escalation (Twilio)    | 🔜 Planned      |
| 🔜 Escalation history logs      | 🔜 Planned      |
| 🔜 Team routing/dashboard       | 🔜 Planned      |

---

## 🤝 Join Us

1. 📩 **Just want updates?**
   👉 [Join Early Access Waitlist](https://form.typeform.com/to/lGGTZRf6)

2. 🔥 **Want to support development & get early access?**
   👉 [Pre-order the Pilot Plan](https://buy.stripe.com/aFa3cw3n7eBY5Omh2Idwc00)

---

### 💬 Connect

* 💬 [Join our Discord](https://discord.gg/De9MhRXM)
* 🐦 [Follow on X/Twitter](https://x.com/hitlmiddleware)
* 📩 Email: [hitl@cyberservices.com](mailto:hitl@cyberservices.com)

---

## ⚠️ Legal Note

> **Important:** HITL is in early development. No usable product is immediately available. Your support helps fund buildout, shape the roadmap, and reserve your place in early beta access.

```

---





