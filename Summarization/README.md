# Summarization

In this folder, we implemented both **abstractive** and **extractive** summarization techniques. We then compared the various methods using the **Rouge** metric to determine which was most effective.

## Extractive summarization

Time of summarization for different extractive methods (using sumy: LextRank, Lsa, Luhn, TextRank), displayed in bar chart

Comparing the length of summaries for different extractive methods, displayed in a bar chart

The Rouge measure was used to compare all extractive methods summaries to Chatgpt summaries. Statistical analysis was represented by box plots for all methods, and a histogram was created to present the distribution of the most effective method, which was **TextRank**.  

 ## Abstractive summarization

For abstractive summarization, we used **T5**, **BERT**, **GPT**, **GPT2** and **DISTILBERT**. Then We calculated time of summarization and length of each summary to compare different methods.
The most effective method in abstractive summarization was **DistilBERT**.
