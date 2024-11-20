# **Steam Games Insights Dashboard - MongoDB Analysis and Managerial Insights**
![Game Insights Dashboard](https://github.com/user-attachments/assets/b9a00343-fa22-4b0a-a876-67c08d667052)



### **Unique Games (Top Left Card)**  
**Question**: How extensive is the gaming database used for analysis?  
**Insight**: The dataset contains **6,746 unique games**, showcasing a rich variety of titles to analyze gaming trends.

---

### **Average Game Price (Top Center Card)**  
**Question**: What is the typical price point for games in the market?  
**Insight**: The average game price is **$445.11**, indicating that premium-priced games dominate the dataset. This could also reflect the inclusion of expensive collector editions or bundled packages.

---

### **Total Number of Games (Top Right Card)**  
**Question**: How many games are analyzed in total, including all platforms?  
**Insight**: There are **21,000 games** across various platforms and configurations, providing a robust dataset for trend exploration.

---

### **Peak Game Prices (Top Right)**  
**Question**: What is the highest price point for games in the dataset?  
**Insight**: The peak price is **$999**, likely representing special editions or rare collector's items. Such data highlights the extreme pricing strategies in gaming.

---

### **Recommended Memory for Games**  
**Questions**: 
- How do memory requirements vary across operating systems (Windows, Linux, MacOS)?  
- Which OS demands the most memory for optimal performance?  

**Insights**:  
- **Windows**: Majority of games recommend **8 GB RAM**, reflecting modern gaming standards.  
- **Linux**: Games are mostly optimized for **4 GB RAM**, showcasing its lightweight gaming requirements.  
- **MacOS**: Most games recommend **8 GB RAM**, aligning closely with Windows.  

---

### **Minimum RAM Required for Games**  
**Questions**:  
- What are the minimum RAM requirements across different operating systems?  
- How accessible are games for devices with lower specifications?  

**Insights**:  
- **Linux**: A significant number of games can run with just **2 GB RAM**, highlighting its compatibility with low-spec devices.  
- **Windows**: Games generally require a minimum of **4 GB RAM**, suggesting moderate hardware requirements.  
- **MacOS**: Similar to Windows, most games require **4 GB RAM** as the baseline.  

---

### **Games Evolution: Yearly Price Trends**  
**Question**: How has the pricing of games evolved over the years?  
**Insight**: The chart shows a steady rise in game prices over time, with a sharp increase in recent years. This reflects the increasing development costs and inclusion of premium editions.

---

### **Yearly Average Game Price**  
**Question**: What are the yearly trends in average game pricing?  
**Insight**: The average price fluctuates, with peaks likely tied to the release of high-value games or bundles. The consistent rise reflects inflation and increasing production values.

---

### **Popular PEGI Tags**  
**Question**: What content descriptors are most common in games?  
**Insight**: Tags like "Violence" and "Blood" are frequent, emphasizing the popularity of action and mature-themed games. This indicates a target audience of older gamers.

---

### **Popular Tags**  
**Question**: What are the dominant themes or categories in gaming?  
**Insight**: "Multiplayer," "Action," and "Single-player" are the most frequent tags, highlighting the preference for both individual and group gameplay experiences.

---

### **Popularity in the Gaming World (Word Cloud)**  
**Question**: What themes or genres are most commonly associated with games?  
**Insight**: "Singleplayer" and "Simulation" stand out, showcasing the importance of immersive and individual gaming experiences.

---

### **Most Famous Developers (Word Cloud)**  
**Question**: Which developers have a significant presence in the gaming industry?  
**Insight**: "Paradox Development Studio" and "Dovetail Games" are prominent, reflecting their consistent output and popularity among gamers.

---

### **Famous PC Games (Word Cloud)**  
**Question**: Which games are widely recognized in the dataset?  
**Insight**: Titles like "Conan Exiles" and "Path of Exile" dominate, suggesting their enduring popularity among PC gamers.

# Learning 
---

#### **Objective**  
The goal of this project was to create an interactive dashboard using data stored in MongoDB, focusing on exploring key trends and insights in the gaming industry. The dashboard visualizes aspects such as game pricing, memory requirements, developer popularity, and more.

---

#### **Learnings from Creating the MongoDB Dashboard**

1. **Data Structuring and Modeling**  
   - Learned the importance of structuring data in a NoSQL database like MongoDB to handle a diverse dataset effectively.  
   - Designed collections with appropriate schemas to manage game data such as prices, system requirements, developers, and tags.

2. **Data Aggregation**  
   - Gained hands-on experience using MongoDB's aggregation pipeline to compute metrics like average prices, count of unique games, and distribution of RAM requirements.  
   - Leveraged `$group`, `$match`, and `$sort` stages to process and summarize data efficiently.

3. **Real-Time Query Execution**  
   - Implemented queries for retrieving specific data points (e.g., minimum/maximum game prices, most popular developers).  
   - Enhanced skills in crafting flexible and optimized queries to ensure rapid dashboard rendering.

4. **Data Cleaning and Preparation**  
   - Addressed inconsistencies and missing values in raw data while importing into MongoDB.  
   - Applied data transformation techniques such as standardizing RAM values and price formatting.

5. **Integration with Visualization Tools**  
   - Connected MongoDB with Python-based frameworks for creating visually appealing dashboards.  
   - Improved skills in linking backend data processing with frontend visualizations.

6. **Performance Optimization**  
   - Learned to index key fields in MongoDB (e.g., price, platform, RAM) to improve query performance.  
   - Reduced computation time for large datasets by caching frequently accessed results.

---

#### **Managerial Insights Gained**

1. **Market Segmentation**  
   - **Insight**: The breakdown of minimum and recommended RAM requirements highlights clear segmentation between casual gamers (low RAM) and serious gamers (high RAM).  
   - **Decision**: Companies can develop games catering to both budget and high-end gaming systems, maximizing audience reach.

2. **Pricing Strategies**  
   - **Insight**: The average price and peak pricing indicate a wide variance, suggesting opportunities for tiered pricing models (e.g., basic, premium, collector editions).  
   - **Decision**: Introduce diverse pricing tiers to appeal to different customer segments.

3. **Trends Over Time**  
   - **Insight**: Rising game prices and increasing memory requirements show a shift towards higher-quality and resource-intensive games.  
   - **Decision**: Invest in advanced technologies to meet market expectations for high-quality graphics and gameplay.

4. **Content Focus**  
   - **Insight**: Popular tags like "Multiplayer" and "Singleplayer" highlight the importance of catering to both social and solo gaming preferences.  
   - **Decision**: Prioritize game designs that allow flexibility, such as hybrid modes supporting both single and multiplayer options.

5. **Developer Dominance**  
   - **Insight**: Certain developers dominate the gaming landscape, indicating their strong market presence and loyal customer base.  
   - **Decision**: Smaller developers can consider partnerships with these leaders, while established developers can diversify their portfolio to maintain their lead.

6. **Platform-Specific Optimization**  
   - **Insight**: Memory and system requirements differ significantly between platforms.  
   - **Decision**: Optimize games specifically for Linux, MacOS, and Windows to ensure a seamless experience across platforms.

7. **Affordability Analysis**  
   - **Insight**: A high average price suggests limited accessibility for budget-conscious gamers.  
   - **Decision**: Consider releasing affordable versions of games to tap into untapped market segments.

8. **Regional and Content Regulations**  
   - **Insight**: Popular PEGI tags like "Violence" and "Blood" suggest the importance of adhering to content rating systems.  
   - **Decision**: Ensure compliance with global and regional content regulations to avoid legal challenges.

---

#### **Future Scope**

1. **Enhanced Data Exploration**  
   - Expand the dashboard to include insights on regional trends and game genres by geography.
   
2. **Predictive Analytics**  
   - Use machine learning algorithms to predict future trends in game pricing and memory requirements.

3. **User-Centric Enhancements**  
   - Add filters for real-time exploration of data by users, such as filtering by year, genre, or platform.

4. **Monetization Opportunities**  
   - Integrate sales data to analyze the relationship between pricing, platform, and profitability.

---

