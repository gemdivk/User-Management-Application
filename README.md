# User Management Application

This is a user management application built with **Node.js**, **Express**, and **MongoDB**. The application allows you to manage users, including performing CRUD operations (Create, Read, Update, and Delete). It also provides some additional features, such as filtering users by name or age and displaying a chart showing the age distribution of users.

## Features

- **CRUD Operations**: Create, Read, Update, and Delete users.
- **Filtering**: Filter users by name and age.
- **Age Distribution Chart**: A bar chart showing the number of users in different age groups (e.g., 10-19, 20-29, etc.).
- **Responsive Design**: Optimized for desktop and mobile views.

## Technologies Used

- Node.js
- Express.js
- MongoDB (with Mongoose)
- Chart.js (for data visualization)
- HTML, CSS, and JavaScript

## Installation and Setup

### Prerequisites

Before running the app locally, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [MongoDB](https://www.mongodb.com/try/download/community) (running locally or using a cloud instance like MongoDB Atlas)

### Steps to Install and Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/gemdivk/User-Management-Application.git
   cd User-Management-Application
   ```

2. **Install the dependencies**:
   ```bash
   npm init -y
   npm install express mongoose body-parser
   npm install express mongoose body-parser cors

   ```

3. **Start the MongoDB server** (if you're running MongoDB locally):
   ```bash
   mongod
   ```

4. **Start the Node.js server**:
   ```bash
   node server.js
   ```

5. The application will be running at `http://localhost:3000`. You can open this URL in your browser.

## CRUD Operations

The application supports the following CRUD operations for users:

### Create a New User

1. Fill out the form in the **Add User** section with the user's **Name**, **Email**, and **Age**.
2. Click **Add User** to create a new user. The user will be added to the database.
   ![screen](/screenshots/screen1.jpg)   

### Read All Users

1. All users are displayed in a table with their **Name**, **Email**, and **Age**.
2. You can filter users by name or age using the filter options provided above the table.
   ![screen](/screenshots/screen2.jpg)

### Update a User

1. Click the **Edit** button next to the user you want to update.
2. You will be prompted to enter a new **Name**, **Email**, and **Age** for the user.
3. Once updated, the user's information will be reflected in the table.
   ![screen](/screenshots/screen3.jpg)


### Delete a User

1. Click the **Delete** button next to the user you want to remove.
2. The user will be deleted from the database, and the table will automatically update.
   ![screen](/screenshots/screen4.jpg)

## Additional Features

### Filtering by Name and Age

You can filter the list of users based on their **Name** and **Age**:

- Enter a **Name** in the "Filter by Name" field to search for users by their name.
- Enter an **Age** in the "Filter by Age" field to filter users by their age.
- After applying the filter, the table will update to display only the users matching the criteria.
  ![screen](/screenshots/screen5.jpg)
### Age Distribution Chart

The **Age Distribution** chart shows the number of users in different age ranges. The age groups are divided into ranges such as 10-19, 20-29, 30-39, etc. The chart updates dynamically as users are added or removed, providing a visual representation of the user age distribution.
![screen](/screenshots/screen6.jpg)


