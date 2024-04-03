<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Reviews Data Analysis</h1>
    <h2>Overview</h2>
    <p>This project aims to analyze customer reviews collected from the Capterra website for businesses using NetSuite as their Enterprise Resource Planning (ERP) software. The project involves preprocessing the data to handle missing values, followed by text cleaning using NLTK (Natural Language Toolkit) for tasks such as removing punctuation and special characters, tokenization, and lemmatization. Finally, sentiment analysis will be performed using BERT (Bidirectional Encoder Representations from Transformers) and TensorFlow to assign scores (0, 1, or -1) to each review.</p>
    <h2>Project Steps</h2>
<ul>
    <li><strong>Data Collection:</strong> This step involves using the <a href="https://pandas.pydata.org/">pandas</a> library to load data from the Capterra website. The collected data consists of customer reviews for businesses using NetSuite as their ERP software.</li>
    <li><strong>Data Preprocessing:</strong> Before analyzing the reviews, it's essential to clean and preprocess the textual data. This is accomplished using the <a href="https://www.nltk.org/">NLTK (Natural Language Toolkit)</a> library for tasks such as punctuation removal, special character removal, tokenization, and lemmatization.</li>
    <li><strong>Textual Analysis:</strong> Once the data is preprocessed, textual analyses such as tokenization and lemmatization are performed using NLTK. This transforms the raw text into a more structured representation suitable for analysis.</li>
    <li><strong>Sentiment Classification:</strong> Finally, sentiment analysis is conducted using <a href="https://huggingface.co/transformers/">Transformers</a> with TensorFlow. The BERT model is employed to assign sentiment scores (positive, negative, or neutral) to each customer review, enabling the assessment of sentiments expressed in the comments.</li>
</ul>

<h2>Installation</h2>
<p>The required libraries to run this project are:</p>
<ul>
    <li><a href="https://pandas.pydata.org/">pandas</a></li>
    <li><a href="https://www.nltk.org/">NLTK</a></li>
    <li><a href="https://huggingface.co/transformers/">Transformers</a></li>
    <li><a href="https://www.tensorflow.org/">TensorFlow</a></li>
</ul>
<p>You can install them using the following command:</p>
<pre><code>pip install pandas nltk transformers tensorflow</code></pre>
</body>
</html>

