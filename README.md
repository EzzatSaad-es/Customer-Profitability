# Sales Scorecard Dashboard

## Overview

A comprehensive sales performance monitoring dashboard providing real-time revenue tracking, team performance analysis, and industry margin insights. This project enables sales managers and executives to monitor revenue targets, track team performance across regions, analyze gross margins by industry, and identify growth opportunities through interactive scorecards and detailed analytics.

---

## Key Features

### 📊 Three Main Dashboards:

1. **Individual Scorecard (Annelie Zubar)**
   - Revenue performance status tracking
   - Customer count and acquisition metrics
   - Monthly revenue trends vs. budget
   - Regional revenue breakdown
   - YTD revenue and variance analysis
   - Filterable by individual team member

2. **Team Scorecard**
   - 83 total customers across team
   - 7 products in portfolio
   - 42.5% gross margin average
   - Team member performance comparison
   - Revenue variance trends by person
   - Geographic distribution analysis
   - Global map with revenue by state/region

3. **Industry Margin Analysis**
   - 80 customers across industries
   - 5 products in portfolio
   - 42.5% gross margin
   - Revenue and margin by business unit (BU)
   - Industry-specific performance metrics
   - Product revenue breakdown (Primus, Gladius, Sova)
   - Margin trends by team member

---

## Key Metrics Summary

| Metric | Value |
|--------|-------|
| Team Total Customers | 83 |
| Products Portfolio | 7 |
| Overall Gross Margin % | 42.5% |
| Revenue Status | Green (On Track) |
| Total Revenue by Month | $5M - $10M range |

---

## Regional Performance

### Total Revenue by Region (Team Level):
- **NORTH**: Largest market
- **EAST**: Secondary market
- **SOUTH**: Growing market (Red/Underperforming)
- **WEST**: Moderate performance
- **CENTRAL**: Smaller market (Yellow/Average)

### Team Member Distribution by Region:
- Andrew Ma
- Annelie Zubar
- Carlos Grilo
- Tina Lassila
- Valery Ushakov

---

## Monthly Revenue Trends

### Individual Performer (Annelie Zubar):
- Consistent performance $1.5M - $2M monthly
- Relatively stable revenue pattern
- Minimal variance from plan
- 16 customers managed

### Team Performance:
- Cumulative monthly range: $5M - $10M+
- Peak performance: September-October
- Variance to budget: -20% to +20%
- Seasonal patterns visible

---

## Industry Analysis

### Business Units Tracked:
1. **(Blank)** - Foundation revenue
2. **CPG** - Consumer Packaged Goods
3. **Distribution** - Wholesale/Distribution
4. **Energy** - Energy sector
5. **Federal-Civilian** - Government civilian
6. **Federal-DOD** - Department of Defense
7. **High Tech** - Technology sector
8. **Industrial** - Manufacturing
9. **Insurance** - Insurance industry
10. **Metals** - Metals & mining
11. **Oil & Gas** - Energy production
12. **Paper** - Paper & forest products
13. **Pharma** - Pharmaceutical
14. **Retail** - Retail sector
15. **Services** - Service industry
16. **Telecom** - Telecommunications
17. **Transportation** - Transportation
18. **Utilities** - Utility companies

---

## Product Performance

### Featured Products:
- **Primus** - Top performer (Teal/Primary)
- **Gladius** - Secondary revenue driver (Dark)
- **Sova** - Growing product (Yellow)
- **MI-72** - Specialty product
- **(Blank)** - Legacy products

### Revenue Distribution:
- Primus dominates overall revenue
- Gladius provides stable secondary revenue
- Sova showing growth trajectory
- Portfolio diversification across customer base

---

## Gross Margin Analysis

| Category | Margin % |
|----------|----------|
| Team Average | 42.5% |
| By Industry | Varies by sector |
| By Product | Varies by line |
| By Team Member | 30% - 70% range |

### Monthly Margin Trends:
- Seasonal variation: 30% - 100%+ range
- Peak margins in certain months
- Team member performance varies
- Product mix impacts overall margin

---

## Geographic Coverage

### Global Reach:
- North America primary market
- Europe secondary presence
- Asia emerging market
- South America presence
- Australia coverage
- Africa presence

### State-Level Distribution:
- Multiple states across North America
- Concentrated customer base in key regions
- Regional revenue allocation visible on maps

---

## Team Member Performance

