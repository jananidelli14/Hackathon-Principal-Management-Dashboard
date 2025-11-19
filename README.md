# Hackathon-Principal-Management-Dashboard

Project Overview
This project contains a data analytics dashboard built using Grafana for analyzing departmental performance, student engagement, recruitment, and innovation metrics based on the dataset provided. The dashboard provides insights to help academic leadership make data-driven decisions.

Dataset
The key dataset file is derived from Augmented_500_Final_Fixed.csv.

Data columns include:

department_name

event_year

total_students

total_offers

recruiter_visits

partnership_count

active_participants

innovation_score_avg

total_hackathon_cost

departmental_performance_index_dpi

institutional_roi

Data is aggregated by department and year in various dashboard panels.

Dashboard Visuals
The dashboard covers the following key visuals:

Recruiter Visits and Partnerships by Department:

Stacked bar chart showing recruiter engagement and partnership counts.

Student Engagement by Department:

Pie chart showing active participants share by departments.

Hackathon Investment vs Innovation Score:

Scatter plot comparing hackathon costs to innovation output per department.

Departmental Performance Index Heatmap:

Heatmap displaying the performance index over time across departments.

Placement Success Rate Trends:

Line chart tracking placement success rates over years by department.

Institutional ROI Leaderboard:

Table ranking departments by average institutional ROI.

Top N Department Tables:

Leaderboard tables for metrics like active participants and offers.

Usage
Import the included JSON files into Grafana to replicate the dashboard setup.

Ensure the data source connects to a PostgreSQL database containing the dataset described.

Run the provided SQL queries to populate dashboards.

Customize visuals as needed based on organizational needs.

Running Locally
Clone the repository.

Load the dataset into your PostgreSQL database.

Configure Grafana to connect to your PostgreSQL datasource.

Import the dashboard JSON files from this repo via Grafana’s import feature.

Adjust queries and panels as needed for your environment.
