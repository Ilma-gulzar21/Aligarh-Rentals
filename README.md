# Aligarh-Rentals
A full-stack rental marketplace built with Node.js, Express.js, MongoDB, and EJS to help students and newcomers find rental properties and roommates in Aligarh. Features include property search and filtering, user authentication, owner dashboards, reviews, ratings, image uploads, and interactive maps.

# Aligarh Rentals — Full-Stack Rental Marketplace

**Aligarh Rentals** is a full-stack web application designed to help students, newcomers, and residents find rental properties and roommates in Aligarh, Uttar Pradesh. It connects property owners with tenants through a user-friendly platform for discovering and managing rental listings.

The project is built using the **MERN-related web development ecosystem with Node.js, Express.js, MongoDB, and EJS**, following the MVC architecture.

##  About the Project

Finding suitable rental accommodation in a new city can be challenging, especially for students moving to Aligarh for education at Aligarh Muslim University (AMU).

Aligarh Rentals aims to simplify this process by providing a centralized platform where tenants can explore rental properties, compare available options, and find potential roommates. Property owners can create and manage listings to reach prospective tenants.

##  Features

### Property Listings

* Browse available rental properties in Aligarh.
* View detailed property information and images.
* Explore property types and BHK configurations.
* View rent, security deposit, furnishing details, and location information.

###  Property Search & Filtering

* Search properties based on location and area.
* Filter properties by rent and property type.
* Filter by BHK configuration and tenant preferences.
* Explore properties according to rental requirements.

###  User Authentication

* User registration and login.
* Separate Owner and Tenant roles.
* Authentication and authorization for protected actions.
* Role-based access control.

###  Owner Dashboard & Property Management

* Allow property owners to create rental listings.
* Update and manage existing properties.
* Delete listings when required.
* View and manage property-related information.

###  Roommate & Flatmate Discovery

* Explore roommate and flatmate options.
* View relevant roommate information.
* Help users find potential people to share accommodation with.

###  Reviews & Ratings

* Allow authenticated users to submit property reviews.
* Provide ratings to help users make informed rental decisions.
* Display property feedback to support rental discovery.

###  Interactive Maps

* Display property locations using Leaflet.js.
* Help users understand where a property is located.

###  Image Uploads

* Upload property images.
* Display images with rental listings.
* Support visual property discovery.

###  Validation & Error Handling

* Server-side validation.
* Authentication and authorization middleware.
* Custom error-handling middleware.
* Protected routes for restricted operations.

##  Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap
* EJS (Embedded JavaScript Templates)

### Backend

* Node.js
* Express.js
* RESTful Routing

### Database

* MongoDB
* Mongoose

### Mapping & Image Management

* Leaflet.js
* Cloudinary and Multer, where configured

### Other Tools & Libraries

* Git
* GitHub
* VS Code
* Connect-Flash, where configured
* Express Session, where configured
* Method-Override, where configured

##  Architecture

The application follows the **Model-View-Controller (MVC)** architecture.

* **Models:** Define database schemas and relationships using Mongoose.
* **Views:** Render dynamic web pages using EJS templates.
* **Controllers:** Handle application logic and process requests.
* **Routes:** Define endpoints for properties, users, reviews, and related features.
* **Middleware:** Manage authentication, authorization, validation, and error handling.

## 📂 Project Structure

```text
Aligarh-Rentals/
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── utils/
├── uploads/
├── middleware.js
├── app.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

*Note: This is a general representation. Update it to match the actual folders and files in your repository. The `uploads/` folder may not be present in every configuration.*

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Ilma-gulzar21/Aligarh-Rentals.git
```

### 2. Navigate to the Project Directory

```bash
cd Aligarh-Rentals
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the project root and add the configuration required by your application.

Example:

```env
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
```

**Important:** Use the exact environment variable names expected by your application. The example above includes optional Cloudinary variables; only configure those used by your project.

Never commit your `.env` file or expose database credentials, API keys, or session secrets on GitHub.

### 5. Start the Application

If your project uses `app.js` as its entry point, run:

```bash
node app.js
```

If a start script is configured in `package.json`, you can also use the corresponding npm command.

### 6. Open in Browser

If the application runs on port `8080`, open:

```text
http://localhost:8080
```

Use the port configured in your application if it differs.

##  How It Works

1. Users visit the application and browse rental properties.
2. Tenants search and filter properties according to their requirements.
3. Users register or log in to access protected features.
4. Property owners create and manage rental listings.
5. Users view property details, images, and map locations.
6. Authenticated users can submit reviews and ratings.
7. Users can explore roommate and flatmate options.

##  Database

MongoDB is used to store application data.

Mongoose provides schema definitions, data validation, and relationships between relevant collections.

Depending on the implemented features, the database includes information related to:

* Users
* Property listings
* Reviews
* Roommate or flatmate details

## Security & Validation

The application incorporates security and validation practices such as:

* Authentication for protected operations.
* Authorization to restrict access to permitted users.
* Role-based access for Owners and Tenants.
* Server-side validation of submitted data.
* Middleware for request processing.
* Centralized error handling.
* Environment variables for sensitive configuration.

## Project Objectives

* Solve rental accommodation discovery challenges in Aligarh.
* Help students and newcomers find suitable properties.
* Provide property owners with a platform to manage listings.
* Simplify property search using filtering options.
* Support roommate discovery and rental decision-making.
* Apply full-stack development concepts in a practical project.

## Future Enhancements

Potential future improvements include:

* Online booking and rental applications.
* Payment gateway integration.
* Saved properties and favorites.
* Email and notification services.
* Advanced map-based search.
* Property availability notifications.
* Improved mobile experience.

## Developer

**Ilma Gulzar**

Master of Computer Applications (MCA)
Aligarh Muslim University (AMU)

* GitHub: [Ilma-gulzar21](https://github.com/Ilma-gulzar21)

## License

This project was developed as an academic and learning project.

---

**Aligarh Rentals — Making rental discovery easier in Aligarh.**
