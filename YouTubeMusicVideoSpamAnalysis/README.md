# 🎶 YouTube Music Video Spam Analysis

An applied LLM-powered analysis to detect spam in YouTube music video comments for scalable and effective content moderation.

## 📌 Project Description

This project analyzes spam patterns in YouTube music video comments using Python and IBM WatsonX Granite LLM to enable automated, contextual spam moderation, and improve discussion quality.

## 📈 Dataset

- **Source**: [Kaggle - YouTube Comments Spam Dataset](https://www.kaggle.com/datasets/ahsenwaheed/youtube-comments-spam-dataset)
- **Content**: comment ID, author, date, content, video name, class label (spam/non-spam).

## 🚀 Key Results

- 1,710 cleaned comments from 5 music videos over 19 months (July 2013 - May 2015).
- Over 55% of comments detected as spam.
- Spam peaks during low-traffic periods and persists for long periods on certain videos.
- Popular videos (e.g., LMFAO, PSY) attract more spam.
- Spam is spread thinly across many accounts, not dominated by single spammers.
- Common spam keywords: “check”, “subscribe”, “please”, “video”.

## 🛠️ Tools

- Python (Data cleaning & EDA)
- Google Colab (Environment)
- IBM WatsonX Granite 3-2b-Instruct (LLM classification)

## 📊 Visual Analysis

- Spam vs. non-spam distribution over time.
- Video-wise spam frequency and spam wave analysis.
- Word cloud of spam keywords.
- Author-based spam heatmaps to visualize spammer patterns.

## 🎯 Insights

- Spam often dominates during low-comment activity windows, requiring targeted moderation.
- Spammers tend to focus on popular videos for extended periods.
- Spam is thinly distributed across many low-intensity accounts, making collective monitoring necessary.
- Keywords can be used for preliminary filtering before LLM classification.

## 🤖 AI Support

IBM WatsonX Granite was tested for automatic spam classification using a structured prompt based on manual analysis findings, achieving 63% accuracy in initial tests, and effectively identifying explicit spam but requiring prompt refinement for subtle promotions.

## 💡 Conclusion

This project demonstrates the potential of LLM-assisted spam detection to automate moderation workflows on YouTube, ensuring scalable, contextual spam filtering to maintain comment quality.

## 📬 Contact

Feel free to reach out if you have questions about this project:

📧 **Email:** azzahmstudio@gmail.com  
🌐 **LinkedIn:** [Azzah M](http://www.linkedin.com/in/azzah-m-165867214)
