# Homework-9-NLP-Analyzing-a-Distribution-of-Acceptable-Gold-Std-Text-NLU
# 📝 Homework 9: Analyzing Gold Standard vs. Pedestrian Poetry Using NLP

## 📚 Overview

This project explores the linguistic and thematic characteristics that distinguish **Pushcart-nominated poems (Gold Standard)** from **non-nominated poems (Pedestrian)** using Natural Language Understanding (NLU) techniques. We apply POS tagging, topic modeling, sentiment analysis, and generative AI to identify and quantify what makes a poem nomination-worthy.

---

## 🔗 Run the Full Analysis in Google Colab

👉 [Open in Google Colab](https://colab.research.google.com/drive/1Ua7wQCrOkSu3pOi-lyPhKBx7v_UfMwYC?usp=sharing)  
_All steps from data scraping to final evaluation are included in this single notebook._

---

## 🗂 Dataset

**Pushcart-Nominated Poems (2022):**
- [Iowa Poetry](https://iowapoetry.com/pushcart2022.htm)
- [Rattle](https://www.rattle.com/info/news)
- [La Sierra University](https://roadrunner.lasierra.edu/nominations-for-the-2022-pushcart-prize/)
- [Prolific Pulse](https://prolificpulse.blog/2022/10/18/pushcart-nominations-2022)
- [Pulp Literature](https://pulpliterature.com/announcing-pulp-literatures-2022-pushcart-prize-nominees/)

**Non-Nominated Poems:**  
Scraped from similar poetry sources and blogs, limited to 2022 to ensure fairness in temporal comparison.

---

## 🧠 Methodology

### ✅ Step 1: POS Distribution Analysis
- POS tagging with `spaCy`
- Normalized noun, verb, adjective, and adverb counts
- Visualized gold vs. pedestrian distributions

### ✅ Step 2: Topic Modeling
- Used `Gensim`'s LDA model
- Identified dominant themes and compared distributions

### ✅ Step 3: Sentiment Analysis
- Analyzed emotional tone using `TextBlob` and `VADER`
- Compared polarity and subjectivity metrics

### ✅ Step 4: Delta Analysis
- Highlighted differences across POS, topic, and sentiment dimensions

### ✅ Step 5: Gemini API + Narrative Comparison
- Queried Gemini API with Pushcart vs. pedestrian poems
- Captured insights on what may disqualify poems

### ✅ Step 6: Fractal Chain-of-Thought Prompting
- Engineered prompts combining:
  - Statistical data
  - Topic & sentiment features
  - Generative comparison outputs
- Ranked pedestrian poems on their Pushcart-worthiness (0–100%)

---

## 🧰 Tools & Libraries

- `spaCy`, `NLTK` – POS tagging
- `Gensim` – Topic modeling
- `matplotlib`, `seaborn` – Visualization
- `TextBlob`, `VADER` – Sentiment scoring
- `Gemini API` – AI inference
- `OpenAI GPT-4` – Prompt design (Fractal-CoT)

---

## 📊 Output Highlights

- 📈 POS distributions between groups
- 🧵 Dominant topics and semantic overlap
- ❤️ Sentiment contrasts across poems
- 🤖 Narrative from AI on why poems fail to qualify
- 📑 Ranked list of pedestrian poems with nomination likelihood

---

## 📁 Folder Structure

