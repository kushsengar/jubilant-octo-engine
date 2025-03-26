# DemandWise
Overview of the Website
The website will serve as the user interface for the AI-Powered Demand Forecasting System for Hyperlocal Delivery. It will enable businesses to interact with the demand forecasting model, analyze their sales data, and manage inventory in a seamless and intuitive way.

The website will have different sections, including:

User Authentication (Login/Signup)

Dashboard with demand forecasts, sales data, and recommendations.

Demand Forecasting Page for detailed forecasts and predictions.

Sales Data Page to visualize historical sales and trends.

Inventory Management Page to track and manage inventory levels.

Reports Page for generating and downloading reports.

Settings Page to update profile and business preferences.

Contact Page for user support and inquiries.

Each section will be designed to provide businesses with insights to make data-driven decisions on inventory management and product delivery.
![image](https://github.com/user-attachments/assets/05d07f25-8fa2-47d3-bcee-c31398bfed53)

![image](https://github.com/user-attachments/assets/7ab2aee9-6ea3-4443-84b7-469448ebefdb)


Website Structure
1. Homepage
The homepage serves as an introduction to the AI-Powered Demand Forecasting System. It provides a brief overview of the product and encourages users to sign up or log in.

Header:

Contains the logo and navigation links (Home, Features, About Us, Contact, Login/Signup).

The Login/Signup button should redirect users to their respective pages.

Hero Section:

A large banner image with a tagline like: "AI-Driven Demand Forecasting for Hyperlocal Delivery Businesses".

CTA Button: "Get Started" → Redirects to the signup page.

Features Section:

Key features are described with icons and short text (e.g., Predict Demand, Optimize Inventory, etc.).

Learn More button redirects to the detailed Features page.

Footer:

Links to Privacy Policy, Terms of Service, and social media channels.

2. Authentication Pages (Login/Signup)
Login Page:

Fields: Email, Password, and a button "Login" that redirects to the Dashboard if credentials are correct.

If a user doesn’t have an account, a "Sign Up" link redirects them to the signup page.

Signup Page:

Fields: Name, Email, Password, and a "Sign Up" button to create a new user account.

After successful signup, the user is redirected to the login page.

Forgot Password Page:

Allows the user to enter their email to reset the password.

3. Dashboard Page
The dashboard is the primary page after login, where users get an overview of their business performance and the forecasted demand.

Sidebar Navigation: Links to Demand Forecasting, Sales Data, Inventory Management, Reports, and Settings pages.

Greeting Section: A personalized welcome message for the user.

AI Forecast: Displays predicted demand for the next month with an option to view more details.

Recent Sales: A quick view of the last month’s sales data with a button "View Details" that redirects to the Sales Data page.

Current Inventory: Shows the existing inventory status with a "View Inventory" button that redirects to the Inventory Management page.

4. Demand Forecasting Page
This page displays the demand forecast generated by the AI model. Users can view the predicted demand for specific products and plan accordingly.

Forecast Chart: Line graph showing the demand forecast for the next few months.

Historical Data: Graphical representation of past product sales for comparison.

Generate New Forecast Button: Allows users to update the forecast with the latest data.

Download Report Button: Exports the forecast data to CSV/PDF.

5. Sales Data Page
This page shows the historical sales data, which is used by the AI model to generate demand predictions.

Sales Data Table: A table displaying the sales history with columns for Date, Product, Quantity Sold, and Revenue.

Chart View: Option to view sales data as a bar chart or line graph.

Filter Options: Users can filter sales data by date, product, and region.

Export Data Button: Allows users to download the sales data as a CSV or Excel file.

6. Inventory Management Page
This page allows businesses to track inventory levels, set reorder points, and receive AI-driven recommendations for restocking.

Inventory Table: Displays products with columns for current stock levels, reorder points, and lead times.

Reorder Recommendations: Suggestions generated by AI on products that need restocking based on forecasted demand.

Adjust Inventory Button: Allows users to manually adjust inventory levels.

Stock Alerts: Notifies users when inventory is running low or needs to be reordered.

7. Reports Page
This page allows users to generate reports based on their demand forecasts, sales data, and inventory levels.

Report Type Selection: Dropdown to select the type of report (e.g., Demand Forecast, Sales Analysis).

Generate Report Button: Generates the selected report and displays it.

Download Report Button: Allows users to download the generated report in PDF/Excel format.

8. Settings Page
The settings page allows users to manage their profile and configure business-related preferences.

Profile Information: Update name, email, and password.

Notification Settings: Configure notification preferences (e.g., inventory alerts, forecast updates).

Business Settings: Set working hours, location, and time zone.

9. Contact Page
This page allows users to get in touch with the support team or send inquiries.

Contact Form: Fields for Name, Email, and Message.

Submit Button: Sends the form data to the backend system for processing.

Contact Information: Email and phone number for customer support.

Design and User Interface Guidelines
Clean and Minimalistic Design: The design should focus on user-friendly navigation and data clarity. Use white space generously to keep the interface uncluttered.

Responsive Design: Ensure the website is fully responsive on all devices (desktop, tablet, and mobile).

Color Scheme: Use professional colors that align with business goals, such as blue (trustworthy) and green (growth).

Typography: Use modern fonts such as Roboto or Open Sans for readability and a sleek look.

Interactive Elements: Buttons and links should have hover effects for better user experience.

Data Visualization: Use charts and graphs to display data clearly (e.g., line graphs, bar charts, pie charts).

Technology Stack
Frontend: React.js (for building a dynamic user interface), Tailwind CSS (for styling), Chart.js (for data visualization).

Backend: Node.js (with Express.js) for the API layer, Python for the AI model (Flask/FastAPI for model integration).

Database: MongoDB/PostgreSQL for storing user data, sales data, and inventory information.

Authentication: JWT (JSON Web Tokens) for secure login and session management.

Cloud: AWS or DigitalOcean for hosting, S3 for file storage, and MongoDB Atlas for the database.

Setup Instructions

Navigate to the frontend directory:
cd frontend

Install dependencies:
npm install

Start the development server:
npm start

Backend

Navigate to the backend directory:
cd backend

Install dependencies:
npm install

Start the server:
npm start


