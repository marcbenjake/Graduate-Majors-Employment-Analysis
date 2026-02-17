# College Majors Employment & Earnings Analysis

A comprehensive data analysis examining employment outcomes, earnings potential, and demographic patterns across 172 college majors representing 6.8 million recent college graduates.

## 📊 Project Overview

This project analyzes recent college graduate data to identify critical patterns in:
- Employment outcomes and unemployment rates
- Earnings potential across different majors and categories
- Gender distribution and pay disparities
- Full-time vs part-time employment rates
- Low-wage job placement risks

The analysis addresses 12 key research questions to inform strategic recommendations for improving graduate outcomes.

## 🔍 Key Findings

### Critical Statistics
- **Total Majors Analyzed:** 172
- **Total Graduates:** 6,771,654
- **Average Unemployment Rate:** 6.80%
- **Average Median Earnings:** $40,077
- **Full-Time Year-Round Employment:** 63.14%

### Major Discoveries

#### 🚨 Gender Pay Gap Crisis
- **Female-dominated majors** (>70% women): Average earnings of **$33,162**
- **Male-dominated majors** (<30% women): Average earnings of **$52,094**
- **Pay Gap:** **$18,932** (57% higher for male-dominated fields)
- **Correlation:** -0.6187 between percentage of women and median earnings

#### 📈 Unemployment Challenges
- **59.9% of majors** (103 out of 172) have unemployment rates **above the 6% national average**
- Highest unemployment categories:
  - Social Science: 9.57%
  - Law & Public Policy: 9.08%
  - Arts: 9.02%
- Lowest unemployment categories:
  - Physical Sciences: 4.65%
  - Industrial Arts & Consumer Services: 4.81%
  - Education: 5.17%

#### 💰 Earnings Extremes
**Highest Earning Majors:**
1. Petroleum Engineering: $110,000
2. Mining and Mineral Engineering: $75,000
3. Metallurgical Engineering: $73,000

**Lowest Earning Majors:**
1. Library Science: $22,000
2. Counseling Psychology: $23,400
3. Educational Psychology: $25,000

**Earnings Gap:** 5:1 ratio between highest and lowest paying majors

#### 📊 Employment Quality Issues
- **Part-Time Work:** Biology graduates have 39.7% part-time employment (highest among top 10 majors)
- **Low-Wage Jobs:** Communications & Journalism majors average 12,399 low-wage jobs (highest risk)
- **Earnings Variability:** High-earning fields like Astronomy and Pharmacy show massive earnings spreads, indicating high-risk/high-reward outcomes

## 📋 Research Questions Addressed

1. **What are the 5 most common majors among recent graduates?**
   - Psychology (393,735), Business Management (329,927), Biology (280,709), General Business (234,590), Communications (213,996)

2. **What is the gender distribution across these 5 majors?**
   - Significant gender imbalances identified, with Psychology 78% female and General Business 43.6% female

3. **Which majors have the highest and lowest median earnings?**
   - Engineering dominates top earnings; Education and Psychology at the bottom

4. **How does the unemployment rate vary across different major categories?**
   - 2x variation from lowest (4.65%) to highest (9.57%) categories

5. **Do female-dominated majors have lower earnings than male-dominated majors?**
   - YES - $18,932 pay gap identified

6. **Are students in more popular majors more likely to find full-time employment?**
   - NO correlation found between popularity and employment quality

7. **Do majors with more full-time employees have higher median earnings?**
   - NEGATIVE correlation (-0.079) suggests oversupply depresses wages

8. **Which major categories have the highest/lowest average number of low-wage jobs?**
   - Highest: Communications & Journalism (12,399); Lowest: Agriculture (824)

9. **How many majors have unemployment above 6%?**
   - 103 majors (59.9%) - majority of majors fail to beat national average

10. **Which top 10 major has the highest percentage of part-time workers?**
    - Biology at 39.7% (corrected: using Part_time/Employed ratio)

11. **Which majors have the largest earnings spread?**
    - Astronomy, Pharmacy, and specialized Engineering fields show highest variability

12. **What are the strategic recommendations for improving outcomes?**
    - See Recommendations section below

## 💡 Strategic Recommendations

### 1. Address Gender Pay Disparity
- Implement targeted scholarships for women in high-earning fields
- Advocate for increased compensation in female-dominated professions
- Create mentorship programs connecting female students with STEM/Business professionals
- Mandate transparent salary disclosures

### 2. Enhance Career Counseling
- Develop comprehensive "Total Cost of Ownership" analysis for each major
- Require labor market analysis courses before major declaration
- Create real-time employment outcome dashboards
- Warn students about high-risk majors

### 3. Restructure High-Risk Programs
- Reduce enrollment in consistently poor-outcome majors
- Mandate internships for high-risk fields (Communications, Arts)
- Audit curriculum gaps in high-unemployment categories
- Develop hybrid degree programs

### 4. Improve Employment Quality
- Target 75% full-time year-round employment (vs current 63%)
- Partner with employers for guaranteed placement programs
- Address part-time work issues in Biology and Psychology
- Create employer consortiums for problematic majors

### 5. Combat Low-Wage Placement
- Establish minimum wage thresholds for career services postings
- Reduce low-wage placement by 50% in Communications & Journalism
- Create certification programs in high-demand skills

### 6. Manage Earnings Variability
- Provide pathway guidance for high-variability fields
- Develop income-share agreements for high-risk majors
- Show full earnings distributions, not just medians

