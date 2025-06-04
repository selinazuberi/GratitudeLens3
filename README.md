# Gratitude Lens

Final project for the Building AI course at the University of Helsinki

## Summary

Gratitude Lens is an AI-powered journaling app that guides users to reflect daily on five positive things they experienced and five good things they did for others. Using NLP, emotion detection, and personalized prompts, the app cultivates well-being through structured gratitude.

## Background

Modern life can feel fast-paced, isolating, and overwhelming. Many people struggle with anxiety, depression, or burnout — and research consistently shows that practicing gratitude increases happiness, resilience, and life satisfaction.

Studies from Harvard Medical School, the Greater Good Science Center, and researchers like Emmons & McCullough (2003) show that people who journal gratitude regularly experience better mood, improved sleep, and stronger relationships. Wood et al. (2010) found gratitude correlates with lower stress and depression, while Wong et al. (2016) found gratitude enhances emotional regulation in therapy. Neuroscience studies also show gratitude activates dopamine-related brain regions, changing how we process experiences.

Yet, people often forget or lack motivation to reflect meaningfully each day. Gratitude Lens addresses this gap by:
* Guiding users to journal five helpful things they did and five good things they experienced every day
* Offering AI-powered emotional insights and encouragement
* Reinforcing positive patterns over time

### Personal Motivation

You can either see the glass as half empty or half full — this perspective shapes how we experience life. I completed my bachelor's degree in Psychology and have a deep interest in the intersection of technology and wellness, both physical and psychological. Gratitude Lens is inspired by this intersection — combining evidence-based psychology with AI to support emotional resilience and daily mindfulness.

## How is it used?

Each day, users write or speak journal entries. The AI analyzes the text for emotional tone and themes, tracks mood trends over time, and recommends prompts based on reflection history.

**Main use case:**
- 5 things users are grateful for
- 5 actions users did to help others

**Additional uses:**
- Mental health check-ins
- Journaling support in therapy or coaching
- Wellness and mood-tracking tools

## Data sources and AI methods

**Data Sources**
- User-generated text data (journal entries)
- Optional future inputs: audio, emojis

**AI Techniques Used**
1. Natural Language Processing (NLP) — structuring and tagging text
2. Sentiment & Emotion Detection (e.g., using BERT/DistilRoBERTa)
3. Topic Modeling (LDA) — surfacing common gratitude themes
4. Conversational AI — reflection support and encouragement
5. Time Series Analysis — emotion tracking over time
6. Anomaly Detection — spotting mood shifts or crises
7. Personalized Prompt Generation — suggesting prompts based on journaling habits
8. Multimodal Input (future) — integrating voice and image sentiment

## Challenges

- Does not replace clinical therapy or mental health care
- May misread sarcasm or cultural nuance
- Self-reporting introduces bias and incomplete data

**Ethical considerations:**
- Privacy and user data protection
- Avoiding toxic positivity
- Supporting empathy, not replacing it

## What next?

Future development ideas:
- Add voice tone detection and speech-based journaling
- Create community features like gratitude walls
- Partner with therapists and health coaches
- Expand into other languages using multilingual AI models

Support needed:
- ML engineers for backend model development
- UX designers for mobile interface
- Mental health consultants for safe content design

## Acknowledgments

* Research: Greater Good Science Center, Harvard Medical School
* Emotion detection model: [j-hartmann/emotion-english-distilroberta-base](https://huggingface.co/j-hartmann/emotion-english-distilroberta-base)
* Prompt framework: Inspired by CBT and Positive Psychology
* [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
