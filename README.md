

# AI Feedback Analyzer

An end-to-end sentiment and topic analysis system built with Hugging Face Transformers and Scikit-learn.

## Features
- Analyzes sentiment of customer feedback (positive/negative percentages)
- Extracts discussion topics using K-Means clustering
- Works with CSV or text files
- Outputs structured JSON summaries

## How to Run
1. Upload your feedback file (CSV or TXT) to Colab.
2. Run the notebook.
3. View sentiment results and top discussion topics.

## Example Output
```json
{
  "sentiment_distribution": {"POSITIVE": 63.33, "NEGATIVE": 36.67},
  "summary": "Feedback analyzed: 30 items. Positive: 63.33%, Negative: 36.67%.",
  "topics": ["price, expensive, plan", "design, clean, interface", "crash, bug, update"]
}
