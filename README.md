# Zomato Analytics Dashboard

## Overview
This project involves the development of a **Zomato Analytics Dashboard** designed to provide actionable insights into food delivery performance, restaurant reviews, and customer preferences. The dashboard will help stakeholders track KPIs, visualize trends, and make data-driven decisions.

---

## Key Features
- **KPIs Tracking**: Monitor total orders, average delivery time, average order value, customer satisfaction, and discount utilization.
- **Interactive Visualizations**: 
  - Line charts for order trends.
  - Bar charts for delivery time analysis and top restaurants.
  - Pie charts for ratings distribution.
- **Dynamic Filters**: Filter data by date range, location, cuisine type, ratings, and discounts.
- **Data Sources**: Integrates with Zomato's orders, restaurants, and reviews datasets.

---

## Business Objectives
- Improve delivery operations by identifying bottlenecks.
- Enhance customer satisfaction through review analysis.
- Optimize marketing strategies using cuisine popularity trends.
- Support restaurant owners with performance metrics.

---

## Technical Details
### Data Sources
1. **Orders Dataset**: Includes `Order_ID`, `Customer_Name`, `Location`, `Order_Date`, `Delivery_Time`, etc.
2. **Restaurant Dataset**: Includes `Restaurant_Name`, `Location`, `Ratings`, `Cuisine`.
3. **Reviews Dataset**: Includes `Rating`, `Review_Text`, `Review_Date`.

### Tools & Technologies
- **Frontend**: Power BI (for visualizations).
- **Backend**: Data aggregation and validation scripts (Python/SQL optional).
- **Performance**: Optimized for datasets up to 1 million rows.

### Functional Requirements
| View Name                | Description                              | Key Columns                     |
|--------------------------|------------------------------------------|---------------------------------|
| Total Orders KPI         | Displays total orders placed.            | `Order_ID`, `Order_Date`        |
| Delivery Time Chart      | Analyzes delivery time by city.          | `Delivery_Time_Minutes`, `Location` |
| Cuisine Popularity Chart | Highlights top cuisines.                 | `Cuisine`, `Order_ID`           |

---

## Setup Instructions
1. **Prerequisites**:
   - Power BI Desktop installed.
   - Access to Zomato datasets (CSV/API).

2. **Steps**:
   - Clone this repository.
   - Open the Power BI file (`Zomato_Dashboard.pbix`).
   - Connect to the data sources (update paths if needed).
   - Refresh the dataset to load the latest data.

---

## Project Timeline
| Phase               | Estimated Duration |
|---------------------|--------------------|
| Requirement Gathering | 2 weeks           |
| Development         | 4 weeks            |
| Testing & Feedback  | 2 weeks            |
| Deployment          | 1 week             |

---

## Stakeholders
- **Business Analysts**: Analyze metrics.
- **Operations Team**: Monitor delivery efficiency.
- **Marketing Team**: Track customer trends.
- **Restaurant Owners**: Access feedback and performance data.

---

## Risks & Mitigation
| Risk                  | Mitigation Strategy                          |
|-----------------------|---------------------------------------------|
| Data inconsistency    | Implement validation rules during ETL.      |
| Slow dashboard loads  | Optimize Power BI models and use aggregations. |
| Scope creep           | Freeze requirements before development.     |

---

## Support
For questions or issues, contact:  
📧 [(jaytamkhane161@gmail.com)]  
🔗 [Project Wiki Link (if available)]
