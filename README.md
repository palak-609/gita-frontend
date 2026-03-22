# Gita Wisdom — Frontend 🕉

The frontend for [Gita Wisdom](https://gita-frontend-rho.vercel.app), an AI-powered Bhagavad Gita verse recommender. Built with vanilla HTML, CSS, and JavaScript — no frameworks.

## Live Demo
**[gita-frontend-rho.vercel.app](https://gita-frontend-rho.vercel.app)**

## What it does

- User types how they are feeling in natural language
- Sends the text to a fine-tuned RoBERTa emotion classifier (Flask API)
- Displays 3 relevant Bhagavad Gita verses returned by the Spring Boot backend
- Shows Sanskrit text, transliteration, Bhaktivedanta English translation, and full purport
- Quick-select emotion chips for 14 common emotions (anger, grief, anxiety, etc.)
- Breathing exercise (4-2-6 pattern) to reflect after reading the verses

## Features

- 14 emotion categories supported
- Sanskrit rendering with Devanagari font
- Bhaktivedanta English translations + purport (commentary)
- Collapsible purport section per verse
- Guided breathing exercise modal after verses load
- Keyword fallback if ML API is unavailable
- Fully responsive design
- Smooth animations and transitions

## Tech

- HTML5 / CSS3 / Vanilla JavaScript
- Google Fonts (Cormorant Garamond, Tiro Devanagari Sanskrit, IM Fell English SC)
- Deployed on Vercel

## Part of

| Component | Link |
|---|---|
| Frontend (this) | [gita-frontend-rho.vercel.app](https://gita-frontend-rho.vercel.app) |
| Emotion Model | [HuggingFace Space](https://huggingface.co/spaces/palakhf/gita-nlp) |
| Backend API | [gita-backend](https://github.com/palak-609/gita-backend) |
