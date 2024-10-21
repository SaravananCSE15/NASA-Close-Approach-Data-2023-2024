# 🚀 NASA Close Approach Analysis 2023-2024 🌍
📄 Introduction
This notebook analyzes data on near-Earth objects (NEOs), including asteroids and comets, that approached Earth between January 1, 2023, and September 25, 2024. The dataset is sourced from NASA’s Jet Propulsion Laboratory (JPL), using the Close Approach Data API (CAD API). It includes critical information about each object's closest approach, such as the nominal distance, relative velocity, and the time uncertainty.

# 🔍 Objective
The goal of this analysis is to explore:

The distance of close approaches between Earth and these objects.
The velocity of the objects during their approach.
Patterns in close approaches over time.
Relationships between object size (H magnitude) and proximity to Earth.
# 📊 Dataset Overview
Date Range: January 1, 2023 – September 25, 2024
Object Types: Asteroids and comets
Source: NASA/JPL SBDB Close Approach Data API
File Path: /kaggle/input/nasa-close-approach-data-2023-2024/nasa_close_approach_2023_2024.csv
# 📝 Fields in the Dataset:
des: Object designation (unique identifier for the object)
orbit_id: Orbit identification for close approach
jd: Julian Date for the close approach
cd: Calendar Date for the close approach
dist: Nominal approach distance (AU)
dist_min: Minimum approach distance (AU)
dist_max: Maximum approach distance (AU)
v_rel: Relative velocity (km/s)
v_inf: Velocity relative to a massless object (km/s)
t_sigma_f: Time uncertainty for close approach
h: Absolute magnitude of the object
# 🧭 Analysis Plan
Data Exploration: Visualize and summarize the approach distance, velocity, and time uncertainties.
Temporal Analysis: Explore how close approaches vary over time.
Correlation Analysis: Investigate potential relationships between the size of the object and its approach distance or velocity.
Visualizations: Create plots to represent the distribution of distances and velocities, along with time series trends.
