<h1 align="center">Hi, I'm Ekeodu Arnold 👋</h1>

<p align="center">
  <b>AI Data Annotation & Quality Evaluation Specialist</b><br>
  📍 Port Harcourt, Nigeria
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=white" alt="Colab">
</p>

---

## 🧭 About Me

I help make AI systems more accurate, safe and useful. My day-to-day work is evaluating LLM responses, writing rubrics, checking facts and annotating data. I'm also growing my technical skills in Python, SQL and machine learning so I can work closer to the data itself.

I hold a B.Tech in Quantity Surveying (Second Class Upper) from the Federal University of Technology Owerri, which gave me a strong habit of precision, measurement and attention to detail. I bring that to every evaluation task.

## 💼 Experience

| Role | Where | When |
|---|---|---|
| AI Rubrics Quality Evaluator (Lighthouse project) | OneForma | Sep 2025 – Present |
| Rubrics Specialist | Outlier | Jun 2024 – Aug 2025 |
| Data Annotator | Alignerr | Feb 2023 – May 2024 |

## 🛠️ Skills

**AI Evaluation:** LLM response evaluation · rubric scoring · preference ranking · side-by-side comparison · instruction-following assessment · factual verification · safety review

**Research & Analysis:** online research · source verification · data interpretation · basic calculations · written rationales

**Quality Assurance:** error detection · consistency checks · calibration · ambiguity flagging · language, grammar and localization review

**Data Annotation:** image and video annotation · object identification · bounding boxes · audio transcription

**Technical:** Python · SQL · Pandas · Google Colab · machine learning fundamentals

**Tools:** Microsoft Excel · Google Sheets · Google Docs · Notion

## 🚀 Featured Project

### 🗓️ Theukeme Digital Booking Desk
A web-based booking desk I worked on that lets customers book services online.

🔗 **[Visit the live site](https://theukeme-digital-booking-desk.ai.studio)**

## 🐍 Code Snippet

A small example of how I think about evaluation data: scoring responses against a rubric with Pandas.

```python
import pandas as pd

# Rubric-based scoring of model responses
data = {
    "response_id": [1, 2, 3],
    "accuracy":    [5, 3, 4],
    "instruction_following": [4, 4, 5],
    "safety":      [5, 5, 5],
}
df = pd.DataFrame(data)

weights = {"accuracy": 0.5, "instruction_following": 0.3, "safety": 0.2}
df["weighted_score"] = sum(df[col] * w for col, w in weights.items())

print(df.sort_values("weighted_score", ascending=False))
```

## 🎯 Currently

- 🔍 Evaluating AI responses on the Lighthouse project
- 📚 Deepening my Python, SQL and data analysis skills
- 🌱 Exploring a specialization within data analysis

## 📫 Let's Connect

I'm open to AI evaluation, data annotation and data analysis opportunities.

<!-- OPTIONAL: GitHub stats. Replace YOUR_GITHUB_USERNAME, then remove this comment wrapper.
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&hide_border=true" height="150" alt="GitHub stats">
</p>
-->
