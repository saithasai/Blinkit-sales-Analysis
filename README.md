# Blinkit-sales-Analysis   

## Problem Statement
BlinkIt, India's leading last-minute delivery app, needed comprehensive business intelligence to:
- Track multi-dimensional performance across revenue, customers, inventory, and marketing
- Monitor operational metrics including stock management and customer satisfaction
- Analyze growth trends and identify optimization opportunities
- Provide stakeholder-ready insights without requiring technical intervention

## Objective
Develop a fully automated, interactive Power BI dashboard that integrates data collection, cleaning, analysis, and visualization to enable data-driven decision making across all business functions.

## Tools & Technologies
- **Microsoft Power BI**: Data modeling, DAX calculations, interactive visualizations, Power BI Service
- **Power Query**: Data transformation and ETL processes
- **Data Processing**: Automated data refresh, data modeling
- **Visualization**: Interactive charts, KPI cards, dynamic filtering, drill-through capabilities
- **Dashboard Design**: Multi-page navigation, responsive layouts
- **Analytics**: Advanced analytics, trend analysis, segmentation, performance tracking
- **Filter panel**: year,month,product name, customer name,custoemr segment,quantity vs revenue, time (month,month-yr,week,day),monthly comparison,a toggle switch for condition(enable,disable)

## Methodology
1. **Data Integration**: Consolidated data from multiple business functions using Power Query
2. **Dashboard Architecture**: Created 7 specialized pages (Home, Overview, Sales, Customer, Feedback, Inventory, Marketing)
3. **Data Modeling**: Established relationships and calculated columns using DAX
4. **KPI Development**: Built custom measures for each business area
5. **Automation**: Implemented scheduled data refresh and real-time updates
6. **Visualization**: Designed interactive charts with drill-down capabilities
7. **User Experience**: Created intuitive navigation with bookmarks and page filters

## Dashboard Components
- **7 Interactive Pages**: Comprehensive business coverage with seamless navigation
- **25+ KPI Metrics**: Real-time performance monitoring with custom DAX measures
- **Multiple Visualization Types**: Trend lines, bar charts, donut charts, KPI cards
- **Dynamic Filtering**: Area, product, time-period selections with cross-filtering
- **Automated Refresh**: Scheduled data updates from multiple data sources
- **Mobile-Responsive**: Optimized layouts for desktop, tablet, and mobile viewing
- **Drill-Through Actions**: Deep-dive capabilities for detailed analysis
  
***Sale Overview***  
<img width="758" alt="Sale Overview" src="https://github.com/user-attachments/assets/8601386c-6cab-49c8-adb5-32c3ca49e054" />

- The business saw good growth in early 2024, especially in March.  
- From mid-year onward, performance was flat or declining.  
- End of year (Nov-Dec) is a critical concern due to major drops in sales compared to 2023.

- Top area - Sambalpur, Thiruvananthapuram, Nandyal, Gandhinagar,Orai  
- Top products - Vitamins,Cough Syrups, Pet treats, Cat food, Bread
- Payment Methods: Card > Cash > UPI > Wallet   
- Customer segment: Regular > Premium > Inactive > New  

***Customer***  
<img width="758" alt="Customer" src="https://github.com/user-attachments/assets/72a3d992-ec4c-467f-af1b-c307334b786d" />

- Revenue in 2024 was ₹2.51 million, up from ₹2.46 million in 2023 — a year-over-year growth of 2.08%. 🔼  
- Customer count increased from 1,573 in 2023 to 1,612 in 2024 — a modest growth. ➡️  
- 100% of 2024 customers are repeat/multiple-time customers   
- 2024 saw a net gain of 39 customers (599 new, 560 lost).    
- New customer revenue: ₹0.91M | Lost customer revenue: ₹0.859M. ✅ Net positive.

- Early and Mid-Year Strength: Business retained more customers and grew in 2024 vs. 2023 in the first 8 months.  
- Late-Year Drop: Growth dips sharply in Nov–Dec, indicating a need to:  Investigate churn or customer inactivity.  
- Reevaluate year-end campaigns or product/service delivery.   
- High Repeat Rate: Combined with the insight that 100% of 2024 customers are repeat buyers, this chart shows customer loyalty, though new acquisition may have slowed toward year-end.   

- Top customers by revenue in 2024
- Highest: Odika Kannan. with ₹10.5K

***Feedback***  
<img width="758" alt="Feedback" src="https://github.com/user-attachments/assets/715d4b7a-162a-41f4-a447-2557450272b0" />

