# Analysis of the Android App Market on Google Play
---
<p><img src="images/google_play_store.webp" alt="Google Play Store">

---
This project provides a comprehensive analysis of over 10,000 apps from the Google Play Store. Using data science techniques, we explore app categories, pricing strategies, user ratings, and sentiment trends to uncover key insights. The findings are intended to guide app developers and businesses in creating successful mobile applications.

### Project Overview

Mobile apps are ubiquitous, and their development can be lucrative. This project focuses on answering critical questions such as:

- What are the most popular app categories?
- How do user ratings vary across mobile apps?
- How does price and size of apps affect ratings?
- What pricing models (free vs. paid) are most prevalent, and how do they impact app success?
- Can the category of an app be used to justify the price?
- Are users more satisfied with free apps?

The analysis is conducted using Python, with data visualization and exploration to derive actionable insights.

### Dataset

The project uses two datasets:

1. **apps.csv**: Contains details of Google Play Store apps, including 13 features like Category, Installs, Price, and Rating.
2. **user_reviews.csv**: Contains 100 reviews per app, with sentiment analysis features: Sentiment, Sentiment Polarity, and Sentiment Subjectivity.

### Tools and Libraries

- **pandas**: Data manipulation and cleaning
- **numpy**: Numerical computations
- **matplotlib & seaborn**: Data visualization
- **plotly**: Interactive visualizations

### Key Insights

- **App Categories**: Family and Game apps are most prevalent, while Medical apps are few but high-priced.
- **App Ratings**: The average rating is 4.17, with most apps receiving high ratings.
- **App Pricing**: Most apps are priced under $10, and Medical apps can reach up to $80.
- **User Sentiment**: Free apps tend to receive more negative feedback, while paid apps maintain a more positive sentiment.

### Project Structure

- **notebook.ipynb**: Jupyter notebook containing the full analysis
- **datasets/apps.csv**: Dataset with app details
- **datasets/user_reviews.csv**: Dataset with user reviews
- **requirements.txt**: Required libraries to be installed with pip
- **README.md**: Project overview and documentation (this file)

### How to Run

Clone the repository:

`git clone https://github.com/OlumideOlumayegun/Analysis-of-the-Android-App-Market-on-Google-Play.git`  

Install required libraries:

`pip install -r requirements.txt`  

Open the Jupyter notebook:

`jupyter notebook notebook.ipynb`  

### Future Work

    Explore freemium and subscription models.
    Perform regional analysis based on user demographics.
    Develop predictive models for app success based on app features.

### License

This project is licensed under the MIT License.

### Acknowledgments

This project was conducted as part of the project portfolio for DataCamp's Data Scientist with Python Career Track. The analysis, insights, and visualisations presented here were made possible using the dataset provided by DataCamp. Special thanks to DataCamp for their comprehensive curriculum and resources that facilitated the development of data analysis and visualisation skills demonstrated in this project.


---

See the <a href="https://github.com/OlumideOlumayegun/Analysis-of-the-Android-App-Market-on-Google-Play/blob/main/notebook.ipynb">Jupyter Notebook</a> or <a href="https://nbviewer.org/github/OlumideOlumayegun/Analysis-of-the-Android-App-Market-on-Google-Play/blob/main/notebook.ipynb">nbviewer page</a> for the complete analysis.
