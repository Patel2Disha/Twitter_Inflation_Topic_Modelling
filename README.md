# Twitter_Inflation_Topic_Modelling

Summary:
  For this personal project, I aimed to analyze people's views regarding inflation in different areas such as food prices, government policies, and fuel costs. Inflation has remained a hot topic since the onset of the COVID-19 pandemic. To perform this analysis, I utilized Databricks and Apache Spark, along with additional libraries such as Gensim and PyLDAvis for topic modeling.

The project workflow included data retrieval from Twitter using AWS S3, data preprocessing, and topic modeling using Latent Dirichlet Allocation (LDA) with Spark. The primary challenge encountered was the computing time required for Spark LDA due to the large dataset.

Major Challenges:

- Extensive computing time with Spark LDA due to dataset size.
- Addressed by optimizing Spark LDA, fine-tuning parameters, and considering more powerful compute resources.

Key Insights:
- Valuable for Businesses:
  - Understanding public sentiment on inflation in key areas (food, government policies, fuel).
  - Informs pricing strategies, inventory management, and marketing decisions.
- Valuable for Governments:
  - Insights into public perceptions of policies related to inflation.
  - Identifying areas for policy improvement.
- Economic Stability:
  - Monitoring and addressing inflation concerns fosters economic stability.
- Public Trust:
  - Addressing inflation concerns enhances public trust in government actions.

Conclusion:
  In conclusion, this personal project successfully employed Databricks and Spark for data processing, topic modeling using LDA, and Gensim and PyLDAvis for visualization. Despite the computational challenges, the insights gained from analyzing Twitter data on inflation in various areas can be valuable for both businesses and governments. Continuous monitoring of public sentiment on such critical economic issues can aid in making data-driven decisions and responding effectively to public concerns. The project serves as an example of leveraging big data tools and natural language processing techniques to gain actionable insights from social media data.
