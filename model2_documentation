# Model 2: Lyric Intelligence Analyzer

## Overview
Model 2 analyzes song lyrics using natural language processing (NLP) to extract features that help evaluate a song's commercial potential before release.

## Technologies
- Python
- Hugging Face Transformers
- RoBERTa
- PyTorch
- Datasets
- Evaluate

## Features Extracted
- Sentiment polarity (positive, negative, neutral)
- Hook density
- Lexical diversity (Type-Token Ratio)
- Semantic coherence
- Chorus detection
- Line repetition rate
- Profanity detection

## Workflow
1. Retrieve song lyrics.
2. Tokenize the lyrics using a Hugging Face tokenizer.
3. Run the pretrained RoBERTa sentiment classifier.
4. Extract custom NLP features.
5. Output structured metrics for downstream models.

## Example Output
- Song: Folded
- Artist: Kehlani
- Sentiment: 98.65% Negative
- Lexical Diversity (TTR): 0.2874
- Chorus Present: Yes
- Chorus Repetition Rate: 88.9%
- Profanity Count: 0
- Semantic Coherence: 0.2798

## Role in StreamBreaker AI
The extracted lyric features are passed to the StreamBreaker AI pipeline to support the marketing strategy generator and overall decision-making.
