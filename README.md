# 🎓 GrammaScore

**GrammaScore** is a machine learning-based Grammar Scoring Engine designed to evaluate the grammatical quality of spoken audio clips. It predicts a continuous score between **0 and 5** using MOS (Mean Opinion Score) Likert-scale ratings.

---

## 📝 Overview

In this project, we build a regression model that listens to audio samples (45–60 seconds each) and predicts a grammar quality score. This can be applied to spoken language assessment, pronunciation tools, or AI-based interview evaluators.

### 📊 Task
- Input: `.wav` audio file
- Output: Grammar MOS Score ∈ [0.0, 5.0]

---

## 📁 Dataset

- **Training samples**: 444 labeled audio clips
- **Test samples**: 195 unlabeled audio clips

Each clip is annotated with a grammar proficiency score based on a Likert-scale MOS rubric.

---

## 🔧 Project Structure

