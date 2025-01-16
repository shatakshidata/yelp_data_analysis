# Yelp Dataset Analysis

This project analyzes the Yelp dataset to extract insights about businesses, reviews, and user behaviors. Using Python and Pandas, the project processes large datasets efficiently by leveraging chunk processing and memory optimization techniques.

## Dataset

The data is sourced from the **Yelp Dataset** and includes the following components:
- **Businesses**: Information about businesses, including location, ratings, and attributes.
- **Reviews**: User-generated reviews with ratings and timestamps.
- **Users**: Metadata about Yelp users.
- **Check-ins**: Data on user check-ins at businesses.
- **Tips**: User tips for businesses.

## Features

- **Data Processing**:
  - Efficiently loads and processes large JSON datasets in chunks to prevent memory overload.
  - Combines chunks into Pandas DataFrames for analysis.

- **Exploratory Data Analysis (EDA)**:
  - Provides summaries of each dataset, including structure, column details, and sample records.
  - Identifies key attributes like business categories, user check-in trends, and review distributions.

- **Insights Generation**:
  - Analyzes business ratings, popular categories, and geographic trends.
  - Examines user engagement metrics (usefulness, funniness, and coolness of reviews).

## File Structure

```plaintext
├── yelp-dataset
│   ├── yelp_academic_dataset_business.json
│   ├── yelp_academic_dataset_review.json
│   ├── yelp_academic_dataset_user.json
│   ├── yelp_academic_dataset_checkin.json
│   ├── yelp_academic_dataset_tip.json
│   └── Dataset_User_Agreement.pdf
├── badm-project.ipynb
└── README.md
