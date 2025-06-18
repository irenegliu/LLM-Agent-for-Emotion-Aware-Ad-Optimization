# LLM-Agent-for-Emotion-Aware-Ad-Optimization
This project provides a unified workflow to:
- Fetch real ad copy from the Meta Ad Library API
- Analyze emotional tone using a CMU-MOSI-trained sentiment classifier
- Suggest persona-targeted improvements using an LLM (e.g., OpenAI GPT-4)

## Recommended Development Approach

1. **Modular Notebooks (for development, debugging, and research):**
    - `notebook_1_mosi_sentiment_model.ipynb`  
      Train or load a sentiment classifier using the CMU-MOSI dataset.
    - `notebook_2_meta_ad_insights_agent.ipynb`  
      Fetch ads, run sentiment analysis, and generate targeting suggestions.

2. **Unified Notebook (for delivery or demo):**
    - Merge the above into an integrated notebook for end-to-end workflows.

---

## Notebook Structure Example

1. Import & Setup
2. Load/Train Sentiment Classifier (CMU-MOSI)
3. Query Meta Ad Library API
4. Analyze Ad Sentiment
5. Generate Persona/Targeting Suggestions (via LLM)
6. (Optional) A/B Test Suggestions
7. Conclusion + Metrics

---

## Requirements

- Python 3.9+
- `transformers`, `torch`, `pandas`, `requests`, `openai` (for GPT-based suggestions)

---
