<h1 align="center"><strong>Analyzing the Skincare Industry: A Data-Driven Approach</strong></h1>

![AI Generated Image](ai-generated-8123375_1280.png)

### **Unveiling the Secrets of Skincare: A Data-Driven Exploration**

In the dynamic world of beauty and skincare, every product carries a narrative—of promises to consumers, expectations from brands, and the underlying connection that binds them: data. As the industry evolves with innovations and trends, it becomes increasingly vital to look beyond attractive packaging and uncover the data-driven insights that influence consumer preferences and market trends.

This project embarks on a journey to decode the skincare industry using data from 8,494 products. From cult-favorite serums to budget-friendly moisturizers, each data point contributes to a more comprehensive understanding of the market. By employing exploratory analysis and predictive modeling, we reveal the factors driving success in this vibrant and competitive industry.

---

#### **The Mission**

Imagine a world where predicting the next best-selling skincare product or determining the ideal price point is not a guessing game but a science. This project aims to turn that vision into reality. Through rigorous data analysis and machine learning, we uncover the "why" behind consumer decisions and the "how" for brands to excel.

---

#### **Objectives**

1. **Data Cleaning and Preparation**:  
   - Address missing values and standardize data to ensure accuracy and consistency.  
   - Engineer new features to enhance the dataset and unlock deeper insights.

2. **Exploratory Data Analysis (EDA)**:  
   - Explore trends in pricing, ratings, consumer feedback, and brand performance.  
   - Visualize relationships between product attributes and their impact on market success.

3. **Solution Strategies**:  
   - **Price Optimization Model**: Recommends products by identifying optimal price points tailored to consumer budgets and preferences.  
   - **High-Rating Product Filtering (Excluding Specific Brands)**: Focuses on customer satisfaction by filtering products with high ratings, excluding underperforming brands, and emphasizing popular choices. This analysis helps businesses make informed decisions regarding inventory, investments, and marketing strategies to maximize revenue and customer satisfaction.

---

#### **Significance**

By combining exploratory and predictive techniques, this analysis provides a comprehensive view of the skincare market. It offers actionable insights for businesses striving to enhance their market presence, researchers studying consumer behavior, and consumers making informed purchasing decisions.

This project underscores the value of data analytics in shaping the future of the skincare industry, offering a blueprint for innovation and success.

---

# **Product Information and Reviews Analysis**

## **Overview**
This project analyzes product and review data to extract meaningful insights. The dataset includes product details, pricing, reviews, and customer interactions. The goal is to use this data for understanding customer preferences, product performance, and key attributes influencing sales and satisfaction.

---

## **Dataset Description**
The dataset contains two main components:
1. **Product Information**: Details about products, including pricing, variations, and highlights.
2. **Reviews Data**: Customer reviews with ratings, recommendations, and additional feedback.

### **Key Columns**
#### Product Information
- **product_id**: Unique product identifier.
- **product_name**: Full product name.
- **brand_id**: Unique brand identifier.
- **brand_name**: Name of the product brand.
- **loves_count**: Number of users who marked the product as a favorite.
- **rating**: Average user rating.
- **price_usd**: Product price in USD.
- **limited_edition**, **online_only**, **out_of_stock**, etc.: Boolean indicators of product attributes.
- **primary_category**, **secondary_category**, **tertiary_category**: Categorization details.

#### Reviews Data
- **author_id**: Unique identifier for the review author.  
- **rating**: Rating provided by the customer (1–5 scale).  
- **is_recommended**: Whether the product is recommended by the reviewer (1 for yes, 0 for no).  
- **helpfulness**: Ratio of positive to total feedback for the review.  
- **review_text**: The main text of the review.  
- **review_title**: Title of the review.  
- **skin_tone**, **eye_color**, **skin_type**, **hair_color**: Reviewer demographics (if available).  

---

## **Project Objectives**
1. **Data Cleaning**: Handle missing values, remove duplicates, and standardize formats to ensure data quality.
2. **Exploratory Data Analysis (EDA)**:  
   - Analyze pricing trends, product popularity, and review sentiments.  
   - Identify top-rated brands and categories.  
   - Explore correlations between features like `price_usd`, `rating`, and `loves_count`.  
3. **Feature Engineering**: Create additional features for better insights (e.g., discount percentages, normalized ratings).  
4. **Insights Extraction**:  
   - Highlight best-performing products and categories.  
   - Analyze user feedback for recurring themes.  
   - Identify opportunities for product improvement.  

---

## **Technologies and Tools**
- **Python Libraries**:  
   - `pandas` for data cleaning and manipulation.  
   - `matplotlib` and `seaborn` for visualizations.  
   - `numpy` for numerical analysis.  
- **Jupyter Notebook**: For interactive development and visualization.
- **Streamlit** (Optional): For building a dashboard to present findings.

---

## **Usage**
1. Clone this repository:  
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:  
   ```bash
   python analysis.py
   ```
4. (Optional) Launch the dashboard:  
   ```bash
   streamlit run app.py
   ```

---

## **Results**
Key findings will be summarized here after the analysis is completed, including:  
- Most loved and best-reviewed products.  
- Key pricing trends and insights.  
- Recommendations for product development and marketing strategies.

---

## **Future Work**
- Build predictive models to recommend products based on customer preferences.  
- Analyze sentiment in review texts using Natural Language Processing (NLP).  
- Develop a live dashboard for real-time insights.

---

## **Contributors** 
  Data Scientist: Silindile Ndlela 


