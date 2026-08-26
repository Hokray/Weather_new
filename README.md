# Weather & Outdoor Activity Recommendation App

A web app that pairs weather forecasting with recommendations for outdoor
activities — hikes, walking trails and sports — helping users decide where
to go based on the conditions that actually matter for each activity.

Built during NASA Space Apps Challenge 2025, a 2 day challenge. 
Forked from a teammate's original repository so I could contribute in parallel.

## Features
- Activity-specific weather parameters across 13 outdoor activities
  (hiking, swimming, skiing, fishing, camping, sailing, outdoor exercise
  and others), each mapped to the conditions relevant to it — snow depth
  and fresh snowfall for skiing, wave height and water temperature for
  swimming, ocean current for fishing, forest fire risk for hiking
- Historical weather data for Ireland via the Meteomatics API, queried
  across a national bounding box (2015–2024)
- Map-based location and route data through the Google Maps API
- Flask API layer connecting the frontend to the weather and prediction
  services

## Tech Stack
**Frontend:** JavaScript, HTML, CSS
**Backend:** Python, Flask, pandas
**APIs:** Meteomatics API, Google Maps API
**Modelling:** scikit-learn, NumPy

## My Contributions — Frontend Lead
- Led frontend development across the application
- Integrated the Google Maps API to source location and route data
  feeding the recommendation layer
- Built the interface presenting weather conditions alongside suggested
  activities
- Collaborated with teammates on the Flask API contract between the
  frontend and the weather/prediction services

## Repository Structure
