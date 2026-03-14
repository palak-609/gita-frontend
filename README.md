# Gita Wisdom — Frontend 🕉

The frontend for [Gita Wisdom](https://gita-frontend-rho.vercel.app), an AI-powered Bhagavad Gita verse recommender. Built with vanilla HTML, CSS, and JavaScript — no frameworks.

## What it does

- User types how they are feeling in natural language
- Sends the text to a fine-tuned RoBERTa emotion classifier (Flask API)
- Displays 3 relevant Bhagavad Gita verses returned by the Spring Boot backend
- Shows Sanskrit text, transliteration, and full English translation
- Quick-select emotion chips for common feelings (anger, grief, anxiety, etc.)

## Features

- 14 emotion categories supported
- Sanskrit rendering with Devanagari font
- Bhaktivedanta English translations
- Keyword fallback if ML API is unavailable
- Fully responsive design
- Smooth animations and transitions

## Tech

- HTML5 / CSS3 / Vanilla JavaScript
- Google Fonts (Cormorant Garamond, Tiro Devanagari Sanskrit)
- Deployed on Vercel

## Live Demo

[gita-frontend-rho.vercel.app](https://gita-frontend-rho.vercel.app)

## Part of

| Component | Link |
|---|---|
| Frontend (this) | [gita-frontend-rho.vercel.app](https://gita-frontend-rho.vercel.app) |
| Emotion Model | [HuggingFace Space](https://huggingface.co/spaces/palakhf/gita-nlp) |
| Backend API | [gita-backend](https://github.com/palak-609/gita-backend) |
