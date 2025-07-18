### 📊 **Net Promoter Score (NPS)** — Explained

**Net Promoter Score (NPS)** is a **customer loyalty and satisfaction metric** that measures how likely your users are to **recommend your product, service, or company** to others.

It’s based on a **single question:**

> **"On a scale of 0 to 10, how likely are you to recommend \[Product/Company] to a friend or colleague?"**

---

## 🧮 **How NPS Works**

### 📋 Respondents are categorized:

| Score Range | Category       | Meaning                             |
| ----------- | -------------- | ----------------------------------- |
| **9–10**    | **Promoters**  | Loyal enthusiasts who recommend you |
| **7–8**     | **Passives**   | Satisfied but unenthusiastic        |
| **0–6**     | **Detractors** | Unhappy customers who may churn     |

---

### 📐 **NPS Calculation:**

```
NPS = % of Promoters − % of Detractors
```

* **Range:** -100 to +100
* **Good NPS:** Above 0 is positive. Above 50 is excellent. Above 70 is world-class.

---

### 📊 Example:

| Respondents | Score | Category   |
| ----------- | ----- | ---------- |
| 100 total   |       |            |
| 60 → 9–10   |       | Promoters  |
| 20 → 7–8    |       | Passives   |
| 20 → 0–6    |       | Detractors |

**NPS = (60%) − (20%) = +40**

---

## 📌 **Why NPS Matters in Product Management**

* Measures **customer satisfaction and brand loyalty**
* Helps identify **champions and churn risks**
* Drives **feature prioritization** (based on feedback)
* Used as a **KPI** for product success and team performance

---

## 🧰 **How to Collect NPS**

* In-product popups or modals
* Post-purchase emails
* Quarterly or annual surveys (e.g., via **Qualtrics**, **Delighted**, **Typeform**)

Include **open-ended follow-ups**:

> "What is the primary reason for your score?"

---

## 🎯 Best Practices

* **Segment by user type** (e.g., paid vs free, region, role)
* **Track over time** to spot trends
* Use NPS as a **conversation starter**, not just a number
* Pair with **qualitative feedback** to inform your roadmap

---

## 🔄 Example in Product Practice:

> “In our NGINX Security product, we tracked NPS quarterly. When scores dipped, we learned users struggled with UI navigation. We redesigned key flows and added in-app guides. In the next cycle, NPS rose from 38 to 54 and support tickets dropped 20%.”

---

Great! Below is a **template NPS survey** along with a guide on how to **integrate NPS into a product dashboard and OKR framework**.

---

## 📋 **Template NPS Survey**

### **Subject:**

> "We’d love your feedback – 30 seconds to help us improve"

### **Body:**

> **On a scale of 0–10, how likely are you to recommend \[Product Name] to a friend or colleague?**

* 0 → Not at all likely
* 10 → Extremely likely

\[🔘 Radio buttons from 0–10]

---

### **Follow-up (open text box):**

> **What’s the primary reason for your score?**
> *(Optional but helps us improve.)*

---

### ✅ **Optional Tagging Questions**

You can segment responses by adding:

* “What do you use \[Product Name] for?” *(Dropdown: Personal / Business / DevOps / Finance / etc.)*
* “How long have you been using \[Product Name]?” *(New / <6 months / >6 months / 1+ year)*

---

## 🧰 **Tools to Deploy This:**

* **In-app NPS tools:** [Delighted](https://delighted.com), [Wootric](https://wootric.com), \[Hotjar], \[Survicate]
* **Email-based tools:** Typeform, Google Forms, Qualtrics
* **Custom survey widget:** Embed using React or frontend modal and send to backend for logging

---

## 📊 **Integrating NPS into a Product Dashboard**

Use tools like:

* **Grafana, Power BI, Tableau**, or
* Lightweight tools like **Retool**, **Metabase**, or **Google Data Studio**

### 🔹 Key NPS Metrics to Display:

| Metric                       | Description                     |
| ---------------------------- | ------------------------------- |
| **NPS Score (Overall)**      | Line chart by month/quarter     |
| **NPS by Segment**           | Role, region, or plan type      |
| **Promoter/Detractor Count** | Absolute numbers & ratios       |
| **Top Feedback Themes**      | Word cloud or keyword frequency |
| **NPS vs. Feature Usage**    | Are power users more satisfied? |

You can store raw responses in a **PostgreSQL or BigQuery** table, then visualize it.

---

## 🎯 **Integrating NPS into OKRs**

### 🔷 Example Product OKRs using NPS:

#### **Objective:** Improve customer satisfaction and retention

| Key Result                                            | Target            |
| ----------------------------------------------------- | ----------------- |
| Increase NPS from **+38 to +50**                      | Q3 Target         |
| Reduce Detractor % from 25% to 15%                    | Q3 Target         |
| Collect >250 NPS responses this quarter               | Engagement metric |
| Implement 3 user-requested features from NPS feedback | Feature focus     |

You can also create a feedback-to-roadmap tracker:

* “X% of roadmap items in Q4 should be NPS-driven”

---

## 💡 Bonus: Tips for Acting on NPS Feedback

1. **Tag feedback themes** (e.g., performance, UI, onboarding)
2. Prioritize patterns: if 15+ detractors mention "too complex," that’s a signal.
3. Share promoter quotes with Sales/Marketing for testimonials.
4. Reach out to detractors directly to close the loop.

---



