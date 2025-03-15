# ChatGPT Reviews Analysis with Python

## Project Overview
I analyzed user reviews of ChatGPT, including textual feedback, ratings, and review dates. The goal was to understand user sentiment, identify what users like and dislike, analyze trends over time, and compute the Net Promoter Score (NPS) for ChatGPT.

## Dataset
The [dataset](https://statso.io/what-people-think-about-chatgpt-case-study/) consists of user reviews, including:
- Textual feedback
- Ratings (1 to 5 stars)
- Review dates

## Steps Involved in Analysis

### 1. Data Preprocessing
- The dataset contained some null values in the review column.
- I replaced these null values with empty strings to ensure they did not affect the analysis.

### 2. Sentiment Analysis
- I determined the sentiment of each review using the `textblob` library.
- I classified reviews into three categories: **Positive, Neutral, and Negative**.

### 3. Sentiment Distribution
I visualized the sentiment distribution of reviews to understand the proportion of positive, neutral, and negative reviews.

![Sentiment Distribution](https://github.com/Sourabh1710/ChatGPT-Reviews-Analysis/blob/main/images/Sentiment%20Distribution%20of%20Chatgpt%20Reviews.png)

### 4. Analyzing What Users Like About ChatGPT
To understand what users appreciate about ChatGPT:
- I filtered reviews with a **positive sentiment**.
- I extracted and analyzed the most common phrases and keywords from positive reviews.

![Positive Reviews Analysis](https://github.com/Sourabh1710/ChatGPT-Reviews-Analysis/blob/main/images/Top%20Common%20Phrases%20in%20Positive%20Reviews.png)

#### Findings:
- Users describe ChatGPT as a **“great app”**, frequently mentioning phrases like **“amazing app”**, **“AI app”**, and **“excellent app”**.
- It is praised for being **“useful”**, **“user-friendly”**, and **helpful for students**.
- The free version and ability to answer questions effectively are appreciated.

### 5. Analyzing What Users Don’t Like About ChatGPT
To identify recurring complaints:
- I filtered reviews with **negative sentiment**.
- I extracted and analyzed the most common phrases and keywords from negative reviews.

![Negative Reviews Analysis](https://github.com/Sourabh1710/ChatGPT-Reviews-Analysis/blob/main/images/Top%20Common%20Phrases%20in%20Negative%20Reviews.png)

#### Findings:
- Complaints include **“bad app”**, **“useless app”**, and **“doesn’t work”**.
- Technical issues such as **“error occurred”**, **“network error”**, and **“error messages”** are common.
- Users express dissatisfaction with incorrect or misleading answers and difficulty using features like **voice chat**.

### 6. Common Problems Faced by Users
- I categorized frequent phrases found in negative reviews into broader problem areas.
- I visualized the most common user complaints.

![Common Problems](https://github.com/Sourabh1710/ChatGPT-Reviews-Analysis/blob/main/images/Common%20Problems%20Faced%20by%20Users%20in%20ChatGPT.png)

#### Findings:
- The most reported issue is **“Incorrect Answers”**.
- Other major concerns include **App Performance** and **Quality of Responses**.

### 7. Analyzing How Reviews Changed Over Time
To understand trends:
- I aggregated reviews by sentiment over time.
- I visualized the volume of each sentiment type across different months.

![Sentiment Trends Over Time](https://github.com/Sourabh1710/ChatGPT-Reviews-Analysis/blob/main/images/Sentiment%20Trends%20Over%20Time.png)

#### Findings:
- **Positive reviews increased significantly from March to May 2024** and slightly declined in July 2024.
- **Neutral reviews showed a gradual increase**, peaking around May 2024.
- **Negative reviews remained relatively stable** and low throughout the period.

### 8. Analyzing How Often Users Promote ChatGPT (Net Promoter Score - NPS)
Net Promoter Score (NPS) measures how likely users are to recommend a product. Based on ratings:
- **Promoters:** 5-star ratings
- **Passives:** 4-star ratings
- **Detractors:** 3-star or lower ratings

**NPS Formula:**
\[ NPS = \% \text{Promoters} - \% \text{Detractors} \]

The calculated **NPS for ChatGPT is approximately 64.35**, which is considered an excellent score.

## Summary
- **Most users have a positive experience** with ChatGPT.
- **Common praises:** Usability, AI capabilities, and educational benefits.
- **Common complaints:** Incorrect answers, performance issues, and technical errors.
- **NPS Score (64.35)** indicates high user satisfaction and likelihood of recommendation.

## Author
Sourabh Sonker <br>
Data Scientist

