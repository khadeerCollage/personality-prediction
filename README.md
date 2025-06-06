# Encoder-Only Transformer: Personality Prediction and NLP Tasks

This repository demonstrates the use of encoder-only transformer models, such as BERT, for various natural language processing (NLP) tasks. It includes implementations for personality prediction, sentence embeddings, text similarity, named entity recognition (NER), and sentiment analysis.

## Project Structure

- **Ocean_prediction.ipynb**: A milestone project for predicting personality traits using the OCEAN model (Openness, Conscientiousness, Extraversion, Agreeableness, Neuroticism) based on survey data.
- **task_1_on_sentiment_analysis_BERT_Encoder_only.ipynb**: Sentiment analysis using BERT.
- **task_2_on_NER_BERT_Encoder_only.ipynb**: Named entity recognition using BERT.
- **task_3_on_text_similarity_BERT_Encoder_only.ipynb**: Text similarity computation using Sentence-BERT.
- **task_4_on_sentence_embeddings_BERT_Encoder_only.ipynb**: Generating sentence embeddings using BERT.

## Dataset

The dataset used for the **Ocean_prediction** project is sourced from the [Big Five Personality Test Dataset](https://openpsychometrics.org/_rawdata/). It contains responses to personality-related questions, which are processed to predict the OCEAN traits.

## Key Features

1. **Personality Prediction**:
   - Preprocessing of survey data.
   - Feature engineering to create a text column from personality traits.
   - Training a BERT model for multi-label classification.

2. **Sentiment Analysis**:
   - Binary classification of text into positive or negative sentiment.
   - Fine-tuning BERT for sequence classification.

3. **Named Entity Recognition (NER)**:
   - Identifying entities like names, places, and dates in text.
   - Using Hugging Face's NER pipeline.

4. **Text Similarity**:
   - Computing semantic similarity between sentences.
   - Leveraging Sentence-BERT for embeddings and cosine similarity.

5. **Sentence Embeddings**:
   - Generating dense vector representations of sentences.
   - Using pre-trained Sentence-BERT models.

## Installation

To run the notebooks, install the required libraries:

```bash
pip install transformers datasets scikit-learn sentence-transformers matplotlib seaborn nltk
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/encoder-only-transformer.git
   cd encoder-only-transformer
   ```

2. Download the dataset for the **Ocean_prediction** project and place it in the root directory.

3. Open the notebooks in your preferred environment (e.g., Jupyter Notebook, VS Code) and execute the cells.

## Results

- **Ocean_prediction**: Predicts personality traits with high accuracy using BERT.
- **Sentiment Analysis**: Classifies text sentiment effectively.
- **NER**: Extracts named entities from text.
- **Text Similarity**: Computes similarity scores between sentences.
- **Sentence Embeddings**: Generates meaningful embeddings for downstream tasks.

## Milestone: Ocean Prediction

The **Ocean_prediction** project is the highlight of this repository. It showcases the power of encoder-only transformers in predicting personality traits from textual data. The dataset is preprocessed, cleaned, and used to train a BERT model for multi-label classification.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Sentence-Transformers](https://www.sbert.net/)
- [Big Five Personality Test Dataset](https://openpsychometrics.org/_rawdata/)

## References

- [Hugging Face Transformers Documentation](https://huggingface.co/docs/transformers/)
- [Sentence-Transformers Documentation](https://www.sbert.net/)
- [Big Five Personality Test Dataset](https://openpsychometrics.org/_rawdata/)
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)
- [PyTorch Documentation](https://pytorch.org/docs/)
