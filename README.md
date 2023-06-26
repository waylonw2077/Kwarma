
Project Presentation: Kwarma Mod Manager

Introduction:
Welcome to the presentation of my project, the Kwarma Mod Manager. This full-stack application combines a Flask backend with a React frontend. The purpose of this project is to demonstrate my acquired skills, prepare for future capstone projects, and enhance my portfolio.

Project Overview:
The Kwarma Mod Manager aims to simplify mod management for The Elder Scrolls V: Skyrim. It provides users with a platform to discover, download, and organize mods while facilitating sharing within the community. The focus of this project is to implement essential features and meet the specified user stories.

User Stories:
To fulfill the project requirements, I have defined the following user stories:

MVP User Stories:

User Registration: Users can sign up for an account.
User Authentication: Users can log in and remain logged in.
User Logout: Users can log out from the application.
Mod Listing: Users can view a list of available mods and their details.
Mod Downloading: Users can download mods and add them to their collection.
Mod Reviews: Users can create mod reviews and provide ratings.
Review Management: Users can modify or delete their own mod reviews.
Mod Uploading: Users can upload and share their own mods with the community.
Stretch User Stories:

Mod Search: Users can search for mods based on specific criteria.
Mod Filtering: Users can filter mods based on average rating.
Models and Relationships:
For data representation, I have designed three models with appropriate relationships:

User: Represents a registered user of the application.
Mod: Represents a mod uploaded by a user, including details and associated reviews.
Review: Represents a user's review of a specific mod.
The relationships between these models are as follows:

A User can have many Mods (one-to-many).
A Mod can have many Reviews (one-to-many).
A User can have many Reviews, and a Review belongs to a User (reciprocal many-to-many).
Execution Approach:
To ensure a systematic approach, I followed a feature-based methodology. Instead of working across different layers, I focused on implementing each feature in its entirety. This allowed for the development of fully functional features and minimized the need for rework.

The execution approach involved the following steps:

Migrations: Setting up the necessary database tables and relationships.
Models: Defining the data models and establishing their relationships.
Seed Data: Populating the database with sample data for testing and demonstration purposes.
Controller Actions: Implementing the backend logic to handle CRUD actions for each resource (User, Mod, Review).
View Logic: Developing frontend components and views to interact with the API endpoints.
Data Fetching: Connecting the frontend and backend using fetch() to retrieve and update data.
Styling: Applying CSS styles to create an intuitive and visually appealing user interface.
Background and Motivation:
The choice of developing a mod manager stems from my initial interest in coding, which was sparked by modding The Elder Scrolls V: Skyrim.

Conclusion:
In conclusion, the Kwarma Mod Manager is a full-stack application that simplifies mod management for The Elder Scrolls V: Skyrim. By utilizing a Flask backend and a React frontend, this project demonstrates my skills as a developer and serves as a valuable addition to my portfolio.
