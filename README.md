# FoodieAI – AI-Powered Restaurant Recommendation System

**FoodieAI** is a restaurant recommendation platform designed to help users discover restaurants based on their cuisine preferences, location, price range, ratings, and dining requirements.

The project currently implements a content-based recommendation engine in Python and is being developed into a full-stack web application.

## Project Overview

Finding suitable restaurants can be difficult when users have specific cuisine, budget, and dining preferences. FoodieAI addresses this problem by filtering restaurants according to user requirements and ranking them based on cuisine similarity, ratings, and customer vote confidence.

## Key Features

### Implemented – Recommendation Engine

- Content-based restaurant recommendations
- Cuisine matching using multi-label encoding and cosine similarity
- City, price range, and minimum rating filtering
- Online delivery and table booking preference filters
- Weighted restaurant ranking
- Top-N personalized recommendations
- Data preprocessing and basic recommendation testing

### Planned – Full-Stack Application

- Responsive web interface using React.js and Tailwind CSS
- FastAPI backend for recommendation requests
- PostgreSQL database integration
- Interactive restaurant search and filtering
- Restaurant detail pages
- Integration of the recommendation engine with the web interface
- Deployment of the completed application

## Recommendation Algorithm

FoodieAI uses content-based filtering to identify restaurants matching user preferences.

The recommendation score combines three factors:

| Factor             | Weight |
| ------------------ | -----: |
| Cuisine similarity |    60% |
| Restaurant rating  |    30% |
| Vote confidence    |    10% |

**Final Score = 0.60 × Cuisine Similarity + 0.30 × Normalized Rating + 0.10 × Normalized Vote Score**

Cuisine similarity is calculated using cosine similarity, while ratings and votes help rank relevant restaurants.

## Dataset

The project uses a restaurant dataset containing 9,551 records across multiple countries.

Features include restaurant names, cities, cuisines, price ranges, aggregate ratings, votes, online delivery availability, and table booking availability.

## Technology Stack

| Layer                   | Technologies                        | Status      |
| ----------------------- | ----------------------------------- | ----------- |
| Recommendation Engine   | Python, Pandas, NumPy, Scikit-learn | Implemented |
| Development Environment | Jupyter Notebook                    | Implemented |
| Backend                 | FastAPI                             | Planned     |
| Frontend                | React.js, Vite, Tailwind CSS        | Planned     |
| Database                | PostgreSQL                          | Planned     |

## Development Roadmap

- Dataset exploration and preprocessing
- Cuisine feature encoding
- Content-based recommendation algorithm
- Weighted recommendation ranking
- Preference-based filtering
- Initial recommendation testing
- Upload recommendation notebook and reusable Python modules
- Develop FastAPI backend
- Build React frontend
- Integrate PostgreSQL
- Connect frontend and backend
- Perform end-to-end testing
- Deploy FoodieAI


The recommendation engine has been implemented in Jupyter Notebook.

This repository will be updated with source code, API documentation, frontend components, database integration, and deployment instructions as development progresses.

## Author

**Ashish Gije**

[GitHub Profile](https://github.com/ashishgiije)
