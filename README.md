# 22MIA1167_BA_Hackathon
📊 Dataset Source

This project uses the Bot Detection Dataset available on Kaggle:
https://www.kaggle.com/datasets/goyaladi/twitter-bot-detection-dataset

The dataset contains structured Twitter user profile data and associated tweet activity, along with a binary classification label indicating whether an account is a bot (1) or a human (0). It includes behavioural, engagement, textual, and credibility-related features that make it ideal for building intelligent bot detection systems.

🧠 Why This Dataset is Perfect for Behavioural Analytics

Unlike traditional spam datasets that focus only on keyword detection, this dataset enables true behavioural modelling. It captures how users interact, post, and engage — not just what they say. By including engagement metrics (retweets, mentions), network indicators (follower count, verified status), linguistic content (tweet text, hashtags), and temporal signals (creation timestamp), the dataset allows us to model behavioural patterns that differentiate organic human activity from automated bot behaviour.

Bots typically display structured engagement patterns, abnormal follower dynamics, repetitive text structures, and coordinated posting timing. This dataset allows us to transform those behavioural signals into measurable features and build predictive models that identify manipulation and artificial engagement. Because it contains a labelled target variable, it supports supervised learning while still allowing advanced behavioural anomaly detection approaches.

⚙️ Behavioural Features Engineered

To move beyond raw metadata, we engineered behavioural intelligence features that capture deeper patterns of account activity.

From engagement behaviour, we derived total engagement, engagement ratios relative to followers, mention ratios, and hashtag intensity to detect artificial amplification and spam tagging strategies.

From network behaviour, we incorporated follower count normalization, verified status encoding, and follower-to-activity relationships to identify credibility imbalance patterns often associated with bot networks.

From linguistic behaviour, we extracted text length, word count, capitalization ratios, digit usage, special character density, sentiment polarity, and TF-IDF embeddings to capture automation language signatures and repetitive posting styles.

From temporal behaviour, we engineered posting frequency, time differences between tweets, timing regularity scores, and burst activity flags to detect automated scheduling and coordinated bot clusters.

These engineered features transformed the dataset from simple social media metadata into a behavioural analytics framework capable of detecting coordinated and artificial digital behaviour.

