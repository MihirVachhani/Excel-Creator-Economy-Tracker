# Creator Economy Intelligence

### YouTube Creator Growth, Monetization & Sustainability Analysis

An analytical project focused on understanding YouTube creators as businesses — looking beyond subscribers and views to study **growth, engagement, monetization, creator maturity and sustainability risk**.

This is the first project in my longer-term focus on **Creator, Gaming, Esports and Digital Entertainment Analytics**.

---

## 📌 Project Overview

I didn't want to make another basic Excel project where the analysis ends with charts such as *Top YouTubers by Subscribers* or *Top Categories by Views*.

Instead, I wanted to use the data to answer questions that are closer to real business problems:

* Where is the creator economy concentrated?
* Which categories have the strongest earning potential?
* Which categories monetize attention most efficiently?
* Does creator scale always mean better productivity?
* Which creator segments are showing stronger growth?
* Where is there an earnings gap or untapped monetization potential?
* How concentrated are subscribers and earnings among large creators?
* How does creator maturity relate to engagement and burnout risk?
* Which creator segments or categories could represent better opportunities?

The project is being developed as a complete business intelligence case study rather than just a dashboard.

---

# 🎯 Project Objectives

The analysis focuses on four main areas:

### 1. Market Understanding

Understand creator growth, market concentration and geographic distribution.

### 2. Monetization

Identify earning potential, monetization efficiency and potential revenue gaps.

### 3. Creator Performance

Analyze engagement, subscriber growth, content productivity and creator size.

### 4. Sustainability & Opportunity

Understand burnout risk, creator maturity and areas with potential for further growth or monetization.

---

# 📊 Dashboard A — Executive Overview

Dashboard A provides a high-level view of the creator economy.

The goal is simple:

> **What does the creator economy currently look like?**

### KPIs

* Total Channels Tracked
* Average Estimated Yearly Earnings
* Maximum Earnings Potential
* High Burnout Risk %

### Analysis Included

#### Channel Creation Trend

Tracks the number of creators created across different years.

#### Top Countries by Creator Economy

Shows the countries with the largest subscriber base.

#### Revenue Potential by Category

Compares estimated yearly earnings with expected yearly earnings across content categories.

#### Monetization Efficiency by Category

Measures how efficiently different categories monetize views.

#### Audience Engagement by Category

Compares average engagement levels across categories.

#### Burnout Risk by Category

Shows the distribution of Low, Medium and High burnout risk.

#### Subscriber Growth by Channel Size Tier

Compares recent subscriber growth across Macro, Mega, Micro and Mid creators.

### Dashboard A Purpose

Dashboard A is designed for a quick executive-level understanding of:

**Market → Geography → Revenue → Engagement → Growth → Risk**

---

# 📈 Dashboard B — Creator Strategy & Decision Intelligence

Dashboard B goes deeper into the data and focuses on strategic questions.

The main question is:

> **Where are the opportunities, gaps and risks that could influence future creator or business decisions?**

### Analysis Included

#### Monetization Ceiling vs Reality

Compares estimated earnings against maximum earning potential to identify categories with larger monetization gaps.

#### Earnings Concentration Among Top Creators

Uses cumulative earnings to understand how concentrated creator earnings are among the highest-earning creators.

#### Scale–Productivity Gap

Compares creator scale with productivity indicators to identify categories where scale and content productivity do not move together.

#### Creator Opportunity Matrix

Compares audience engagement with earnings per million views to identify different engagement and monetization profiles.

#### Creator Survival / Maturity Distribution

Analyzes burnout risk across different channel-age groups.

#### Creator Maturity Analysis

Examines how average earnings and engagement change as channels become older.

#### Creator Economy Concentration

Compares subscriber share and expected earnings share across different creator size tiers.

### Dashboard B Purpose

Dashboard B moves from:

**"What is happening?"**

towards:

**"Why is it happening, where are the opportunities, and what decisions could be made from it?"**

---

# 🗂️ Dataset

The dataset contains information about YouTube channels including:

* Rank
* YouTuber
* Subscribers
* Video Views
* Category
* Channel Title
* Uploads
* Country
* Channel Type
* Video View Rank
* Country Rank
* Channel Type Rank
* Recent 30-Day Video Views
* Lowest Monthly Earnings
* Highest Monthly Earnings
* Lowest Yearly Earnings
* Highest Yearly Earnings
* Recent 30-Day Subscriber Growth
* Channel Creation Date
* Population
* Unemployment Rate
* Urban Population
* Upload Frequency
* Views per Upload
* Subscribers per Upload
* Subscriber-to-View Ratio
* Earnings per Million Views
* Views per Subscriber
* Channel Age
* Monthly Expected Earnings
* Yearly Expected Earnings
* Engagement Rate
* Burnout Risk
* Channel Size Tier
* Estimated Yearly Earnings

---

# 🧮 Key Calculated Metrics

Additional metrics were created from the original dataset to make the analysis more useful for business decisions.

### Estimated Yearly Earnings

```text
(lowest_yearly_earnings + highest_yearly_earnings) / 2
```

### Monthly Expected Earnings

```text
highest_monthly_earnings - lowest_monthly_earnings
```

### Yearly Expected Earnings

```text
highest_yearly_earnings - lowest_yearly_earnings
```

### Views per Upload

```text
video_views / uploads
```

### Subscribers per Upload

```text
subscribers / uploads
```

### Subscriber-to-View Ratio

```text
subscribers / video_views
```

### Earnings per Million Views

Used to compare monetization efficiency between creators and categories.

