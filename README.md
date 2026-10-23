# 0. AI: Scaffolding a Robust API Integration

## Overview
This task demonstrates integrating AI into a software development workflow using Contextual Prompting to add secure credential management and enhanced exception handling.

## Files Included
- `initial_sentiment_analyzer.py`: The baseline legacy sentiment analysis script.
- `sentiment_analyzer.py`: The refactored version with environment variable authorization (`TEXT_PROCESSING_API_KEY`) and granular exception management (`Timeout`, `ConnectionError`).

## Usage
```bash
chmod +x sentiment_analyzer.py
export TEXT_PROCESSING_API_KEY="DUMMY_KEY"
./sentiment_analyzer.py "This software engineering assignment was very insightful!"
