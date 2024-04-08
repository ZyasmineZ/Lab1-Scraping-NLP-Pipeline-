# Lab1-Scraping-NLP-Pipeline

# Arabic Text Processing with NLP Techniques

This repository documents the exploration of Natural Language Processing (NLP) techniques applied to analyze poetry scraped from an Arabic website. The primary objective was to extract meaningful insights from the poems and gain a deeper understanding of their content and structure.

## Project Overview

1. **Scraping Arabic Web Sources:** The initial step involved web scraping techniques. The Scrapy framework was utilized to efficiently collect poems from the Diwan Al-Arab website (https://www.diwanalarab.com/). Scrapy facilitates automated web crawling and data extraction, making it well-suited for this task.

2. **Data Storage with MongoDB:** The scraped data, in its raw form, was stored within a MongoDB database.  This NoSQL database offered flexibility and scalability, making it well-suited to handle unstructured text data like poems.

3. **NLP Pipeline Development:**
   - **Text Cleaning:** Removed noise, irrelevant characters, and special symbols from the raw text data.
   - **Tokenization:** Segmented text into individual words or tokens, facilitating further analysis.
   - **Stop Words Removal:** Eliminated common stop words from the text to focus on meaningful content.
   - **Diacritics Removal:** Stripped diacritics from Arabic text to standardize and simplify textual representations.
   - **Normalization:** Applied techniques like Unicode normalization, case normalization, and whitespace normalization to standardize text representations.

4. **Stemming and Lemmatization Comparison:**
   - Conducted a comparative analysis of stemming and lemmatization techniques to evaluate their effectiveness.
   - Found that lemmatization outperformed stemming in terms of preserving semantic integrity and context, making it the preferred choice for Arabic text processing tasks.

5. **Parts of Speech (POS) Tagging:**
   - Implemented POS tagging to analyze grammatical structures and word categorization within the text.

6. **Named Entity Recognition (NER) Methods:**
   - Explored NER methods to identify and classify named entities such as persons, organizations, and locations in the text data.

## Conclusion

This lab provided hands-on experience with various NLP techniques for Arabic text processing. It highlighted the importance of data acquisition, cleaning, and preparation before applying more advanced NLP methods. I compared stemming and lemmatization, understanding the trade-off between efficiency and semantic accuracy.

This experience has broadened our understanding of the NLP tools available for Arabic text processing. By combining these techniques, I can extract valuable insights from Arabic web sources and unlock the potential of Arabic NLP for various applications.