### Channel Age

Calculated using the channel creation date.

---

# 🔎 Business Questions

The current analysis is built around questions such as:

1. Which categories have the highest earning potential?
2. Which categories monetize views most efficiently?
3. Which countries have the largest creator audiences?
4. How has creator participation changed over time?
5. Which creator size tiers are generating recent subscriber growth?
6. How concentrated are creator earnings?
7. Which categories have the largest gap between estimated earnings and maximum potential?
8. How does creator age relate to earnings and engagement?
9. How does burnout risk change across creator maturity?
10. Does creator scale always translate into better productivity?

---

# 💡 Initial Insights

The current dashboards highlight several patterns that require deeper investigation:

* Creator subscribers and earnings are heavily concentrated among larger creators.
* Subscriber concentration and earnings concentration are not necessarily identical.
* Monetization efficiency varies significantly between content categories.
* High audience engagement does not automatically mean high monetization efficiency.
* Some categories show a much larger gap between estimated earnings and their maximum potential.
* Creator maturity is associated with changes in earnings and engagement.
* Burnout risk varies across different stages of the creator lifecycle.
* Creator scale and content productivity can move in different directions.

These are initial analytical findings. The final business report will validate them further before turning them into recommendations.

---

# 🧠 Business Insight Framework

The final analysis will not stop at describing charts.

Each major finding will follow:

```text
Finding
   ↓
Supporting Data
   ↓
Business Impact
   ↓
Recommendation
```

This will help convert the project from a visualization exercise into a decision-making case study.

---

# 🎯 Potential Business Applications

The analysis can be useful for different stakeholders.

### New Creators

* Category selection
* Content strategy
* Upload strategy
* Monetization planning

### Existing Creators

* Growth analysis
* Audience engagement
* Content productivity
* Revenue optimization

### Creator Managers / Agencies

* Creator identification
* Segment targeting
* Growth opportunity analysis
* Risk monitoring

### Brands

* Category selection
* Audience quality analysis
* Creator-market evaluation

### Creator Platforms

* Creator growth analysis
* Market opportunity identification
* Creator sustainability analysis

---

# 🛠️ Tools & Skills

* Microsoft Excel
* Data Cleaning
* Data Transformation
* Data Analysis
* Business Intelligence
* KPI Development
* Dashboard Design
* Calculated Metrics
* Data Storytelling
* Business Decision Analysis

---

# 📁 Project Structure

```text
Creator-Economy-Intelligence/
│
├── Data/
│   ├── Raw/
│   └── Processed/
│
├── Dashboard/
│   ├── Dashboard-A-Executive-Overview/
│   └── Dashboard-B-Strategy-Decision-Intelligence/
│
├── Report/
│   └── Business-Insights-Report/
│
├── Screenshots/
│   ├── Dashboard-A.png
│   └── Dashboard-B.png
│
├── Documentation/
│   ├── Data-Dictionary
│   └── Metric-Definitions
│
└── README.md
```

---

# 🚧 Current Project Status

**Status: In Progress**

### Completed

* [x] Dataset preparation
* [x] Data cleaning and transformation
* [x] Derived analytical metrics
* [x] Dashboard A — Executive Overview
* [x] Dashboard B — Creator Strategy & Decision Intelligence
* [x] Initial business analysis
* [x] Initial strategic insights

### Planned

* [ ] Detailed business insights report
* [ ] Final recommendations
* [ ] Final validation of major findings
* [ ] Complete project documentation
* [ ] Full project walkthrough video

---

# 📋 Planned Final Report

The final report will organize the analysis around:

### Market

Where is the creator economy growing and how concentrated is it?

### Monetization

Which categories and creator segments have stronger earning potential?

### Audience

Which categories have stronger engagement and subscriber conversion?

### Growth

Which creators and creator segments are showing stronger momentum?

### Sustainability

Where does burnout risk appear across the creator lifecycle?

### Opportunity

Where are the biggest gaps between performance and potential?

### Recommendations

What should creators, agencies, brands or platforms do based on the findings?

---

# 🎥 Final Project Video

A complete YouTube case-study video will be created after the final report is completed.

The video will cover:

```text
Business Problem
      ↓
Dataset
      ↓
Data Preparation
      ↓
Calculated Metrics
      ↓
Dashboard A
      ↓
Dashboard B
      ↓
Key Findings
      ↓
Business Insights
      ↓
Recommendations
      ↓
Final Conclusion
```

The purpose of the video is to make the project understandable even to someone who has never seen the dataset or dashboards before.

The video will also be linked to my portfolio website.

---

# 🚀 Why This Project Is Part of My Portfolio

I don't want my portfolio to be limited to generic Data Analyst projects.

My longer-term goal is to work in **Creator, Gaming, Esports, YouTube and Digital Entertainment Analytics**.

Creators are businesses.

Their:

* Views represent attention
* Subscribers represent audience
* Engagement represents audience quality
* Content represents the product
* Monetization represents business value
* Growth represents momentum
* Burnout represents sustainability risk

This project is my first step toward analyzing that entire ecosystem from a business and data perspective.

The next projects will move deeper into **gaming creators, esports, gaming audiences, content performance and creator monetization**.

---

# 📌 Project Status

**Current Stage:** Dashboards + Initial Analysis

**Next Stage:** Business Insights Report + Recommendations

**Final Stage:** Complete Case Study Video + Portfolio Integration

---

## Author

**Mihir R. Vachhani**

Data Analytics | Business Intelligence | Creator & Gaming Analytics
