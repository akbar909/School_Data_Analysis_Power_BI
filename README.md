# School Data Analysis Power BI

## Overview

This repository contains a comprehensive Power BI solution for analyzing and visualizing school performance data. The dashboard provides educational institutions with actionable insights into student performance, enrollment trends, and academic metrics through advanced data analytics and interactive visualizations.

## Project Objectives

- **Performance Monitoring**: Track student academic performance across subjects and grade levels
- **Trend Analysis**: Identify patterns in enrollment, attendance, and achievement metrics
- **Data-Driven Decision Making**: Empower educators and administrators with insights to improve educational outcomes
- **Stakeholder Reporting**: Generate comprehensive reports for administrators, teachers, and parents
- **Predictive Analytics**: Utilize historical data to forecast future trends and identify at-risk students

## Key Features

### 📊 Interactive Dashboards
- Student performance analytics by subject and semester
- Class-wise and school-wide comparative analysis
- Attendance and enrollment trend visualization
- Grade distribution and achievement patterns

### 📈 Data Insights
- Real-time KPIs for key academic metrics
- Historical trend analysis
- Benchmarking against institutional targets
- Demographic breakdowns and diversity analysis

### 📋 Reporting Capabilities
- Customizable reports for different stakeholder groups
- Automated drill-down functionality
- Export options for further analysis
- Performance scorecards

## Data Sources

The analysis integrates data from:
- Student Information System (SIS)
- Academic records and grades
- Attendance logs
- Enrollment databases
- Assessment scores

## Dashboard Overview

### 1. National Student Analytics Dashboard

This comprehensive dashboard provides an overview of student distribution across Australia with the following key metrics:

#### Key Metrics:
- **Total Students**: 73M (as of 2018)
- **Year Range**: 2009-2018 analysis period

#### Visualizations:

**Students by Sector**
- Government: 48M (65.3%)
- Catholic: 15M (20.3%)
- Independent: 11M (14.2%)

**Geographic Distribution**
- Interactive map showing Students by States and Country
- Regional breakdown across all Australian states

**Students by State**
- NSW: 23.3M (highest enrollment)
- VIC: 19.0M
- QLD: 15.4M
- WA: 7.8M
- SA: 5.3M
- TAS: 1.6M
- ACT: 1.3M
- NT: 0.8M

**Students by Year and Sector**
- Trend analysis from 2009-2018
- Comparative growth across Government, Catholic, and Independent sectors
- Stacked bar charts showing sector distribution over time

**Students by State and School Level**
- Primary vs Secondary distribution by state
- Detailed breakdown for NSW, VIC, QLD, WA, SA, TAS, ACT, NT

**Students by Sector and Gender**
- Gender distribution: Female (~50%) and Male (~50%) across all sectors
- Analysis by Government, Catholic, and Independent sectors
- Demonstrates gender balance across educational sectors

**Data Summary Table**
Comprehensive year-by-year breakdown (2009-2018) showing:
- Government students and % of total
- Catholic students and % of total
- Independent students and % of total
- Total student population and percentages

### 2. Queensland (QLD) Education Analytics Dashboard

Focused analysis on Queensland state with staff and sector-specific metrics:

#### Key Metrics:
- **Total Students**: Analyzed across the state
- **Total Staff**: 1.1M
- **Students:Teachers Ratio**: 28.31

#### Visualizations:

**Staff by Sector and Gender**
- Government: 78.2% Female, 21.8% Male
- Catholic: 74.01% Female, 25.99% Male
- Independent: 67.12% Female, 32.88% Male

**Staff by Function**
- Teaching staff: 0.54M (largest group)
- Non-teaching staff: 0.25M
- Administrative & clerical: 0.19M
- Building operations, grounds: 0.03M
- Specialist support staff: 0.03M

**Staff by Year and Sector** (2009-2018)
- Trend analysis showing Government sector dominance
- Growth patterns in Catholic and Independent sectors

**Students, Staff and Schools by School Level, Sector and Year**
- Bubble chart showing relationships between students, schools, and sectors
- Time series analysis from 2009-2018
- Primary vs Secondary distribution

**Students:Teachers by Year and Sector**
- Government sector ratio trends (2009-2018)
- Catholic sector ratio trends
- Independent sector ratio trends
- Shows overall declining ratio trend, indicating increased teacher-to-student attention

## Visualizations Included

- **Pie Charts**: Sector and demographic distribution analysis
- **Geographic Maps**: Regional student distribution across Australian states
- **Bar Charts**: Comparative metrics across sectors, states, and gender
- **Stacked Bar Charts**: Year-over-year trend analysis by sector
- **Bubble Charts**: Multi-dimensional relationship visualization
- **Line Charts**: Historical trend analysis for students and staff ratios
- **Tables**: Detailed year-by-year statistical summaries
- **Interactive Filters**: Year, sector, and state-level filtering capabilities

## Technical Stack

- **Power BI Desktop**: Data modeling and visualization
- **Power Query**: Data transformation and cleaning
- **DAX (Data Analysis Expressions)**: Custom measures and calculations
- **MySQL/Excel**: Data sources

## Getting Started

### Prerequisites
- Power BI Desktop (Latest version)
- Access to school data sources
- Basic understanding of Power BI concepts

### Installation

1. Clone this repository
2. Open the Power BI file (.pbix) in Power BI Desktop
3. Configure data connections to your school's data sources
4. Refresh data to load the latest metrics
5. Publish to Power BI Service for sharing and collaboration

## Usage

### For Administrators
- Monitor overall school performance
- Track enrollment trends
- Generate compliance reports
- Analyze resource allocation effectiveness

### For Teachers
- Review class and individual student performance
- Identify students needing additional support
- Compare performance across teaching methods
- Track progress toward learning objectives

### For Parents
- Access anonymized student performance metrics
- Track attendance records
- Monitor grade trends
- Understand academic standing

## Key Metrics

- **Student Achievement Rate**: Percentage of students meeting grade-level standards
- **Attendance Rate**: Average daily attendance percentage
- **Graduation Rate**: Percentage of students completing grade level/program
- **Subject Performance**: Average scores by subject area
- **Grade Distribution**: Breakdown of letter grades
- **Enrollment Trends**: Student population changes over time

## Data Refresh Schedule

Data is automatically refreshed on a scheduled basis to ensure up-to-date analytics. Check your Power BI Service settings for refresh frequency.

## Best Practices

1. **Data Privacy**: Ensure all student data is anonymized and handled according to FERPA guidelines
2. **Regular Updates**: Keep data sources current for accurate insights
3. **Stakeholder Training**: Provide training to end-users on dashboard navigation
4. **Documentation**: Maintain clear documentation of data definitions and calculations
5. **Validation**: Regularly validate data accuracy against source systems

## Troubleshooting

### Data Not Loading
- Verify data source connections
- Check network connectivity
- Ensure credentials are current
- Review Power Query transformation steps

### Performance Issues
- Reduce data volume using date filters
- Optimize DAX formulas
- Consider aggregating large datasets
