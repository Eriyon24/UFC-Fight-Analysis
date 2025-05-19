# UFC-Fight-Analysis

# 🥊 UFC Fight Outcome & Upset Analysis (2010–2020)

This project explores the relationship between UFC fight outcomes and betting odds from 2010 to 2020. We focus on identifying **underdog victories (upsets)** and patterns across weight classes, years, and fight types using scraped fight data and odds.

## 📦 Dataset
- **6,000+ UFC fights**
- Sourced from: [UFCStats](http://ufcstats.com) & [BestFightOdds](https://www.bestfightodds.com)
- Includes:
  - Fighter names
  - Fight dates and locations
  - Betting odds (`R_odds`, `B_odds`)
  - Winners
  - Weight class
  - Title bout flag

## 🧠 Key Analysis
- **Upset Definition**: Fighter with worse odds wins
- **Overall upset rate**: ~23%
- **Title bouts**: Lower upset frequency than non-title bouts
- **Common upset range**: Odds between +100 and +250
- **Weight class trends**: Flyweight and Bantamweight had more frequent upsets

## 📊 Visual Insights
- Distribution of odds differences (favorites vs underdogs)
- Upsets over time (2010–2020)
- Correlation heatmap (odds, title status, upset likelihood)
- Upset wins by weight class

## 🔮 Future Work
- Apply predictive models (Logistic Regression, Random Forest) to forecast fight outcomes
- Simulate ROI from betting on underdogs
- Engineer advanced features: fight finish method, short-notice replacements, fighter stats

## 📄 Report
- Includes a **20+ page report** with visualizations and breakdowns
- Generated using Python, Pandas, BeautifulSoup, Matplotlib in Google Colab

---

> Built by [Eriyon Adams](mailto:eriyonadams10@gmail.com) & Abraham Gonzales
