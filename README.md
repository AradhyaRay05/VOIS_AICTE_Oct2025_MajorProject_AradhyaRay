# 🎬 Netflix Dataset Analysis - Comprehensive Data Analysis Project

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red.svg)](https://matplotlib.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📋 Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Project Objectives](#project-objectives)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Analysis Sections](#analysis-sections)
- [Key Insights](#key-insights)
- [Installation & Usage](#installation--usage)
- [Project Structure](#project-structure)
- [Visualizations](#visualizations)
- [Results & Recommendations](#results--recommendations)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🎯 Overview

This project presents a **comprehensive exploratory data analysis (EDA)** of Netflix's content library, examining trends in Movies vs. TV Shows, genre distribution, geographical content contributions, and temporal patterns from 2008 to 2021. The analysis provides actionable insights for content strategy and audience targeting.

The notebook contains **128 professional cells** with individual visualizations and detailed findings, making it suitable for presentation, portfolio, and academic purposes.

---

## 🔍 Problem Statement

**Content Trends Analysis for Strategic Recommendations**

Netflix has evolved from a US-centric streaming service to a global entertainment platform. Understanding how content distribution has changed over time is crucial for:
- Strategic content planning
- Market expansion decisions
- Audience preference identification
- Investment prioritization across genres and regions

This analysis aims to uncover how Netflix's content distribution (Movies vs. TV Shows, genres, and country contributions) has evolved over the years, identifying key patterns and providing data-driven recommendations.

---

## 🎯 Project Objectives

1. **Content Type Analysis**: Analyze the distribution of Movies vs. TV Shows and track their evolution
2. **Genre Intelligence**: Identify the most common genres and analyze popularity trends
3. **Geographical Insights**: Compare country-wise contributions and regional content strategies
4. **Temporal Patterns**: Understand content addition trends, peak periods, and growth phases
5. **Duration Analysis**: Examine movie durations and TV show season distributions
6. **Quality Metrics**: Analyze rating distributions and content maturity levels
7. **Strategic Recommendations**: Provide actionable insights for future content strategy

---

## 📊 Dataset Description

**Source**: Netflix Dataset (CSV format)

**Key Features**:
- **show_id**: Unique identifier for each title
- **type**: Movie or TV Show
- **title**: Name of the content
- **director**: Director(s) of the content
- **cast**: Main cast members
- **country**: Country/countries of production
- **date_added**: Date when content was added to Netflix
- **release_year**: Original release year
- **rating**: Content rating (PG, TV-MA, etc.)
- **duration**: Movie runtime (minutes) or TV show seasons
- **listed_in**: Genres/categories
- **description**: Brief synopsis

**Dataset Size**: 8,807 rows × 12 columns

**Time Period**: 2008 - 2021

---

## 🛠️ Technologies Used

### Programming Language
- **Python 3.8+**

### Core Libraries
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Static visualizations
- **Seaborn**: Statistical data visualization

### Development Environment
- **Jupyter Notebook**: Interactive data analysis
- **VS Code**: Code editing and version control

### Data Analysis Techniques
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Trend Analysis
- Correlation Analysis
- Data Visualization

---

## 📈 Analysis Sections

The comprehensive analysis is divided into the following sections:

### 1. **Data Loading and Initial Setup**
   - Library imports and configuration
   - Dataset loading and initial exploration

### 2. **Dataset Structure and Overview**
   - Comprehensive dataset information
   - Column descriptions and data types

### 3. **Data Quality Assessment**
   - Missing values analysis and visualization
   - Duplicate entries detection
   - Data integrity checks

### 4. **Content Type Distribution**
   - Movies vs TV Shows analysis
   - Bar charts, pie charts, and donut visualizations
   - Proportion analysis

### 5. **Temporal Analysis - Content Trends Over Years**
   - Yearly content addition trends (2008-2021)
   - Growth trajectory analysis
   - Peak year identification
   - Movies vs TV Shows evolution

### 6. **Genre Analysis**
   - Top genres identification
   - Genre popularity trends
   - Pie charts and treemap visualizations
   - Genre evolution over time

### 7. **Geographical Analysis**
   - Country-wise content contribution
   - Top 15 countries analysis
   - Regional trends over time
   - US vs International content balance

### 8. **Director and Cast Analysis**
   - Top directors and actors
   - Talent diversity metrics
   - Collaboration patterns

### 9. **Duration Analysis (Movies)**
   - Movie duration distribution
   - Histogram, box plot, and violin plot analysis
   - Short films identification
   - Duration trends over years

### 10. **TV Show Season Analysis**
   - Season count distribution
   - Single-season vs multi-season shows
   - Season trends over time

### 11. **Rating Analysis**
   - Content rating distribution
   - Rating trends by year
   - Rating by content type comparison

### 12. **Release Year Analysis**
   - Classic vs modern content analysis
   - Decade-wise distribution
   - Content age trends

### 13. **Monthly Addition Patterns**
   - Month-wise content addition analysis
   - Seasonal patterns identification

### 14. **Content Maturity Analysis**
   - Age-appropriate content distribution
   - Maturity level trends

### 15. **Country-Genre Relationship**
   - Top genres by country
   - Regional content preferences
   - Genre diversity by country

### 16. **Genre-Duration Correlation**
   - Average duration by genre
   - Duration patterns across genres

### 17. **Advanced Insights**
   - Correlation analysis
   - Multi-dimensional comparisons
   - Strategic recommendations

---

## 💡 Key Insights

### 📊 Content Distribution
- **Movies dominate** with approximately 70% of the catalog
- **TV Shows** represent 30% but show stronger proportional growth in recent years
- Peak content addition occurred in **2019** with over 2,000 titles

### 🌍 Geographical Trends
- **United States** leads content contribution significantly
- **India** ranks second, reflecting strategic market expansion
- **International content** has surpassed US content post-2016, now representing ~60% of new additions

### 🎭 Genre Insights
- **International Movies** and **Dramas** are the top genres
- **Documentaries** show consistent strong presence
- **Stand-Up Comedy** and **Kids' Content** show growth in recent years

### ⏱️ Duration Patterns
- Most movies fall in the **80-120 minute** range
- Average movie duration is approximately **90-95 minutes**
- **Single-season TV shows** dominate the TV catalog (70%+)

### 📅 Temporal Patterns
- **Explosive growth phase**: 2015-2019 (2,600% increase)
- **July and December** are peak months for content additions
- **2020 decline** reflects COVID-19 production impact

### 🎯 Rating Distribution
- **TV-MA** (Mature Audience) is the most common rating
- **Family-friendly content** (TV-PG, PG) represents significant portion
- Rating diversity has increased over time

---

## 🚀 Installation & Usage

### Prerequisites
```bash
Python 3.8 or higher
pip (Python package manager)
```

### Clone the Repository
```bash
git clone https://github.com/yourusername/netflix-data-analysis.git
cd netflix-data-analysis
```

### Install Required Packages
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Run the Analysis
```bash
jupyter notebook "Netflix Data Analysis.ipynb"
```

### Dataset Setup
1. Ensure `Netflix_Dataset.csv` is in the project root directory
2. The dataset should contain the columns mentioned in the Dataset Description section

---

## 📁 Project Structure

```
netflix-data-analysis/
│
├── Netflix Data Analysis.ipynb    # Main analysis notebook (128 cells)
├── Netflix_Dataset.csv             # Dataset file
├── README.md                       # Project documentation
│
└── visualizations/                 # (Optional) Exported charts
    ├── content_distribution.png
    ├── geographical_trends.png
    └── ...
```

---

## 📊 Visualizations

The project includes **75+ professional visualizations** across multiple types:

### Visualization Types Used
- **Bar Charts**: Content distribution, country contributions, genre popularity
- **Line Plots**: Temporal trends, growth trajectories
- **Pie Charts**: Proportion analysis, content type distribution
- **Donut Charts**: Category breakdowns
- **Heatmaps**: Missing values, correlations
- **Box Plots**: Duration distribution, outlier detection
- **Violin Plots**: Density and distribution analysis
- **Area Charts**: Cumulative growth, percentage trends
- **Stacked Charts**: Multi-category comparisons
- **Treemaps**: Hierarchical data visualization

All visualizations feature:
- Professional styling with Netflix color scheme (#E50914)
- Clear titles and labels (14-16pt fonts)
- Grid lines for readability
- Proper legends and annotations
- High-resolution output suitable for presentations

---

## 📈 Results & Recommendations

### Strategic Recommendations

#### 1. **Geographic Expansion**
- Continue investing in **Indian and Asian markets** (high growth potential)
- Strengthen presence in **emerging markets** (Latin America, Middle East)
- Maintain US content while expanding international library

#### 2. **Genre Strategy**
- Increase **Documentary** and **Stand-Up Comedy** production
- Focus on **International Movies** to cater to global audience
- Develop more **Limited Series** (single-season shows are popular)

#### 3. **Content Duration**
- Optimize movie durations around **90-95 minutes** (sweet spot)
- Consider more **short films** (10-40 minutes) for quick consumption
- Develop diverse TV show formats (1-3 seasons preferred)

#### 4. **Release Strategy**
- Capitalize on **July and December** for major releases
- Balance content ratings to appeal to both mature and family audiences
- Plan releases considering regional preferences

#### 5. **Quality over Quantity**
- Post-2019 data suggests focus shift from volume to quality
- Maintain diversity in genres and ratings
- Invest in critically acclaimed content across categories

---

## 🔮 Future Enhancements

Potential areas for expanding this analysis:

1. **Sentiment Analysis**: Analyze descriptions and reviews for audience sentiment
2. **Machine Learning Models**: 
   - Predict content success based on features
   - Recommend optimal content attributes for markets
   - Classification of content categories
3. **Advanced Visualizations**: Interactive dashboards using Plotly or Tableau
4. **Competitive Analysis**: Compare with other streaming platforms (Amazon Prime, Disney+)
5. **Audience Metrics**: Incorporate viewership data if available
6. **Network Analysis**: Analyze director-actor collaboration networks
7. **Time Series Forecasting**: Predict future content trends
8. **Natural Language Processing**: Extract insights from descriptions

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this analysis:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure your code follows best practices and includes appropriate documentation.

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact

**Aradhya Ray**

- GitHub: [@AradhyaRay05](https://github.com/AradhyaRay05)
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/yourprofile)
- Email: your.email@example.com

---

## 🌟 Star This Repository

If you found this analysis helpful or interesting, please consider giving it a ⭐!

---

<div align="center">

**Made with ❤️ for Data Science and Netflix enthusiasts**

*Last Updated: October 2025*

</div>
