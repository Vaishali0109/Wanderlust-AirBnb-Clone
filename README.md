🌍 **Overview**

Wanderlust is a full-stack Airbnb clone built using Node.js, Express, MongoDB, EJS, and CSS. 
It offers features like user authentication, property listing, dynamic filtering by categories, and search functionality by city or location. 
The application is designed with server-side rendering (SSR) and responsive design principles to deliver a seamless user experience.

**✨ Features**

**User Authentication:** Secure login and signup with session-based authentication.
**Property Listings:** Add, update, and delete property details.
**Category Filtering:** Narrow down listings based on predefined categories (e.g., apartments, houses, shared spaces).
**Search by City or Location:** Quickly find properties by typing the name of a place or city.
**User Reviews and Ratings:** Leave reviews and rate properties to help others make informed decisions.
**Responsive Design:** Fully optimized for all devices.

**💻 Tech Stack**

**Backend**: Node.js, Express.js
**Frontend**: EJS (server-side rendering), CSS
**Database**: MongoDB
**Authentication**: Passport.js

**🚀 How to Install and Run Locally**

Clone the Repository:

```git clone https://github.com/your-username/wanderlust.git```

Navigate to the Project Directory:
```cd wanderlust```

Install Dependencies:
```npm install```

**Set Up Environment Variables:**

Create a .env file in the root directory and add the following:
CLOUD_NAME=your_cloud_name_here
CLOUD_API_KEY=your_cloud_api_key_here
CLOUD_API_SECRET=your_cloud_api_secret_here

MAP_TOKEN=your_mapbox_access_token_here

ATLASDB_URL=mongodb+srv://<username>:<password>@<cluster-name>.mongodb.net/<database-name>?retryWrites=true&w=majority

SECRET=your_secret_code_here

Run the Application:
```npm start``` 

Access the Application:
Open [http://localhost:8080/listings](url) in your browser.

My Deployed Project:
[https://wanderlust-airbnb-clone-r502.onrender.com/listings
](url)

**📸 Screenshots**

Homepage
![image](https://github.com/user-attachments/assets/07df0629-7c01-4a40-953d-1d88910f217d)

Category Filtering
![image](https://github.com/user-attachments/assets/2f1a5d63-8c9e-4f12-94ef-75b54d534842)

Reviews and Ratings Section
![image](https://github.com/user-attachments/assets/b7fd9713-2855-446e-a2f7-e8e156c035bb)

Login/Signup Page
![image](https://github.com/user-attachments/assets/693344ea-ed76-46d2-b58c-a66857fcc6d9)

Add Listings Page
![image](https://github.com/user-attachments/assets/112c2279-c297-470f-b46d-5c6e57135386)


**🌟 Future Enhancements**

Payment Integration: Add a payment gateway for property bookings.

Recommendation System: Suggest properties based on user preferences and browsing history.
