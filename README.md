# GenAI Web-Scrape BBC Title Generator  
> A project focused on generating accurate and realistic titles for BBC articles using a seq-to-seq model built with transformers, developed independently.

> The initial dataset, sourced from Kaggle, contained around 2,250 rows of BBC articles, including titles and content. To demonstrate the potential for expanding this dataset and improving model performance, we web-scraped the BBC website over the course of one day, extracting approximately 200 additional rows of new articles.

> This web-scraping process illustrated how we could significantly increase the size of the dataset by regularly extracting new articles, which would enhance the performance of our model by providing more diverse training data.

> Once the expanded dataset was prepared, a sequence-to-sequence (seq-to-seq) model using transformers was developed. This model was trained to generate highly accurate and realistic titles based on the contents of the articles.

> The effectiveness of the generated titles was evaluated using ROUGE metrics, comparing the generated titles to the original ones. The results showed that the generated titles were highly accurate and demonstrated strong potential for practical use.

## Design Process and Methods  
> **Data Collection and Web Scraping:**  
> - The initial dataset was obtained from Kaggle, containing 2,250 rows of BBC articles with their titles and contents.  
> - To expand the dataset, we performed web scraping on the BBC website for one day, extracting approximately 200 new articles.  
> - The combined dataset, now with around 2,450 rows, was used to train and evaluate the model.

> **Model Development - Sequence-to-Sequence (Seq-to-Seq) using Transformers:**  
> - A seq-to-seq model architecture based on transformers was designed to generate titles from article contents.  
> - The model was trained on the combined dataset, leveraging the additional data to improve its ability to generate accurate and contextually relevant titles.  
> - The use of transformers allowed the model to effectively capture the relationship between the article content and the corresponding title.

> **Model Evaluation - ROUGE Metrics:**  
> - The accuracy and realism of the generated titles were evaluated using ROUGE (Recall-Oriented Understudy for Gisting Evaluation) metrics.  
> - ROUGE scores were calculated by comparing the generated titles to the original ones, providing a quantitative measure of the model’s performance.  
> - The results indicated that the model-generated titles closely matched the original titles, showcasing the model’s effectiveness in generating realistic and relevant titles.

> **Results and Impact:**  
> - The project demonstrated the feasibility of enhancing a title generation model by expanding the dataset through web scraping.  
> - The seq-to-seq model, trained on the expanded dataset, achieved high accuracy in generating titles that were comparable to those written by human authors.  
> - The use of ROUGE metrics provided a reliable evaluation of the model’s performance, affirming its potential for practical applications in automated content generation.
