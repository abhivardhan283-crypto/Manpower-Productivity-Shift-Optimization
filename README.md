# Manpower Productivity & Shift Optimization Analysis

## 📋 Project Overview
A comprehensive data analytics project that evaluates workforce productivity across different shifts and provides data-driven recommendations for optimal staffing strategies. This project is particularly relevant for Regional General Warehouse (RGW) roles and demonstrates operational excellence in manpower planning.

## 🎯 Business Problem
Organizations often struggle with inefficient shift staffing, leading to:
- Understaffing → Increased overtime costs and employee burnout
- Overstaffing → Reduced productivity and increased operational costs
- Inconsistent performance → Varying quality and efficiency across shifts
- Lack of data-driven insights → Subjective decision-making in staffing

## 📊 Key Objectives
1. **Analyze shift-wise productivity** across Morning, Afternoon, and Night shifts
2. **Identify staffing inefficiencies** (overstaffing/understaffing)
3. **Evaluate cost implications** of current staffing patterns
4. **Provide optimization recommendations** for shift rostering
5. **Calculate potential savings** from improved staffing strategies

## 📁 Dataset Structure
The simulated dataset contains 90 days (3 months) of shift performance data with the following features:

| Column | Description | Data Type |
|--------|-------------|-----------|
| Date | Date of the shift | Date (YYYY-MM-DD) |
| Shift | Shift type (Morning/Afternoon/Night) | Categorical |
| Staff_Count | Number of staff on duty | Integer |
| Shipments_Handled | Total shipments processed | Integer |
| Errors_Count | Number of errors recorded | Integer |
| Overtime_Hours | Total overtime hours worked | Float |
| Day_of_Week | Day name (Monday-Sunday) | Categorical |
| Month | Month number | Integer |
| Weekday | Day number (0-6) | Integer |

**Derived Metrics:**
- `Productivity`: Shipments_Handled / Staff_Count
- `Error_Rate`: Errors_Count / Shipments_Handled
- `Efficiency_Score`: Composite metric combining productivity and error rate
- 
## 📈 Analysis Framework

### 1. **Data Generation & Preparation**
- Simulates realistic shift performance data with 90 days of records
- Incorporates weekly patterns and shift-specific characteristics
- Calculates derived metrics for comprehensive analysis

### 2. **Comprehensive Analysis Modules**
1. **Shift-wise Performance Metrics**: Productivity, error rates, overtime
2. **Productivity Analysis**: Distribution and trends across shifts
3. **Error Rate Analysis**: Identification of high-error periods
4. **Overtime Analysis**: Correlation with staffing levels
5. **Staffing Efficiency**: Optimal vs. actual staffing gaps
6. **Day-wise Patterns**: Weekly performance variations
7. **Cost Analysis**: Regular, overtime, and error-related costs
8. **Optimization Opportunities**: Specific improvement areas

### 3. **Visualization Dashboard**
- 9 comprehensive charts providing holistic insights
- Interactive visualizations for trend analysis
- Comparative analysis across shifts and days
- Heatmaps for efficiency patterns

## 🔍 Key Insights & Findings

### Performance Patterns Identified:
1. **Shift Productivity Variations**:
   - Morning shift: Highest productivity (27.1 shipments/staff)
   - Night shift: Lowest productivity (19.8 shipments/staff)
   - 27% productivity gap between best and worst shifts

2. **Staffing Imbalances**:
   - Night shift consistently understaffed
   - Afternoon shift shows periodic overstaffing
   - 32% of shifts have staffing inefficiencies

3. **Cost Inefficiencies**:
   - Overtime costs peak on Mondays and Fridays
   - Error-related costs highest during Afternoon shift
   - Night shift has highest cost per shipment
