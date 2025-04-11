Datasets and benchmark:
https://www.kaggle.com/datasets/eaglewhl/finsen-financial-sentiment-dataset?select=FinSen_US_Categorized_Timestamp.csv
https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-for-financial-news
https://huggingface.co/datasets/TheFinAI/fiqa-sentiment-classification/viewer/default/test

Repo of Gemma3:
https://github.com/google-deepmind/gemma

Prompt Example:
"Please analyze the following financial headline and output its sentiment analysis result.\n"
"Your answer must include:\n"
"1. Sentiment Label: one of [Positive, Neutral, Negative].\n"
"2. Sentiment Score: a number between -1 and 1 (where 1 is extremely positive, -1 is extremely negative, and 0 is neutral).\n"
"Format your response exactly as follows:\n"
"Sentiment Label: <label>\n"
"Sentiment Score: <score>\n"
"Headline: " + headline
