# Urban Tree Distribution & Air Quality Analysis in New York City (2015)

## 📌 Project Overview
This project explores the relationship between **urban tree distribution, species diversity, and air quality** across **New York City community districts** using interactive **Tableau visualizations**.

Rather than claiming causation, the goal is to uncover **spatial patterns and statistical associations** that can inform urban planning, environmental policy, and public health discussions. The analysis combines NYC’s Street Tree Census data with district-level air pollution metrics (PM2.5 and NO₂) to generate actionable insights through visual storytelling.


---

## Datasets Used

### 1️. NYC Street Tree Census (2015)
- **Source:** NYC Department of Parks & Recreation (NYC Open Data)
- **Records:** 683,788 street trees
- **Key Variables:**
  - Tree species, diameter (DBH), health status
  - Stewardship level
  - Stress indicators (e.g., stones, lights, grates)
  - Latitude & longitude

> Note: Dataset includes *street trees only* (not parks or private property)

---

### 2️. NYC Community Air Quality Dataset
- **Source:** NYC Department of Health & Mental Hygiene
- **Metrics:** PM2.5, NO₂ concentrations
- **Granularity:** Community District level
- **Records:** ~18,000 observations across years

---

## Data Preparation & Integration
- Spatial joins performed using **latitude/longitude mapping**
- Tree data aggregated to **Community Districts**
- Tree density normalized by district area
- Air quality metrics aligned using district identifiers
- All preprocessing performed prior to Tableau ingestion

---

## 📈 Key Visualizations & Insights

### Tree Distribution & Biodiversity
- **Tree density maps** reveal higher coverage in Queens and Brooklyn, lower density in Manhattan
- **Species diversity maps** show ecological resilience varies widely across districts
- **Top 10 species analysis** shows dominance of a few species (e.g., London planetree), indicating biodiversity risk

---

### Tree Health & Stewardship
- Trees with **active stewardship (1–2 stewards)** show higher proportions of “Good” health
- Higher-intensity stewardship groups, while fewer, show stronger proportional health outcomes
- Highlights importance of **community engagement** in urban forestry

---

### Environmental Stress Factors
- Over **21% of trees are affected by physical barriers** (stones around tree beds)
- Other common stressors include lights, trunk damage, and root obstruction
- Indicates infrastructure-related challenges to tree health

---

### Air Quality Patterns
- PM2.5 concentrations are higher near **industrial zones and traffic corridors**
- Cleaner air observed near parks and waterfront areas
- Spatial disparities align with known environmental justice concerns

---

## Key Takeaways
- Urban tree density and biodiversity vary significantly across NYC
- Tree stewardship is positively associated with better tree health
- Physical urban infrastructure is a major stressor for trees
- Higher tree diversity correlates with better air quality (association, not causation)
- Visualization is a powerful tool for revealing complex urban-environment relationships

---

## Repository Contents
- **Tableau Packaged Workbook (.twbx)** – interactive dashboards
- **Final Project Report (PDF)** – detailed methodology and analysis
- No code files are included; this repository emphasizes **visual analytics and data storytelling**

---

## Tools Used
- Tableau
- Spatial joins & geospatial mapping
- NYC Open Data
- Statistical regression (for validation)



It serves as a foundation for future causal analysis and urban sustainability research.
