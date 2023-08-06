# Text-Summarizer 📝📚

**Text-Summarizer** is a powerful tool that leverages PyTorch and Transformer models to automatically generate concise and informative summaries from text. Whether you're dealing with lengthy articles, research papers, or any other form of written content, our tool will help you extract the essence and main points in a fraction of the time.

## 🚀 Features

### Transformer Pipeline 🤖🔗

We've harnessed the capabilities of the T5Tokenizer Transformer in PyTorch to create a robust summarization pipeline. Here's how it works:

1. Input sequences and their corresponding target sequences are used for training (Supervised Learning).
2. The input sequence is encoded, and the encoded hidden states are passed through cross-attention layers to the decoder.
3. The decoder generates the summary output in an auto-regressive manner.
4. The generated summaries are stored in a .tsv file for easy access.

**Precision Score:** 0.961  
**Recall Score:** 0.125

### NLTK Summarization 📊📃

Our NLTK-based summarization process involves these steps:

1. Data clean-up, including the removal of special characters, stop words, and punctuation.
2. Creation of word tokens and sentence tokens using the Natural Language Tool Kit library.
3. Evaluation of word frequency and subsequent calculation of weighted frequency for each sentence.
4. Generation of a summary by selecting the top 30% of sentences based on their weighted importance.

**Precision Score:** 0.666  
**Recall Score:** 0.356

## 📋 How to Use

1. Clone the repository.
2. Install the necessary dependencies.
3. Run the Text-Summarizer script on your desired input text.

## 💡 Credits

This project was brought to you by the collaborative efforts of:

- Sainik Khaddar
- Saptarshi Pani
- Arindam Saha

## 📞 Contact

For inquiries or feedback, please reach out to us:

Email: sainikwarror132@gmail.com

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---
