# i4x-CPM

## Project Overview
This project is a collaboration with UC San Diego Capital Project Management (CPM) to explore predictive cost and schedule modeling for future campus construction projects. CPM manages hundreds of projects with over a decade of historical monthly spending data. The long-term goal is to develop models that can estimate project duration and cash flow curves based on project size, type, and category.


## Data Description
**CPM Project Cost Data**
- One row per project
- Monthly dollar spend across multiple years
- Cumulative spending over time reflects project lifecycle


## Phase 1 
1. **Project Identification**
   - Extract project numbers 
   - Clean and standardize project names

2. **Project Completeness Assessment**
   - Detect projects that start near zero, ramp up, peak, and ramp down
   - Flag projects with missing data, gaps, or timing irregularities

3. **Cost-Based Categorization**
   - Initial size categories:
     - Large: > $70M
     - Small: $1M–$5M
     - Medium: Data-driven range between small and large
   - Recommend alternative thresholds based on observed distributions

4. **Summary Statistics**
   - Total number of projects
   - Counts by size category
   - Average, minimum, and maximum project cost
   - Average, minimum, and maximum project duration


## Next Steps (Phase 2 – Future Work)
- Incorporate detailed spending by category and sub-category
- Normalize and compare spending curves across project types
- Develop predictive models for project duration and cash flow shape

---