### Individual Profiles:
1. **Andrew Ma** - Teal indicator
2. **Annelie Zubar** - Individual scorecard focus
3. **Carlos Grilo** - Orange trend line
4. **Tina Lassila** - Yellow trend line
5. **Valery Ushakov** - Dark/Gray trend line

### Performance Trends:
- Each member tracked separately
- Variance to budget by individual
- Monthly performance comparison
- Consistent performers identified

---

## System Requirements

- Microsoft Power BI Desktop 2.0 or later
- Power BI Service for cloud deployment
- Excel 2016+ for data export
- Minimum 4GB RAM
- 500MB free disk space

---

## Data Sources

- CRM system (customer records)
- Sales transaction database
- Revenue tracking systems
- Product catalog
- Industry classification system
- Geographic/regional database

---

## Project Structure

```
Sales-Scorecard-Dashboard/
├── dashboards/
│   ├── individual-scorecard.pbix
│   ├── team-scorecard.pbix
│   └── industry-margin-analysis.pbix
├── data/
│   ├── sales-data.xlsx
│   ├── customer-data.xlsx
│   ├── product-data.xlsx
│   ├── industry-data.xlsx
│   └── regional-data.xlsx
├── documentation/
│   ├── data-dictionary.md
│   ├── calculation-methods.md
│   └── team-structure.md
├── reports/
│   ├── weekly-summaries/
│   ├── monthly-reports/
│   └── quarterly-reviews/
├── README.md
└── LICENSE
```

---

## How to Use

1. **Individual Scorecard**: Select team member from dropdown to view personal metrics
2. **Team View**: Compare performance across all team members simultaneously
3. **Industry Analysis**: Filter by industry or business unit for sector-specific insights
4. **Regional Analysis**: Use map and region filters to analyze geographic performance
5. **Margin Analysis**: Review product and industry profitability metrics
6. **Trend Analysis**: Monitor revenue and margin trends over time
7. **Export Reports**: Generate performance reports for presentations

---

## Interactive Features

- **Team Member Selector**: Dropdown to choose individual or view team totals
- **Industry Filters**: Select specific business units or industries
- **Product Filters**: Focus on specific product lines
- **Date Range Selection**: Analyze specific periods or full year
- **Regional Filters**: Drill down by geographic location
- **Metric Toggles**: Switch between revenue, margin, and customer metrics

---

## Key Performance Indicators (KPIs)

**Revenue Status**: Green indicator = meeting targets

**Customer Count**: Total active customers by segment

**Product Portfolio**: Number of products per rep/team

**Gross Margin %**: Profitability metric by dimension

**Revenue Variance**: Deviation from planned targets

**Monthly Trends**: Revenue progression and seasonality

---

## Variance Analysis

- **Negative Variance**: Below plan performance
- **Positive Variance**: Above plan performance
- **Trend Lines**: Show deviation patterns over time
- **Color Coding**: Visual performance indicators

---

## Performance Optimization

- Use team member filters to reduce data volume
- Archive historical years separately
- Filter to specific industries for focused analysis
- Use region/state filters for geographic drill-down
- Refresh data during off-peak hours

---

## Troubleshooting

**Missing Team Members**
- Verify employee is active in system
- Check data source has latest employee records
- Confirm user permissions

**Revenue Data Not Updating**
- Refresh Power BI data model
- Verify sales transactions are posted
- Check data source connection

**Margin Calculations Incorrect**
- Verify cost data is properly recorded
- Check product cost definitions
- Review calculation formulas

**Slow Performance**
- Reduce date range
- Filter by specific dimensions
- Clear Power BI cache

---

## Contributing

We welcome contributions! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/enhancement`)
3. Commit changes (`git commit -m 'Add improvement'`)
4. Push to branch (`git push origin feature/enhancement`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## Connect With Us

- 💼 **LinkedIn**: [Connect on LinkedIn](https://www.linkedin.com/in/your-profile/)
- 🐙 **GitHub**: [Follow on GitHub](https://github.com/your-username)
- 📊 **Portfolio**: [View My Work](https://your-portfolio.com)

---

## Notes

- Individual scorecard displayed for Annelie Zubar (16 customers)
- Team scorecard consolidates all 5 sales representatives
- Industry analysis covers 18+ industry verticals
- Global coverage across multiple continents
- Monthly data granularity for trend analysis
- Real-time revenue status indicators
- Comprehensive margin analysis by multiple dimensions

---

**Last Updated: October 17, 2025**
