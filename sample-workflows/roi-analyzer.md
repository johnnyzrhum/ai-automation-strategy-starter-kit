# ROI Analyzer: Prioritizing AI Automation Projects

This use case helps you assess the business value of an AI automation idea—before building it—using a fast, lightweight framework to score potential ROI.

---

## 🎯 Goal

Answer the question: “Is this automation idea worth pursuing right now?”

This framework helps you:
- Estimate impact and effort quickly
- Avoid investing in low-value automations
- Prioritize ideas that can scale or show quick wins

---

## 🧩 Use Case: AI Summarization of NPS Survey Feedback

**Automation Idea**  
Use an AI model to summarize open-ended NPS survey responses and flag any critical feedback for internal follow-up.

---

## 📊 Evaluation Framework

### 🟢 1. Potential Benefits
- ⏱ **Time saved**: ~5 hours/week per analyst
- 🧠 **Risk reduction**: Reduces subjective bias in flagging
- 💬 **Business impact**: Faster feedback loop for product & CX teams

---

### ⚙️ 2. Implementation Effort
- ⚠️ **Complexity**: Medium (requires summarization, filtering logic)
- 💸 **Cost**: Low (OpenAI API + Airtable or Google Sheets)
- 🔧 **Integration**: Moderate (could use Zapier, Make, or direct webhook into Slack)

---

## 🧮 3. Impact vs. Effort Matrix

|                | Low Effort | Medium Effort | High Effort |
|----------------|------------|----------------|--------------|
| **High Impact**| ✅ Pilot Now | 🔜 Plan Project | ⚠️ Caution |
| **Medium Impact** | 🟢 Quick Win | 🔄 Wait        | ❌ Skip |
| **Low Impact**| ⚪ Ignore    | ❌ Skip        | ❌ Skip |

➡️ This project scores as **High Impact / Medium Effort**  
🔁 **Next Step**: Prioritize and test in the next sprint with a limited pilot.

---

## 📐 Output Template

Use this format to evaluate any automation idea:


---

## 💬 Suggested Prompt

📄 [`prompts/roi-analyzer.txt`](../prompts/roi-analyzer.txt)

Use this prompt with ChatGPT to:
- Analyze your idea's potential benefits
- Estimate technical effort
- Score it on the matrix
- Receive a go/no-go recommendation

---

## 📝 Tips for Use

- Use before investing time into a prototype or PoC
- Great for working sessions with cross-functional teams
- Keep output in a shared tracker for visibility and comparison

---

## 🧰 Tools You Can Use

- **AI Models**: ChatGPT, Claude, Gemini
- **Automation Tools**: Zapier, Make, Retool
- **Docs & Tracking**: Google Sheets, Airtable, Notion
- **Notification Layer**: Slack, MS Teams, or email

---

*This file is part of the [AI & Automation Strategy Starter Kit](../README.md). Explore related use cases and prompts throughout the repo.*
