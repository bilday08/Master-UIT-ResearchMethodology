# Research-Methodology – SCL-Emotion

This repository presents a **complete set of research methodology materials** for a **hypothetical master’s thesis proposal** developed as part of the *CS2205 – Research Methodology* course.

## 📘 Project Overview

**SCL-EMOTION** is a proposed system for **fine-grained multi-label emotion classification on Vietnamese social media text**.  
The project explores a **supervised contrastive learning approach** that integrates **representation learning with Jaccard-similarity soft-weighting** to generate robust, clean, and distinct semantic boundaries between fine-grained, high-similarity emotions.

Key ideas include:
- Multi-label classification for 28 fine-grained emotion categories
- Jaccard-weighted Supervised Contrastive Learning (JSCL) vs. strict SCL
- Implicit two-view contrastive pair generation via encoder dropout
- Pre-trained language backbone optimized using **ViSoBERT** for social media text
- Comprehensive evaluation using the benchmark **ViGoEmotions** dataset (~20,664 comments)

> ⚠️ All materials in this repository are **hypothetical/sample academic content** and **do not represent an official or approved master’s thesis**.

## 📌 Repository Contents

1. **Master’s Thesis Proposal (PDF)**  
   - Research background, motivation, and the three challenges (Noise & Brevity, Multi-label Overlap, High Inter-class Similarity)
   - Research objectives (Framework construction, Contrastive variants comparison, Latent space & error analysis)
   - Methodology and joint training pipeline (`L_Joint = (1 - α)·L_BCE + α·L_Con`)
   - Expected outcomes, quantitative evaluations, and future work

2. **Research Poster (PDF)**  
   - Visual summary of the proposed framework and training objectives
   - Problem statement, methodology (BCE + JSCL/SCL), and experimental findings

3. **Proposal Presentation Slides (PDF)**  
   - Slides used for the proposal defense presentation
   - Covers research background, goals, methodology, and evaluation plan

4. **YouTube Link – Proposal Presentation Video**  
   - Public link to the presentation video hosted on YouTube: https://youtu.be/h1qyvZUXWiM?si=jUmGHDJObYlxsfQq
