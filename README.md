# Department Analytics Dashboard

## Project Overview

This project provides a comprehensive data analytics dashboard built using **Grafana**, designed to support principals and management in decision-making. The dashboard analyzes departmental performance, student engagement, recruitment, innovation, and resource utilization using a **synthetic dataset**.

---

## Dataset

- Source: `Augmented_500_Final_Fixed.csv` (**synthetic data**)
- Main columns:
  - `department_name`
  - `event_year`
  - `total_students`
  - `total_teams`
  - `active_participants`
  - `total_offers`
  - `partnership_count`
  - `recruiter_visits`
  - `total_faculty`
  - `active_mentors`
  - `total_hackathon_cost`
  - `innovation_score_avg`
  - `departmental_performance_index_dpi`
  - `institutional_roi`
- Data is aggregated by department and year through the dashboard panels.

---

## Dashboard Visuals

1. **Average Innovation Score by Department**  
   - Bar chart of average innovation scores across departments.

2. **Industry Engagement by Department**  
   - Stacked bar chart for recruiter visits and partnership counts per department.

3. **Distribution of Active Participants by Department**  
   - Pie/donut chart showing department-wise participation share.

4. **Hackathon Investment vs Innovation Score**  
   - Scatter plot of total hackathon cost versus average innovation score by department.

5. **Placement Success Rate by Department and Year**  
   - Table panel summarizing students, offers, and placement ratios per department/year.

6. **Total Faculty & Active Mentors by Department**  
   - Bar chart showing faculty and mentor distribution.

7. **KPI Stat Panels**  
   - Big number tiles indicating total students, total offers, average DPI, and institutional ROI.

8. **Year-wise Student and Offer Trends**  
   - Horizontal bar chart for year-on-year student and offer numbers.

9. **Active Participants by Department**  
   - Bar chart ranking departments by total active participants.

10. **Top Departments: Students & Offers Comparison**  
    - Bar chart comparing student and offer counts for top-5 departments.

11. **Recruiter Visits by Department**  
    - Table panel listing total recruiter visits per department.

---

## Usage

- Import the included dashboard JSON file(s) into **Grafana**.
- Ensure the data source is set up to use a PostgreSQL database with the provided synthetic dataset.
- Use the dashboard visuals to interpret institutional performance, engagement, and resource allocation.
- Customize queries or panels as needed for additional KPIs.

---

## Running Locally

1. Clone this repository.
2. Load `Augmented_500_Final_Fixed.csv` into your PostgreSQL database.
3. Set up Grafana and configure the data source to point to your PostgreSQL database.
4. Import the dashboard JSON file(s) through Grafana’s UI.
5. Adjust visualizations and queries for your environment or local schema.

---

## Notes

- This project uses a **synthetic dataset** for demonstration and prototyping.  
- Visuals are meant for data-driven strategic support and simulation; do not interpret figures as real-world institutional outcomes.

---

## Contact / Support

For questions, feedback, or collaboration inquiries, please contact jananidelli14@gmail.com.
