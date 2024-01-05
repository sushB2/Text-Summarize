# Text-Summarize
Automatic Text Summarization Using TextRank Method

In natural language processing, this work compares and contrasts the TextRank approach with the article custom summary algorithm. Whereas the proprietary method uses preprocessing methods including stopword removal, contraction expansion, and HTML cleaning, the TextRank approach uses graph theory to identify important terms. Sentence scoring and word frequency normalization are novel methods used to identify essential sentences; the top 20% of sentences are selected for summary construction. Different algorithms produce different length summaries: TextRank and a bespoke summary function (article_summarize). The findings are compared using a bar chart that is created and made publicly. Based on the assumption that the dataset contains ten articles, the number of characters that each strategy's summary should have is computed. 

The length of each article's summary appears on the final graph with the highest TextRank. Based on the BLEU score of 0.0617, it can be seen that TextRank performs better than the customizable Article_summarize summary.
