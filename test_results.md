# Model 2 Test Results

**Date:** May 2026  
**Model:** Lyric Intelligence Analyzer

---

## Test 1: Lyric Feature Validation

### Input

**Song:** "2 Hands"  
**Artist:** Tate McRae

### Objective

Validate the Lyric Intelligence Analyzer by extracting sentiment and custom NLP features from a commercially released song.

### Features Evaluated

- Sentiment polarity
- Lexical diversity (Type-Token Ratio)
- Hook density
- Chorus detection
- Line repetition rate
- Semantic coherence
- Profanity detection

### Results

✅ Successfully generated sentiment predictions using the pretrained RoBERTa model.

✅ Correctly extracted lexical diversity and semantic coherence metrics.

✅ Detected repeated chorus structures used to calculate hook density.

✅ Successfully identified profanity indicators when present.

### Outcome

The extracted features were successfully formatted for downstream integration with:

- Model 3 – Marketing Strategy Generator
- Model 4 – Agentic AI Orchestrator

---

## Integration Status

| Component | Status |
|-----------|--------|
| Sentiment Analysis | ✅ Passed |
| Feature Extraction | ✅ Passed |
| Output Formatting | ✅ Passed |
| Team Integration | ✅ Passed |

---

## Summary

The Lyric Intelligence Analyzer successfully extracted structured NLP features from song lyrics and produced outputs compatible with the complete StreamBreaker AI pipeline. Validation using Tate McRae's **"2 Hands"** confirmed that the analyzer generated the expected lyrical features for downstream models.
