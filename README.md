
# Text Summarization With Rare Words

In an era of explosive internet content, automatic text summarization has emerged as a vital solution. There is a challenge for taking care of rare and infrequently used words in text summarization. We delve into the intricate dynamics of extractive, abstractive, and hybrid approaches, harnessing transformer models and attention mechanisms to reshape text summarization. The results were compared using the well-known ROUGE metric.


## Dataset
The CNN / DailyMail Dataset is a collection of English-language news articles, encompassing more than 300,000 unique journalistic pieces from CNN and the Daily Mail. Originally designed for machine reading, comprehension, and abstractive question answering, the dataset now caters to both extractive and abstractive summarization tasks.

[CNN, Daily Mail Dataset](https://www.kaggle.com/datasets/gowrishankarp/newspaper-text-summarization-cnn-dailymail/data)

The dataset has the following columns:

- id: URL (in string)
- article: Body of the news article
- highlights: Highlight of the article as written by the author

The articles and highlights features are used as a 'source_text' and 'target_summary' respectively as a training data. The target_summary feature is used to test the model generated summarization vs the author generated summarization of the source_text.
## Results
The ROGUE scores are used to calculate the performance of the model.

Score of BART model:
![Score]([https://drive.google.com/file/d/1ziagObivHjQD6rpnIQEqNw9G0nSOHOrX/view?usp=sharing](https://drive.google.com/file/d/1ziagObivHjQD6rpnIQEqNw9G0nSOHOrX/view?usp=sharing)https://drive.google.com/file/d/1ziagObivHjQD6rpnIQEqNw9G0nSOHOrX/view?usp=sharing)


