# social-media-analytics-project
Social Media Growth Predictor uses Python to analyze social media metrics (views, likes, followers) and predict future engagement trends. Utilizing Linear Regression and data visualization, it provides insights into social media performance to optimize content strategy.
# Social Media Analytics and Growth Prediction

This project analyzes social media metrics across various platforms (Instagram, TikTok, YouTube, Twitter, and Pinterest) to predict engagement and future growth. The dataset includes metrics like views, likes, comments, followers, and interactions. We aim to understand how these metrics influence each other and how they contribute to overall social media growth for a business focused on health-related content.

## Project Overview

We are using Python, with libraries such as `pandas`, `scikit-learn`, `matplotlib`, and `seaborn`, to create models that can predict future social media engagement based on the current dataset. Our goals are to:
- Analyze correlation between views, likes, comments, followers, and interactions.
- Use regression models (initially linear) to predict overall growth.
- Understand which platforms (TikTok, Instagram, Twitter, etc.) contribute most to follower and engagement growth.
- Evaluate how current engagement metrics can lead to increased reach for pain management and health-related content.

## Data

The dataset includes metrics collected from the following platforms:
- **Instagram**
- **TikTok**
- **YouTube**
- **Twitter**
- **Pinterest**

Each platform has the following metrics: 
- **Views**
- **Likes**
- **Comments**
- **Followers**
- **Interactions**

## Model

The project uses the **Linear Regression** model as a baseline to predict social media growth based on views, likes, and other engagement metrics. We aim to refine the model in the future by exploring **Polynomial Regression** and other approaches like **Decision Trees** if needed.

## Visualizations

We used **pairplot** from `seaborn` to explore relationships between variables. We also created scatter plots comparing actual vs. predicted views.

## Steps to Run the Project

1. Clone this repository:
    ```bash
    git clone https://github.com/Dgsc23/custom-chatbot.git
    ```

2. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the analysis:
    Open `Untitled1.ipynb` in Jupyter or Anaconda to run the regression model and generate visualizations.

4. Explore the correlation and regression outputs to evaluate the model.

## Future Enhancements

- Implementing Polynomial Regression or Decision Tree-based models to improve predictions.
- Collecting more data and implementing APIs to automate data collection from social platforms.
- Investigating snowball effects and algorithmic pushes as platforms like TikTok and Twitter favor viral content.

## Tools & Libraries Used

- **Python 3.10**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook (Anaconda)**

## Results

- The correlation matrix shows a strong relationship between views and interactions (0.999).
- Regression analysis helps predict future growth based on current engagement metrics.

## Contributing

Feel free to submit issues or pull requests if you want to contribute to the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

