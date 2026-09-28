# Airbnb-Data-Analytics
Create Airbnb Data Analytics using Python, Jupyter Notebook

🎯 Objectives
Clean and preprocess Airbnb data.
Perform exploratory data analysis.
Visualize trends and insights.
Identify factors affecting listing prices.
Analyze host and neighborhood performance.
Generate actionable business recommendations.

📊 Dataset Features

The dataset contains Airbnb listing information, including host details, property characteristics, pricing, reviews, and availability metrics. Each row represents a unique Airbnb property listing
| Feature                          | Data Type   | Description                                                                |
| -------------------------------- | ----------- | -------------------------------------------------------------------------- |
| `id`                             | Integer     | Unique listing identifier                                                  |
| `NAME`                           | String      | Airbnb listing title/name                                                  |
| `host_id`                        | Integer     | Unique host identifier                                                     |
| `host_identity_verified`         | Categorical | Host verification status (`verified`, `unconfirmed`)                       |
| `host_name`                      | String      | Name of the host                                                           |
| `neighbourhood_group`            | Categorical | Borough/location group (Manhattan, Brooklyn, Queens, Bronx, Staten Island) |
| `neighbourhood`                  | Categorical | Specific neighborhood of the property                                      |
| `lat`                            | Float       | Latitude coordinate of the listing                                         |
| `long`                           | Float       | Longitude coordinate of the listing                                        |
| `country`                        | String      | Country name                                                               |
| `country_code`                   | String      | Country code (`US`)                                                        |
| `instant_bookable`               | Boolean     | Whether instant booking is available                                       |
| `cancellation_policy`            | Categorical | Cancellation policy (`flexible`, `moderate`, `strict`)                     |
| `room_type`                      | Categorical | Type of accommodation (`Entire home/apt`, `Private room`, `Shared room`)   |
| `Construction_year`              | Integer     | Year the property was constructed                                          |
| `price`                          | Numeric     | Nightly listing price                                                      |
| `service_fee`                    | Numeric     | Airbnb service fee                                                         |
| `minimum_nights`                 | Integer     | Minimum nights required for booking                                        |
| `number_of_reviews`              | Integer     | Total reviews received                                                     |
| `last_review`                    | Date        | Most recent review date                                                    |
| `reviews_per_month`              | Float       | Average reviews per month                                                  |
| `review_rate_number`             | Integer     | Listing review score/rating                                                |
| `calculated_host_listings_count` | Integer     | Total listings managed by the host                                         |
| `availability_365`               | Integer     | Number of available days in a year                                         |
| `house_rules`                    | Text        | Rules and restrictions set by the host                                     |
| `license`                        | String      | Property license/permit information                                        |

🛠️ Technologies Used
Programming Language
Python 3.x
Development Environment
Jupyter Notebook

Python Libraries
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
warnings

📂 Project Structure

Airbnb-Data-Analytics/
│
├── data/
│   └── airbnb.csv
│
├── notebooks/
│   └── Airbnb_Data_Analysis.ipynb
│
├── images/
│   └── charts_and_visualizations
│
├── requirements.txt
│
├── README.md
│
└── LICENSE

⚙️ Installation Guide
Step 1: Clone the Repository

git clone https://github.com/yourusername/Airbnb-Data-Analytics.git

Step 2: Create Virtual Environment (Recommended)
Windows
python -m venv venv
venv\Scripts\activate
Linux / MacOS
python3 -m venv venv
source venv/bin/activate
Step 3: Install Dependencies
pip install -r requirements.txt
Or install libraries manually:
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter

Step 4: Launch Jupyter Notebook
jupyter notebook
Open:
Airbnb_Data_Analysis.ipynb

📈 Exploratory Data Analysis

The project includes:

Data Cleaning
Handling missing values
Removing duplicates
Outlier detection
Data type conversion
Price Analysis
Average price by neighborhood
Room type vs pricing
Premium locations
Host Analysis
Top hosts
Host activity
Review performance
Availability Analysis
Availability trends
Occupancy insights
Review Analysis
Popular listings
Customer engagement metrics
📷 Sample Visualizations
Price Distribution Histogram
Room Type Count Plot
Correlation Heatmap
Neighborhood Price Comparison
Host Performance Dashboard
Availability Trends
📊 Key Insights

Some potential findings include:

✅ Entire homes are generally priced higher than private rooms.

✅ Certain neighborhoods consistently attract higher listing prices.

✅ Highly reviewed listings tend to receive better visibility.

✅ Availability significantly impacts booking opportunities.

✅ Super hosts often maintain higher ratings and customer engagement.

💼 Business Use Cases
For Airbnb Hosts
Optimize pricing strategy.
Improve occupancy rates.
Understand market competition.
For Travelers
Discover affordable locations.
Compare room types.
Identify value-for-money stays.
For Data Analysts
Practice data cleaning and EDA.
Develop visualization skills.
Build portfolio projects.
For Businesses
Market trend analysis.
Customer behavior insights.
Revenue optimization strategies.
👥 Target Users

This project is ideal for:

Data Analysts
Business Analysts
Data Science Students
Machine Learning Enthusiasts
Airbnb Hosts
Hospitality Industry Professionals
Researchers
Recruiters evaluating data analytics portfolios
🔮 Future Enhancements
Interactive Power BI Dashboard
Tableau Dashboard Integration
Machine Learning Price Prediction Model
Booking Demand Forecasting
Sentiment Analysis on Reviews
Geospatial Mapping with Folium
Streamlit Web Application
📚 Skills Demonstrated
Python Programming
Data Cleaning
Data Analysis
Exploratory Data Analysis (EDA)
Data Visualization
Statistical Analysis
Business Intelligence
Problem Solving
Dashboard Development
Data Storytelling
🤝 Contributing

Contributions are welcome!

Fork the repository
Create a new branch

<img width="790" height="490" alt="download" src="https://github.com/user-attachments/assets/6d9b07da-0e34-42ec-80e3-3cf15cdf2f94" />
<img width="989" height="590" alt="download" src="https://github.com/user-attachments/assets/c001d312-ebee-46d1-92df-6aeb92f23e5c" />
<img width="790" height="490" alt="download" src="https://github.com/user-attachments/assets/15f0e35e-21ee-4f39-b291-b2a958dd4404" />
<img width="1790" height="1145" alt="download" src="https://github.com/user-attachments/assets/aa2a0c31-14b0-4f03-83ba-37818190e5c2" />
<img width="989" height="590" alt="download" src="https://github.com/user-attachments/assets/15842703-c4bf-4344-9f03-96df7b214c6d" />
<img width="1189" height="590" alt="download" src="https://github.com/user-attachments/assets/91c48960-1a55-40bb-8b80-467bb2f7cdca" />


