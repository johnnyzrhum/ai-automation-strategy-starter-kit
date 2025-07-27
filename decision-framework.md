# Decision Framework: Should You Automate It?

This lightweight decision framework helps you prioritize automation opportunities based on impact, effort, and readiness.

Use this after identifying ideas with the [Opportunity Worksheet](./opportunity-worksheet.md).

---

## 🎯 Goal

Evaluate whether an AI or automation project is worth piloting now, planning later, or shelving altogether.

---

## 🔍 Step 1: Quick Scoring Criteria

Score each proposed automation on a scale of 1–5:

| Category                | 1 (Low)       | 3 (Medium)            | 5 (High)                   |
|-------------------------|---------------|------------------------|----------------------------|
| **Impact**              | Little value  | Helps some users       | Major business benefit     |
| **Effort to implement** | Very high     | Moderate               | Very low / quick to test   |
| **Risk level**          | High (disruptive) | Medium (testable) | Low (safe to pilot)        |
| **Team readiness**      | No ownership  | Some support           | Fully supported            |

Add up your total score (out of 20).

---

## 📊 Step 2: Matrix-Based Recommendation

| Total Score | Recommendation     | Action                                      |
|-------------|--------------------|---------------------------------------------|
| 17–20       | ✅ Pilot Now        | Build a quick prototype                     |
| 13–16       | 🔜 Plan to Test     | Add to roadmap or test in next cycle        |
| 9–12        | 🔄 Explore More     | Needs clarification or stakeholder buy-in   |
| < 9         | ❌ Skip for Now     | Too complex or low-value at this time       |

---

## 🖼️ Visual Matrix

```mermaid
graph TD
    A[High Impact<br>Low Effort] -->|✅| B[Pilot Now]
    A2[High Impact<br>High Effort] -->|🔜| B2[Plan Project]
    A3[Low Impact<br>Low Effort] -->|🟢| B3[Quick Win]
    A4[Low Impact<br>High Effort] -->|❌| B4[Skip]
