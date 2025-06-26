# AgriInsights_Pro_1
# AgriInsights-Dashboard

## Recommended Structure and Order

### 1. Project Title / Headline  
🌾 **AgriInsights: Agricultural Analytics Dashboard**  
A robust, interactive Power BI dashboard designed to explore seasonal agricultural data—focusing on rainfall, temperature, humidity, and yield patterns across regions using a modern data stack built on AWS and Snowflake.

---

### 2. Short Description / Purpose  
AgriInsights is a cloud-powered analytics dashboard that transforms and visualizes agricultural data using AWS S3, Snowflake, and Power BI. It helps users analyze key climatic and agricultural factors across multiple seasons and locations for better planning and decision-making.

---

### 3. Tech Stack  
The dashboard was built using the following tools and technologies:<br>
• 🟡 **AWS S3** – Used to store the raw agricultural dataset (`data_season`).<br>
• ❄️ **Snowflake** – Used for data transformation, staging, and building data pipelines.<br>
• 🔐 **Integration Roles & Stages** – Created in Snowflake to securely connect AWS and Snowflake.<br>
• 📊 **Power BI Desktop** – Main platform for developing interactive visualizations.<br>
• 🧠 **DAX (Data Analysis Expressions)** – Used for dynamic calculations and custom logic (e.g., Rainfall Grouping).<br>
• 📝 **Data Modeling in Snowflake** – Added computed columns and cleaned data within Snowflake.<br>
• 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews.

---

### 4. Data Source  
**Source:** Custom agricultural dataset titled `data_season` stored in an AWS S3 bucket.

The dataset includes the following columns:<br>
• Year<br>
• Location<br>
• Rainfall<br>
• Temperature<br>
• Type of Soil<br>
• Method of Irrigation<br>
• Humidity<br>
• Crop Prices<br>
• Season<br>
• Area<br>

Additionally, a new column called **Rainfall Group** was added based on rainfall values to categorize them as *Low*, *Medium*, or *High*.

---

### 5. Features / Highlights  

• **Business Problem**  
Agricultural stakeholders face challenges in visualizing and understanding climatic trends like rainfall and temperature variations over time. This results in inefficiencies in crop planning, irrigation strategy, and yield prediction.

Key questions such as:  
- How has rainfall varied across different years and locations?  
- What impact does temperature or humidity have on crop yields?  
- Are there consistent seasonal trends in specific regions?  

… are difficult to answer with unstructured or static data.

---

• **Goal of the Dashboard**  
To deliver a cloud-integrated, data-driven tool that:  
- Helps visualize seasonal patterns in agriculture.  
- Aids in strategic decision-making for farmers, researchers, and government bodies.  
- Enables detailed breakdowns of weather trends and their correlation with yield and pricing.

---

• **Walkthrough of Key Visuals**  
- **📄 Page 1: Rainfall Analysis**  
  Shows average rainfall by year, season, crop, and location. Includes Rainfall Group filtering.

- **📄 Page 2: Temperature Analysis**  
  Tracks seasonal and yearly temperature patterns by region.

- **📄 Page 3: Humidity Analysis**  
  Displays humidity variation by season and its correlation with other factors.

- **📄 Page 4: Yield Analysis**  
  Analyzes area, crop prices, and rainfall to explore patterns in agricultural output.

---

• **Business Impact & Insights**  
- **Climate Adaptation**: Helps identify drought-prone or flood-sensitive areas.  
- **Resource Planning**: Suggests where irrigation systems need enhancement.  
- **Yield Optimization**: Links climate factors to crop performance.  
- **Government & Policy Use**: Enables data-backed agricultural strategies and subsidies.

---

### 6. Screenshots / Demos  
Show what the dashboard looks like.  
- ![Rainfall Analysis](https://github.com/sainath-raja/AgriInsights_Pro_1/blob/main/Rainfall_Analysis.png)  
- ![Temperature Trends](https://github.com/sainath-raja/AgriInsights_Pro_1/blob/main/Temp_Analysis.png)  
- ![Humidity Overview](https://github.com/sainath-raja/AgriInsights_Pro_1/blob/main/Humidity_Analysis.png) 
- ![Yield Insight](https://github.com/sainath-raja/AgriInsights_Pro_1/blob/main/Yeild%20Analysis.png)
