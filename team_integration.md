# Team Integration Guide – Model 2 (Lyric Intelligence Analyzer)

## Overview

Model 2 is responsible for extracting meaningful lyrical features using Natural Language Processing (NLP). These features are integrated with the outputs of Models 1, 3, and 4 to support the complete StreamBreaker AI workflow.

---

# Project Pipeline

Model 0 → Audio Feature Extractor  
↓  
Model 1 → Stream Threshold Predictor  
↓  
**Model 2 → Lyric Intelligence Analyzer (Stephanie Lam)**  
↓  
Model 3 → Marketing Strategy Generator  
↓  
Model 4 → Agentic AI Orchestrator

---

## Integration with Model 1

Model 1 predicts whether a song is likely to exceed Spotify's monetization threshold using audio features.

Model 1 provides:

- Stream prediction probability
- Prediction confidence
- Audio-based prediction metrics

The outputs from Model 1 are combined with the lyrical features extracted by Model 2 before being passed to Model 3.

---

## Model 2 Output

The Lyric Intelligence Analyzer extracts:

- Sentiment polarity
- Lexical diversity (Type-Token Ratio)
- Hook density
- Chorus detection
- Line repetition rate
- Semantic coherence
- Profanity detection

Example output:

```json
{
  "sent_pos": 0.0135,
  "sent_neg": 0.9865,
  "sent_neu": 0.0000,
  "ttr": 0.2874,
  "chorus_present": true,
  "chorus_line_repetition_rate": 0.8889,
  "overall_line_repetition_rate": 0.6400,
  "profanity_count": 0,
  "coherence_mean": 0.2798
}
```

---

## Integration with Model 3

Model 3 uses the outputs from Model 2 to generate personalized marketing strategies.

Examples include:

- Interpreting lyrical sentiment
- Identifying memorable hooks
- Supporting audience targeting
- Improving marketing recommendations

---

## Integration with Model 4

Model 4 combines the outputs from Models 1–3 into a single StreamBreaker AI Streamlit application.

User inputs include:

- Song lyrics
- Song title
- Artist name (optional)
- Genre
- Marketing budget

---

## Team Members

| Model | Team Member | Responsibility |
|--------|-------------|----------------|
| Model 0 | Shared | Audio Feature Extraction |
| Model 1 | Harsh Verma | Stream Threshold Predictor |
| **Model 2** | **Stephanie Lam** | Lyric Intelligence Analyzer |
| Model 3 | Miguel Davila | Marketing Strategy Generator |
| Model 4 | Gopi Krishna Reddy Katkuri | Agentic AI Orchestrator |

---

## Live Demo

The complete StreamBreaker AI application is available at:

https://streambreaker-ai.streamlit.app/
