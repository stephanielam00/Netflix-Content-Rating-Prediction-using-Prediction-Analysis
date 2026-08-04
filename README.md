# StreamBreaker AI — Lyric Intelligence Analyzer

> Model 2 of the StreamBreaker AI Capstone Pipeline  
> MS Business Analytics, California State University, East Bay · May 2026

---

## What It Does

StreamBreaker AI is a multimodal artificial intelligence pipeline designed to help independent artists evaluate the commercial potential of music before investing in promotion.

This repository contains **Model 2: the Lyric Intelligence Analyzer**.

The module analyzes song lyrics using a pre-trained RoBERTa sentiment model and custom natural language processing features. It converts unstructured lyrics into structured indicators that can be used by the larger StreamBreaker AI prediction and marketing pipeline.

---

## Features

The analyzer extracts the following lyrical characteristics:

- **Sentiment polarity** — identifies positive, negative, or neutral emotional tone using a pretrained RoBERTa model
- **Hook density** — measures repeated phrases and lyrical structures associated with memorability
- **Lexical diversity** — calculates vocabulary variety using the ratio of unique words to total words
- **Semantic coherence** — measures thematic consistency across lyrical sections
- **Profanity detection** — identifies explicit language that may affect playlist eligibility

---

## How It Works

```text
Song Lyrics
     ↓
Text Cleaning and Preprocessing
     ↓
RoBERTa Sentiment Classification
     ↓
Custom NLP Feature Extraction
     ↓
Structured Lyric Analysis Results
     ↓
StreamBreaker AI Marketing Strategy Generator
