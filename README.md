#   OLA Ride Cancellation Analysis

##   Overview

    This project analyzes OLA ride booking data to understand trends and reasons for cancellations, and to derive insights that can improve the experience for both customers and drivers. The analysis considers booking status, vehicle types, pickup/drop locations, ride distance, payment methods, ratings, and reasons for cancellations or incomplete rides. The primary analysis period is from 01-07-2024 to 29-07-2024.

![image](https://github.com/user-attachments/assets/3fb62115-e7d6-470e-a418-374579f28991)

    The Power BI dashboard used for this analysis can be found here: [https://github.com/rohantade8/Ola-Ride-Cancellation-Analysis/blob/main/Ola%20Data%20Analytics.pbix](https://github.com/rohantade8/Ola-Ride-Cancellation-Analysis/blob/main/Ola%20Data%20Analytics.pbix)

##   Features

    * **Data Cleaning:** Preprocessing the dataset to handle missing values and inconsistencies to ensure data quality for analysis.
    * **Exploratory Data Analysis (EDA):**
        * Analysis of trends in ride cancellations by drivers and customers to identify patterns and contributing factors.
        * Analysis of vehicle types and their booking success rates to understand vehicle preference and efficiency.
        * Insights into payment methods and their usage to determine popular payment choices.
        * Analysis of customer and driver ratings to assess service quality and user satisfaction.
    * **Interactive Visualizations:** Creating interactive dashboards and visualizations in Power BI to explore and present the data.
    * **Database Interaction:** Using SQL to query and extract data from the database, enabling efficient data retrieval and manipulation. This includes solving the SQL questions provided in the project brief.
    * **Key Metrics Calculation:** Calculating important metrics such as Total Bookings, Total Bookings Value and Cancellation Rate within Power BI.
    * **Customer Segmentation:** Identifying Top 5 Customers based on booking value.
    * **Distance Analysis:** Analyzing total and average ride distance.

    * **Insights:**
        * Identification of common reasons for ride cancellations to address specific issues.
        * Analysis of the correlation between ratings and ride success to understand the impact of ratings on service completion.
        * Analysis of ride volume over time to identify peak and low demand periods.
        * Analysis of booking value to understand revenue generation.

##   Dataset Description

    The dataset includes the following fields:

    * Booking Date/Time: Timestamp of the booking, indicating when the ride was requested [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd].
    * Booking\_ID: Unique identifier for each booking, used to track individual ride requests [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd].
    * Customer: Unique identifier for the customer who made the booking [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd].
    * Vehicle\_Type: Type of vehicle used for the booking (e.g., Auto, Mini, Prime Sedan) [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd, 5].
    * Pickup\_Location: Starting location of the ride [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd].
    * Drop\_Location: Destination location of the ride [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd].
    * TAT: Turnaround Time or Total Trip Duration [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd].
    * Cancelled: Indicates whether the booking was cancelled (Yes/No) [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd, 5].
    * Cancellation Reason: Reason provided for the cancellation [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd, 5].
    * Incorrect Booking: Indicates if there was an error or issue with the booking [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd].
    * Payment: Payment method used for the ride (e.g., Cash, UPI, Credit Card) [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd, 5].
    * Ride\_Distance: Distance covered during the ride (in km) [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd].
    * Driver\_Rating: Rating given by the customer to the driver [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd, 5].
    * Customer\_Rating: Rating given by the driver to the customer [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd, 5].
    * Vehicle Images: URL or reference to an image of the vehicle type [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd].
    * Booking\_Status: Status of the ride (e.g., Success, Canceled by Driver, Canceled by Customer, Driver Not Found).

##   Key Findings

    Vehicle Insights:

![Ola Data Analytics_page-0002](https://github.com/user-attachments/assets/4858a1ea-787e-415c-83f5-da2e0e05e539)

    Revenue Analysis:

![Ola Data Analytics_page-0003](https://github.com/user-attachments/assets/8022dcbb-be97-4a93-9c4a-f38fa2e92f5e)

    Cancellation Trends:

![Ola Data Analytics_page-0004](https://github.com/user-attachments/assets/82ff7782-4896-483e-a6f2-60952f952791)

    Ratings Impact:

![Ola Data Analytics_page-0005](https://github.com/user-attachments/assets/2159ade6-f0ef-40fc-889c-15d63aab8c5f)

    * **SQL Analysis:**
        * Solved SQL queries to retrieve successful bookings, find average ride distance by vehicle type, count cancelled rides by customers, list top 5 customers, count driver cancellations due to personal/car issues, find max/min driver ratings for Prime Sedan, retrieve UPI payments, find average customer rating by vehicle type, calculate total successful booking value, and list incomplete rides with reasons.

##   Tools Used

    * Power BI: For creating interactive dashboards and visualizations to explore and present the data. The Power BI dashboard used for this analysis is available at: [https://github.com/rohantade8/Ola-Ride-Cancellation-Analysis/blob/main/Ola%20Data%20Analytics.pbix](https://github.com/rohantade8/Ola-Ride-Cancellation-Analysis/blob/main/Ola%20Data%20Analytics.pbix)
    * SQL: For querying, extracting, and manipulating data from relational databases. Used to answer the SQL questions provided in the project.
    * GitHub: For version control, collaboration, and project management.

##   Installation

    1.  Ensure you have Microsoft Power BI Desktop installed to open and interact with the Power BI report.
    2.  Clone this repository:

        ```text
        git clone <repository_url>
        ```

    3.  (Optional) Set up and configure your SQL database connection if you intend to run the SQL scripts directly. Ensure you have the necessary database drivers installed.

##   Usage

    1.  Load the dataset (e.g., `OLA_Cancellation_Data.xlsx` or `Bookings-July.csv`) into the analysis environment. For Power BI, this involves connecting the data source to the Power BI report.
    2.  Open the Power BI report to explore the interactive visualizations and analysis. If using SQL, execute the SQL queries against your database to extract and prepare data for analysis.
    3.  Explore the generated visualizations and analysis results in Power BI to gain insights into ride cancellations and related factors. Review the SQL query results to answer the specific questions posed in the project.

##   Contribution

    Contributions to this project are welcome! Please fork this repository and submit a pull request with your proposed changes. Ensure your contributions adhere to the project's coding standards and include appropriate documentation.

##   License

    This project is licensed under the MIT License. See the `LICENSE` file for details.

##   Citations

    * OLA Data Analytics.pdf - Page 1, Ride Volume Over Time
    * OLA Data Analytics.pdf - Page 1, Dates 01-07-2024 to 29-07-2024
    * OLA Data Analytics.pdf - Page 2, Vehicle Type Analysis, Total Booking Value, Success Booking Value, Total Distance Travelled, Avg. Distance Travelled
    * OLA Data Analytics.pdf - Page 3, Payment Method Analysis, Top 5 Customers, Sum of Booking Value, Sum of Ride Distance
    * OLA Data Analytics.pdf - Page 4, Overall Metrics, Total Bookings, Cancelled Rides by Customers, Succeeded Bookings, Cancelled Bookings, Cancellation, Cancellation Rate, Booking Status Breakdown, Cancellation Reasons
    * OLA Data Analytics.pdf - Page 5, Driver Ratings
    * OLA Data Analytics.pdf - Page 8, Driver Ratings by Vehicle Type
    * OLA Data Analytics.pdf - Page 9, Customer Ratings
    * OLA Data Analytics.pdf - Page 10, Customer Ratings by Vehicle Type
    * OLA Data Analyst Project-1.pdf - SQL Questions and Answers
    * [cite: image_95eb07.jpg-439d80f9-b7e8-422b-a4ff-b39305e100fd] - Excel Sample Data
    * (Note: I have not included the pplx.ai citations as they are references to the source I used to help compile this information, not direct sources for the data itself)
