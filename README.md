# Fetch Insights

This Jupyter notebook demonstrates a comprehensive analysis of interviewee feedback on an app, including sentiment analysis, information extraction, and text summarization. The notebook is structured to extract and analyze feedback from a transcript of an interview, providing insights into user satisfaction, areas for improvement, and suggestions for enhancing the app's features.

## Overview

- **Extracting Interviewee Feedback**: The notebook begins by extracting the interviewee's feedback from a given transcript using regular expressions. This step isolates the interviewee's statements for further analysis.
- **Sentiment Analysis**: Utilizing the NLTK library and the SentimentIntensityAnalyzer, the notebook performs sentiment analysis on the extracted feedback. This analysis helps in understanding the overall sentiment of the feedback, whether it's positive, negative, or neutral.
- **Information Extraction**: Employing the SpaCy library, the notebook extracts entities and noun phrases from the feedback. This step aids in identifying key topics and features mentioned by the interviewee.
- **Text Summarization**: Finally, the notebook uses the Hugging Face Transformers library to generate a summary of the interviewee's feedback. This summary condenses the feedback into a concise overview, highlighting the main points.

## Dependencies

- **Python**: Ensure you have Python 3.6 or newer installed.
- **NLTK**: Natural Language Toolkit for Python, used for tokenization and sentiment analysis.
- **SpaCy**: A library for advanced Natural Language Processing in Python, used for information extraction.
- **Transformers**: A state-of-the-art library for Natural Language Processing, used for text summarization.
- **Pandas**: A powerful data manipulation library, used for handling data in a tabular format.

## Installation

Before running the notebook, ensure you have installed the necessary libraries. You can install them using pip:

```bash
pip install nltk spacy transformers pandas
```

Additionally, download the necessary SpaCy model:

```
!python -m spacy download en_core_web_sm
```

## Running the Notebook

1. Open the Jupyter notebook in your preferred environment.
2. Ensure all dependencies are installed as mentioned above.
3. Run the cells in order to execute the analysis.

## Output

The notebook will output:

- **Sentiment Analysis Results**: A breakdown of the sentiment scores for each statement in the interviewee's feedback.
- **Information Extraction Results**: A list of entities and noun phrases identified in the feedback.
- **Generated Summary**: A concise summary of the interviewee's feedback, highlighting the main points.

## Conclusion

This notebook provides a practical example of how to analyze interviewee feedback using Python. It demonstrates the power of NLP libraries in extracting insights from text data, which can be invaluable for improving products and services based on user feedback.