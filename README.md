# 🎮 Video Game Market Analysis Using Data Science & RAWG API

This project focuses on analyzing trends in the video game market to understand patterns in sales, genres, and platform performance over time. By integrating RAWG's API, we retrieve additional data on the release years of video games, enriching the analysis and ensuring more accurate insights. Through data cleaning, visualization, and statistical modeling, this project provides actionable insights to guide business strategies in the gaming industry.

# 📝 Overview
The objective of this project is to identify key factors influencing video game sales and recommend strategies based on market trends. The dataset was enriched using the RAWG API to obtain game release dates, helping us examine the evolution of popular genres and platforms over time. The analysis highlights how sales patterns vary by region and platform, guiding stakeholders to make data-driven decisions.

# 🚀 Key Insights
**1. Global Market Trends:**

- Identified significant differences in game sales across regions (North America, Europe, and Japan), with distinct genre preferences in each.
- Sales peaked in specific years due to major platform releases and hit games, confirmed with RAWG API data.
- Certain genres like Action and Sports games consistently dominated sales across all regions.

  **2. Platform Performance:**

- Platforms such as PlayStation and Xbox outperformed others during specific periods, but newer platforms are gaining ground.
- Older platforms showed a decline, with sales gradually shifting towards modern consoles and digital distribution platforms.

**3. Release Timing & Sales:**
- Using data from the RAWG API, we confirmed that release years significantly impact a game’s lifetime sales, with more recent releases showing faster adoption in Western markets.

# 📊 Results and Conclusions
- Action and Shooter games dominate global sales, with regional preferences impacting demand (e.g., JRPGs in Japan).
- Release year and platform choice are critical factors influencing a game’s success, making it essential to align launches with trends and upcoming platform releases.
- Sales distribution varies heavily by region, indicating the importance of tailoring marketing strategies to specific markets.

# 🛠️ Tools and Technologies Used
- Python: Data cleaning, exploration, and statistical analysis.
- Pandas & NumPy: Data manipulation and transformation.
- Seaborn & Matplotlib: Visualization of trends and insights.
- Scikit-learn: Basic statistical modeling.
- RAWG API: Retrieval of video game release data.
- Jupyter Notebook: Development environment.

# 🔍 How to Run the Project
1. Clone the repository:
```
git clone <repository-url>
cd proyecto_sprint6

```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the notebook:
```
jupyter notebook proyecto_6_entregado.ipynb
```

# 💡 Future Work
- Implement machine learning models to predict future sales based on historical data.
- Explore deeper integrations with APIs like Twitch to analyze live streaming trends.
- Develop a dashboard for interactive analysis of sales trends across platforms and regions.

# 🏆 Acknowledgments
Special thanks to **RAWG.io** for providing access to their API, which added critical insights on release dates and game trends. This project was built as part of an ongoing learning journey in data analysis and business strategy development within the video game industry.