## 📁 Project Structure

```
├── Dataset/
│   └── Milestone_1_-_Marcus.xlsx          # Main dataset with all analysis sheets
├── Analysis/
│   ├── Question_9_Corrected_Analysis.xlsx # Corrected unemployment analysis
│   └── Question_9_Comparison.xlsx         # Comparison of methodologies
├── Reports/
│   └── Executive_Summary.docx             # Comprehensive executive summary
└── README.md                               # This file
```

## 🛠️ Methodology

### Data Source
The dataset contains 172 college majors with the following variables:
- Enrollment statistics (Total, Men, Women)
- Employment metrics (Employed, Full_time, Part_time, Unemployed)
- Earnings data (Median, P25th, P75th)
- Job quality indicators (College_jobs, Non_college_jobs, Low_wage_jobs)
- Major category classifications

### Analysis Techniques
- **Descriptive Statistics:** Central tendency and distribution analysis
- **Correlation Analysis:** Identifying relationships between variables
- **Comparative Analysis:** Gender, category, and major-level comparisons
- **Percentile Analysis:** Understanding earnings variability
- **Filtering & Segmentation:** Identifying high-risk and high-opportunity majors

### Tools Used
- **Microsoft Excel:** Pivot tables, charts, and data visualization
- **Python/Pandas:** Statistical analysis and data manipulation
- **Data Visualization:** Bar charts, comparison tables, trend analysis

## 📊 Key Visualizations

The project includes comprehensive visualizations for:
1. Top 5 majors by enrollment (bar chart)
2. Gender distribution across top majors (stacked bar chart)
3. Earnings extremes comparison (horizontal bar charts)
4. Unemployment rates by category (bar chart)
5. Gender pay gap analysis (comparison chart)
6. Full-time employment correlation analysis
7. Low-wage job risk by category
8. Part-time work percentages in top majors
9. Earnings spread analysis
10. Category-level unemployment breakdown (corrected)

## 🔧 Data Quality Notes

### Corrections Made
**Question 9 Methodology Correction:**
- **Original approach:** Counted ALL majors in each category (172 total)
- **Corrected approach:** Filtered for majors with unemployment > 6% FIRST, then counted by category (103 total)
- **Impact:** Reveals that 59.9% of majors fail to achieve below-average unemployment

**Question 10 Calculation Note:**
- Uses `Part_time / Total` for percentage calculation (more accurate than `Part_time / Employed`)
- English Language & Literature has highest part-time percentage at 29.7%

## 📈 Future Analysis Opportunities

### Unexplored Dataset Features
1. **College_jobs vs Non_college_jobs:** Analyze credential underutilization
2. **Geographic Analysis:** Regional variations in outcomes
3. **Within-Major Gender Analysis:** Distinguish occupational segregation from discrimination
4. **Temporal Trends:** Track changes over time if multi-year data available
5. **Multivariate Regression:** Identify strongest predictors of success

### Proposed Composite Metrics
- **Career Value Score:** Weighted combination of earnings, unemployment, FT employment, and wage quality
- **Risk-Adjusted ROI:** Expected value considering earnings variability
- **Employment Quality Index:** Holistic measure of job outcomes

## 👥 Author

**Marcus**
- Data Analyst
- Focus: Educational outcomes and labor market analysis

## 📄 License

This project is available for educational and research purposes.

## 🙏 Acknowledgments

- Dataset source: Recent College Graduates employment survey
- Analysis framework: Educational outcomes research methodologies
- Visualization guidelines: Data presentation best practices

## 📞 Contact & Contributions

For questions, suggestions, or contributions to this analysis, please:
- Open an issue in this repository
- Submit a pull request with improvements
- Contact the author for collaboration opportunities

---

## 🎯 Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/college-majors-analysis.git
   ```

2. **Review the dataset:**
   - Open `Milestone_1_-_Marcus.xlsx`
   - Explore individual analysis sheets for each question

3. **Read the executive summary:**
   - Open `Executive_Summary.docx` for comprehensive findings

4. **Examine corrected analyses:**
   - Review `Question_9_Corrected_Analysis.xlsx` for methodology corrections

## 📚 Key Insights for Students

### ✅ Consider These Factors When Choosing a Major:

1. **Not just median earnings** - look at the full distribution (25th to 75th percentile)
2. **Unemployment risk** - 60% of majors exceed national average
3. **Gender pay patterns** - understand structural inequalities
4. **Employment type** - full-time vs part-time likelihood
5. **Low-wage job risk** - probability of underemployment
6. **Category-level trends** - not all Engineering/Business majors are equal
7. **Supply/demand dynamics** - popularity can depress wages

### ⚠️ High-Risk Red Flags:

- Female-dominated fields with systematically lower pay
- Majors with unemployment > 9%
- Fields with >30% part-time employment
- Categories with >10,000 average low-wage jobs
- Majors with extreme earnings variability without clear pathways

### ✨ Promising Opportunities:

- Physical Sciences (low unemployment, decent earnings)
- Nursing (strong employment, competitive pay)
- Specialized Engineering (high earnings, moderate risk)
- Business fields with clear career tracks
- Education (stable employment, though lower pay)

---

**Last Updated:** February 2026
**Dataset Period:** Recent College Graduates
**Status:** ✅ Analysis Complete | 📊 Visualizations Ready | 📝 Documentation Published
