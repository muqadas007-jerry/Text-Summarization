# Text-Summarization
📌 Text Summarization Project
A system that generates concise summaries from long news articles, blogs, or reports.

Uses both extractive and abstractive summarization techniques.

Based on the CNN/DailyMail dataset.

🧩 Project Steps
Load and explore the dataset (test.csv) containing news articles.

Preprocess the textual data using basic cleaning and tokenization.

Apply extractive summarization using the spaCy library to extract key sentences.

Apply abstractive summarization using a pre-trained model (facebook/bart-large-cnn) from HuggingFace Transformers.

Generate summaries for each article using both methods.

Evaluate and compare results for coherence and quality.

Save final outputs to a CSV file (summarized_output.csv).

🛠️ Technologies Used
Python

pandas

spaCy

HuggingFace Transformers

BART model (facebook/bart-large-cnn)

PyTorch
