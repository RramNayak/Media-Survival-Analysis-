# 📑 Media Analysis Project  

## 📌 Background & Overview  
The media industry is undergoing a rapid transformation post-COVID, with legacy print operations facing sharp declines in circulation and advertising revenue. Digital competitors have adapted quickly, leaving traditional players struggling with high wastage, inefficient circulation, and eroding advertiser confidence.  

This project was designed as a **business case analysis** to evaluate sales, revenue, and readiness data, uncover root causes of decline, and propose actionable solutions.  
The goal was to simulate a real-world analytics engagement where structured problem solving, technical data handling, and visualization come together to deliver **strategic recommendations**.  

---

## 🗂 Data Structure Overview  
The dataset consisted of six interconnected tables:  

- **fact_print_sales** → Monthly circulation, returns, and wastage data per city  
- **fact_ad_revenue** → Ad sales by category (FMCG, retail, classifieds, etc.) and city  
- **fact_city_readiness** → Internet penetration, digital adoption, literacy rates, etc.  
- **fact_digital_pilot** → Performance of e-paper pilot projects across cities  
- **dim_city** → Metadata for city names, zones, and populations  
- **dim_ad_category** → Classification of ad types for grouping  

These datasets were cleaned and joined to create a **unified reporting layer**.  

---

## ⚙️ Methodology – 3-Step Process  

### 1️⃣ Excel – Data Preparation  
- Imported raw data from multiple sheets  
- Cleaned & standardized data (columns, formats, missing values)  
- Created staging tables for consistency  
- Applied formulas: `VLOOKUP`, `XLOOKUP`, `SUMIFS`, yearly deltas  

### 2️⃣ SQL – Business Insights  
- Built queries to extract KPIs:  
  - YoY net circulation drop  
  - Top 3 cities with highest wastage  
  - Ad revenue decline by category & region  
  - Digital readiness score by city  
- Used CTEs for multi-step calculations  
- Structured output for **Tableau integration**  

### 3️⃣ Tableau – Visualization  
- Developed dashboards to highlight:  
  - Monthly circulation decline trends  
  - Wastage analysis (~36M copies wasted in 5 years)  
  - Digital readiness & survival index by city  
  - Advertiser confidence trends (FMCG & retail hit hardest)  

---

## 📊 Executive Summary  
The analysis confirmed that the company is operating at **~80% efficiency**, but hidden inefficiencies threaten long-term survival.  

**Key findings:**  
- 📉 Circulation halved in 5 years (1.2M → 560K daily copies)  
- 🗑 ~36M copies wasted across fragile markets (Jaipur & Varanasi)  
- 💸 Ad revenues sharply down, FMCG & retail categories hardest hit  
- ❌ 2021 e-paper pilot failed due to poor execution  
- 🌐 Cities like Kanpur & Lucknow show **high digital potential**  

---

## 🔎 Insights & Deep Dive  

### 📰 Print Operations  
- Wastage disproportionately high in Tier-2 cities  
- 5–10% cut in fragile markets could unlock significant savings  

### 📢 Advertising Revenue  
- Confidence eroding as circulation drops  
- Classified ads shifting to digital alternatives  

### 📍 Reader & Regional Dynamics  
- Regional strength in Tier-1 cities, but fragile Tier-2 markets drag margins  
- Loyal readers remain if subscription pricing is stable  

### 💻 Digital Readiness  
- Uneven internet penetration across regions  
- Pilot failure due to execution gaps, not lack of opportunity  

---

## 💡 Solutions & Recommendations  

### Phase 1 – Print Optimization & Cost Control  
- Reduce print volumes in fragile markets (Jaipur, Varanasi) by 5–10%  
- Optimize circulation routes & renegotiate supplier contracts  

### Phase 2 – Advertiser Confidence & Revenue Growth  
- Launch **hyperlocal ad bundles** to retain FMCG & retail  
- Provide **data-backed guarantees** to advertisers  

### Phase 3 – Reader Loyalty & Regional Strength  
- Protect subscription pricing in Tier-1 loyal cities  
- Offer targeted incentives to secure long-term readers  

### Phase 4 – Digital & Subscription Strategy  
- Relaunch e-paper in **digitally ready cities (Kanpur, Lucknow, Pune)**  
- Introduce affordable **lite subscription models**  
- Bundle with telecom operators & local apps  

### Phase 5 – Diversification & Partnerships  
- Partner with Indian apps (Pocket FM, Kuku FM, Lenskart) for cross-selling  
- Explore e-commerce tie-ups for monetization  

---

## ✅ Key Takeaways  
This project demonstrates **end-to-end analytics capability**:  

- 📊 **Excel** → Data cleaning & preparation  
- 💻 **SQL** → Query building & KPI extraction  
- 📈 **Tableau** → Interactive dashboards & visualization  
- 🧠 **Business Strategy** → Actionable recommendations  

---
