# Netflix Movies & TV Show Recommendation System

This repository contains code to build a content-based recommendation system for Netflix movies and TV shows using Python. The system is designed to recommend movies and shows based on text similarity between titles. We also incorporate an additional dataset of books to enrich the recommendations.

## Key Features

- **Data Preprocessing:** Clean and standardize the Netflix dataset (lowercase, string operations).
- **Data Merging:** Combine Netflix and book data to expand the recommendation engine.
- **Content-based Filtering:** Uses title similarities between Netflix titles and book titles for recommendations.
- **Visualizations:** Includes plots and visual outputs for insights.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `plotly`

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/saukrtz/Netflix-Movie-TV-Recommendation.git
   cd Netflix-Movie-TV-Recommendation

   
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt


3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Netflix_Movies_T_V_Recommendation.ipynb
    ```
    
### Project Structure:
   ```bash
     .
     ├── Netflix_Movies_T_V_Recommendation.ipynb  # Main notebook for building the recommendation system
     ├── README.md                                # Project overview and instructions
     └── requirements.txt                         # List of required dependencies
   ```

