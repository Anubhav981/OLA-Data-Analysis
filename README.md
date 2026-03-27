<h1>📊 OLA Data Analysis Project (Power BI + SQL)</h1>

<h2>📌 Project Overview</h2>
<p>
This project focuses on analyzing ride booking data for Bengaluru city using SQL and Power BI. 
The dataset contains 1 lakh ride records generated for one month to simulate real-world ride-hailing scenarios.
</p>

<p>The objective is to extract meaningful insights related to:</p>
<ul>
  <li>Booking trends</li>
  <li>Cancellation patterns</li>
  <li>Revenue analysis</li>
  <li>Customer & driver behavior</li>
</ul>

<h2>🎯 Objectives</h2>
<ul>
  <li>Analyze ride volume over time</li>
  <li>Understand booking success vs cancellation rates</li>
  <li>Identify top-performing vehicle types</li>
  <li>Evaluate customer and driver ratings</li>
  <li>Analyze revenue and ride distance patterns</li>
</ul>

<h2>🛠️ Tools & Technologies Used</h2>
<ul>
  <li>Power BI → Data visualization & dashboard</li>
  <li>SQL (MySQL) → Data analysis & querying</li>
  <li>Excel / CSV → Data storage</li>
</ul>

<h2>📂 Dataset Information</h2>
<p>The dataset contains the following key columns:</p>
<ul>
  <li>Date, Time</li>
  <li>Booking_ID</li>
  <li>Booking_Status</li>
  <li>Customer_ID</li>
  <li>Vehicle_Type</li>
  <li>Pickup_Location, Drop_Location</li>
  <li>V_TAT (Vehicle arrival time)</li>
  <li>C_TAT (Customer arrival time)</li>
  <li>Cancellation details</li>
  <li>Booking_Value</li>
  <li>Ride_Distance</li>
  <li>Driver_Ratings, Customer_Rating</li>
</ul>

<h2>🧠 SQL Analysis</h2>
<p>The following SQL queries were performed:</p>
<ul>
  <li>Retrieve all successful bookings</li>
  <li>Average ride distance per vehicle type</li>
  <li>Total cancelled rides (customer & driver)</li>
  <li>Top 5 customers by ride count</li>
  <li>Driver cancellation analysis</li>
  <li>Max & Min driver ratings</li>
  <li>UPI payment analysis</li>
  <li>Average customer rating per vehicle</li>
  <li>Total successful booking value</li>
  <li>Incomplete rides with reasons</li>
</ul>

<pre>
SELECT * 
FROM bookings 
WHERE Booking_Status = 'Success';
</pre>

<h2>📊 Power BI Dashboard</h2>

<h3>🔹 Overall Analysis</h3>
<ul>
  <li>Ride Volume Over Time</li>
  <li>Booking Status Breakdown</li>
</ul>

<h3>🔹 Vehicle Analysis</h3>
<ul>
  <li>Top 5 Vehicle Types by Ride Distance</li>
</ul>

<h3>🔹 Revenue Analysis</h3>
<ul>
  <li>Revenue by Payment Method</li>
  <li>Top 5 Customers by Booking Value</li>
  <li>Ride Distance Distribution</li>
</ul>

<h3>🔹 Cancellation Analysis</h3>
<ul>
  <li>Customer Cancellation Reasons</li>
  <li>Driver Cancellation Reasons</li>
</ul>

<h3>🔹 Ratings Analysis</h3>
<ul>
  <li>Driver Ratings Distribution</li>
  <li>Customer vs Driver Ratings</li>
</ul>

<h2>📸 Dashboard Preview</h2>
<img src="images/dashboard_images/Screenshot 2024-12-15 195004.png" alt="Dashboard" width="800"/>

<h2>🎥 Dashboard Demo</h2>
<img src="images/Ola Dashboard Project DEMO.gif" alt="Demo" width="800"/>

<h2>📁 Project Structure</h2>
<pre>
OLA-Data-Analysis
├── data/
│   └── bookings.csv
├── sql/
│   └── queries.sql
├── dashboard/
│   └── ola_dashboard.pbix
├── images/
│   ├── dashboard.png
│   └── demo.gif
└── README.md
</pre>

<h2>📈 Key Insights</h2>
<ul>
  <li>~62% of bookings are successful</li>
  <li>Majority cancellations are due to driver-related issues</li>
  <li>Peak bookings occur during evenings & weekends</li>
  <li>High revenue generated from premium vehicle types</li>
  <li>Customer ratings are generally higher than driver ratings</li>
</ul>

<h2>🚀 Conclusion</h2>
<p>This project demonstrates an end-to-end data analytics workflow:</p>
<ul>
  <li>✔ Data generation</li>
  <li>✔ Data analysis using SQL</li>
  <li>✔ Dashboard creation using Power BI</li>
  <li>✔ Business insights extraction</li>
</ul>

<h2>📬 Connect With Me</h2>
<ul>
  <li>LinkedIn: (Add your link)</li>
  <li>GitHub: (Add your profile link)</li>
</ul>
