---
layout: default
title: Study Overview
---
<nav style="margin-bottom: 1rem; font-size: 0.95rem;">
  <a href="{{ '/' | relative_url }}">Home</a> ·
  <a href="{{ '/study' | relative_url }}">Study Overview</a> ·
  <a href="{{ '/participation' | relative_url }}">Participate</a> ·
  <a href="{{ '/internships' | relative_url }}">Internships</a> ·
  <a href="{{ '/team' | relative_url }}">Team</a> ·
  <a href="{{ '/publications' | relative_url }}">Publications</a>
</nav>

# Study Overview

## Goals

This project explores:

1. What LLMs such as ChatGPT **already know or infer** about their users.
2. How users **perceive** these inferences (correctness, surprise, comfort, privacy).
3. How LLMs behave as **brainstorming partners** – do they create new ideas or echo users?

## Study Stages

1. **Stage I – Onboarding and One-Shot Test**  
   - Participants answer a short survey about AI usage and background.  
   - They run a single, fixed prompt asking the AI to list:
     - 10 facts,
     - 10 guesses,
     - 10 personal characteristics.  
   - They rate each category on **Correctness (0–10)** and **Surprise (0–10)**.

2. **Stage II – Sensitive Attribute Inference**  
   - The AI is asked to guess age, background, religion (if any), whether the participant has children, and approximate income.  
   - Participants rate **Correctness**, **Surprise**, and **Comfort** for each item.  
   - We do **not** collect any of the AI’s text, only these ratings.

3. **Stage III – Memory Seeding (Short and Long Memory)**  
   - Synthetic, harmless “micro-facts” are injected across several chat sessions over days or weeks.  
   - Later, a final probe checks whether the AI recalls or combines these seeds.  
   - We study recall rate, integration accuracy, and how memory decays over time.

4. **Stage IV – Brainstorming and Echo Effect**  
   - Participants brainstorm with the AI on:
     - a general topic (e.g., global economy), and
     - a personal topic (e.g., budgeting or academic planning).  
   - They rate idea **Diversity**, **Novelty**, **Agreement**, and **Echo feeling**.  
   - This helps us see when AI brainstorming is collaborative vs. echoic.

## Cross-Cultural Design

The study is conducted at multiple sites (e.g., Canada, Egypt), with similar participant profiles.  
This allows us to compare how different communities experience AI memory, privacy, and collaboration.

---

## Documentation

You can link project documents (e.g., PDF protocols, consent forms) here once added to the `docs/` folder.
