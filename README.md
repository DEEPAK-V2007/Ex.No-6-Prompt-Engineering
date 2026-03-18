Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

Developed by: Deepak.V
Register No: 212225230044

Aim: 

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.

Procedure:

Develop a python code that integrates multiple AI tool by interacting with their APIs.
Compare outputs from different APIs.
Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights.

Program:

Positive Statement:
```
from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = "Challenges help me grow stronger."

print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)

# Insight generation
if sentiment['compound'] > 0:
    print("\nInsight: The review is positive and suitable for marketing promotion.")
else:
    print("\nInsight: The review tone is neutral or negative.")
```
Output:

<img width="750" height="233" alt="{84D2F604-772E-4E1C-B8A6-A2F60D4CFBAE}" src="https://github.com/user-attachments/assets/02cb4514-bfcb-4c30-8e70-da859355516f" />


Negative Statement:
```
from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = "Poor quality products wear out quickly."

print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)

# Insight generation
if sentiment['compound'] > 0:
    print("\nInsight: The review is positive and suitable for marketing promotion.")
else:
    print("\nInsight: The review tone is neutral or negative.")
```
Output:

<img width="799" height="231" alt="{94FC212A-E6F0-46B2-9A44-FA9B33673027}" src="https://github.com/user-attachments/assets/d8c5fa40-6730-4062-a6fa-aea2559dd8f4" />

Result: Thus the Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools is successfully implemented.
