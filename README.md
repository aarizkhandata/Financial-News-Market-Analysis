# Financial-News-Market-Analysis
 A data analytics project exploring the correlation between financial news topics and market volatility.

### **Financial News & Market Volatility Analysis**

This project uses data analytics to explore the relationship between financial news headlines and fluctuations in the S&P 500 stock index. It demonstrates how themes in news media can serve as a potential indicator of market behavior.

***

### **Overview & Methodology**

The analysis uses the **S&P 500 with Financial News Headlines (2008–2024)** dataset. The news headlines were preprocessed using standard NLP techniques. We then applied a **Latent Dirichlet Allocation (LDA)** topic model to automatically identify key themes, such as "Market Volatility," "Economic Policy," and "Market Performance."

Finally, we performed a time-series analysis to plot the daily prevalence of these topics and correlated their trends with the S&P 500's closing price.

***

### **Key Findings**

The project reveals a strong **inverse correlation** between the proportion of news about market volatility and the S&P 500's price. When headlines about market warnings and fear increased, the S&P 500 price tended to fall. This suggests that the sentiment and themes within financial news can be a valuable indicator of market behavior.

***

### **Technologies & Libraries**

* Python
* Pandas
* Gensim (for LDA)
* Spacy
* Matplotlib (for visualizations)
* Google Colab
