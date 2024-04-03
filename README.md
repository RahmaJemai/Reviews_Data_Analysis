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
    <h2>Installation</h2>
    <p>To set up this project, follow these steps:</p>
    <ol>
        <li>Clone this repository to your local machine:</li>
        <pre><code>git clone https://github.com/yourusername/Reviews_Data_Analysis.git</code></pre>
        <li>Navigate to the project directory:</li>
        <pre><code>cd Reviews_Data_Analysis</code></pre>
        <li>Download the BERT model from Hugging Face:</li>
        <pre><code>transformers-cli convert --model_type bert --tf_checkpoint bert-base-uncased --config bert-base-uncased</code></pre>
    </ol>
    <h2>Usage</h2>
    <p>To run the project, execute the following command:</p>
    <pre><code>python main.py</code></pre>
    <p>This will start the data analysis process, including data preprocessing, text cleaning, and sentiment analysis.</p>
    <h2>Contributing</h2>
    <p>Contributions to this project are welcome! If you'd like to contribute, please follow these steps:</p>
    <ol>
        <li>Fork the repository on GitHub.</li>
        <li>Create a new branch from the main branch:</li>
        <pre><code>git checkout -b feature/new-feature</code></pre>
        <li>Make your changes and commit them:</li>
        <pre><code>git commit -am 'Add new feature'</code></pre>
        <li>Push your changes to your fork:</li>
        <pre><code>git push origin feature/new-feature</code></pre>
        <li>Submit a pull request on GitHub.</li>
    </ol>
    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
</body>
</html>