- 4.03% growth, 5.12K feedback in 2024 vs 4.92K in 2023  
- Feedback evenly split across 4 categories: Delivery, Customer Service, Product Quality, App Experience (each ~25%)  
- Sentiment: 35% Positive, 33% Neutral, rest Negative   
- Most feedback is 3-4 stars (1398 and 1708 respectively) and 816 five-star ratings  
- Concerning: 1078 one-to-two star ratings combined  
- Shows individual feedback entries, mostly positive sentiment with 4-5 star ratings and "Will definitely order again" comments.

***Inventory***  
<img width="758" alt="Inventory" src="https://github.com/user-attachments/assets/ab8a862e-8c4f-4867-9c81-1e0da4239b75" />

The dashboard shows seasonal inventory patterns with strong availability but declining year-end trends.
- 4.03% growth: 5.12K (2024) vs 4.92K (2023) YTD
- **Total Received Stock**: 29.9K
- **Available Stock**: 19.9K (66.43% - green gauge)
- **Damaged Stock**: 1.1K (3.71% - red gauge)
- **Stock Movements**: 33.6%
- **Stock Received**: 28.8K

- **Stock Received** (yellow): Peaked at 3.5K in Sep-Oct, dropped to 2.3K by Dec
- **Available Stock** (gray): Rose from 1.8K to peak 2.5K mid-year, declined to 1.7K
- **Period Value** (green): Gradual increase from 0.5K to 1.1K
- **Damaged Stock** (black): Remained consistently low around 0.2-0.5K

- Moderate growth (4%)
- Good availability rate (66%)
- Low damage rate (3.7%)
- Seasonal pattern with Sep-Oct peak, year-end decline
- Stock levels dropping in Q4 - potential restocking needed

***Marketing***  
<img width="758" alt="Marketing" src="https://github.com/user-attachments/assets/a3575bd1-69ee-452e-9d4f-cf51312a0d53" />   

- 4.03% growth: 5.12K (2024) vs 4.92K (2023) YTD

**Key Marketing Metrics:**
- **Clicks**: 2.97M
- **Conversions**: 298.04K 
- **Impressions**: 29.49M
- **Revenue**: ₹32.19M
- **Spend**: ₹16.32M

- **Impressions** (green): Peaked at 3M+ in May-Jul, declined to ~1.7M by Dec
- **Revenue Generated** (gray): Strong performance Mar-Oct (~3M+), dropped to ~2M in Nov-Dec
- **Spend** (blue): Steady at ~1.8M most of year, slight decline to ~1M in Dec
- **Clicks** (yellow): Consistent low performance around 0.2M throughout
- **Conversions** (black): Minimal, staying near baseline
- **ROAS** (navy): Maintained around 1.8M level most of year

- Strong ROI: ₹32.19M revenue from ₹16.32M spend (2:1 ratio)
- Seasonal pattern: Peak performance mid-year, Q4 decline
- High impression volume (29.5M) but low click-through
- Conversion optimization needed (298K from 2.97M clicks = ~10% conversion rate)
- The dashboard shows profitable marketing with room to improve click-through and conversion rates.

## Key Findings

### Business Performance
- **Strong Growth**: 72.94% revenue increase demonstrates robust business expansion
- **Customer Acquisition**: Successfully growing customer base across all segments
- **Marketing Efficiency**: Strong ROI of 1.97x on marketing spend

### Operational Insights
- **Inventory Challenges**: 3.51% damaged stock requires attention
- **Geographic Concentration**: Performance varies significantly by area
- **Customer Satisfaction**: Generally positive with room for improvement in lower ratings

### Strategic Opportunities
- **Stock Management**: Optimize inventory to reduce damage rates
- **Geographic Expansion**: Leverage top-performing areas for growth strategies
- **Customer Experience**: Address feedback in delivery and product quality categories
- **Marketing Optimization**: Scale successful campaigns with proven ROI

## Impact & Value
- **Operational Efficiency**: Automated reporting eliminates manual processes
- **Strategic Decision Making**: Data-driven insights across all business functions
- **Performance Monitoring**: Real-time KPI tracking with scheduled refresh
- **Stakeholder Enablement**: Self-service analytics through Power BI Service
- **Scalable Solution**: Cloud-based framework adaptable to business growth
- **Advanced Analytics**: DAX-powered calculations for complex business metrics

 👉[Live dashboard](https://app.powerbi.com/view?r=eyJrIjoiMTU0NTU2MmItOGNmYS00ZTQ0LWIwZDMtYmNkNzNhN2JhY2E2IiwidCI6IjNiN2YyODNhLWI1NzAtNGE5NS04ZTFmLTgwNzAwODAzODEwOSJ9) 
