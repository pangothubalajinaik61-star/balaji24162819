# Israel IMF Report Analysis

This notebook analyses Israel’s 2026 IMF Article IV report using Gemini
Flash-Lite, local sentence-transformer embeddings and FAISS.

It cleans PDF text, generates section summaries, extracts economic
indicators and financial risks, answers questions using retrieved evidence,
and creates a four-panel dashboard. It also compares single-query and
multi-query retrieval.

## How to Run

1. Open the notebook in Google Colab.
2. Upload the report as `israel_2026.pdf`.
3. Add your Gemini API key to Colab Secrets as `Google_key` and enable access.
4. Run the cells in order.

Required packages are installed by the notebook. Internet access and access
to the configured Gemini model are required.

## Results

Outputs are saved in `israel_outputs`, including JSON extractions, CSV
tables, summaries, evaluation records and dashboard images. Cached responses
and embeddings reduce repeated processing.

## Notes

The 2026 report was used with lecturer approval because no suitable report
was located within the allocated 2024–2025 period.

Some quotation checks and trend validations remain unresolved. Judge scores
are automated assessments and do not establish factual accuracy.

Source: IMF Country Report No. 26/161, Israel, 2026.
