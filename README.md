# LinkedIn Influencer Data Management Project
Academic Year: 2022/2023
Course: Database 

## Project Overview
This project entails the design and implementation of a relational database tailored for analyzing LinkedIn influencer data. The goal is to provide a structured storage system that accommodates extensive data related to LinkedIn posts, profiles, and activities of influencers as outlined in the dataset "LinkedIn Influencers’ Data."

## Dataset
The database structures data from the "LinkedIn Influencers’ Data" which is compiled by Shreya Sajal and Vineet Agarwal. It includes detailed records of posts, hashtags, media types, and user interactions.

## Features
- **User Profiles**: Store information such as name, location, follower count, and profile description.
- **Posts**: Manage details about each post including hashtags used, post content (excluding hashtags), and links within the post.
- **Media Association**: Each post can include media such as images, videos, surveys, articles, or documents.
- **Analytics**: Capture an overview of interactions per post, including likes, comments, views, and survey votes.

## Database Structure
- **Schema Design**: Based on an extensive conceptual design utilizing ER diagrams and design patterns like Entity Attribute Reification and Recursive Relationship Reification.
- **Logical Design**: Refined ER schemas leading to a robust logical structure optimized for performance and normalization up to the Boyce-Codd Form.
- **SQL Implementation**: Comprehensive SQL scripts for database creation, population, and manipulation.

## Installation
1. Ensure PostgreSQL is installed and running on your system.
2. Clone this repository to your local environment.
3. Run the SQL creation and population scripts located in the `sql_scripts` directory to set up the database schema and populate it with initial data.

## Documentation
- **Data Dictionary**: Detailed descriptions of each table and relationship in the database are available in the `docs` folder.
- **Schema Diagrams**: ER diagrams and restructured schemas can be found in the `diagrams` folder, illustrating the database design and relationships.

## Usage
- Utilize provided SQL queries to perform data insertion, updates, and complex analytics.
- Example queries for common data retrieval scenarios are included in the `examples` directory.

