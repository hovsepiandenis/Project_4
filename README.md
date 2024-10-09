# Project_4
Smart Data
Movie Database System
Overview
This project is a comprehensive Movie Database System designed to manage and organize a wide range of information related to movies, actors, directors, genres, awards, and users. The system aims to facilitate the storage, retrieval, and manipulation of data, enabling efficient management for both users and administrators. The database is structured to handle various relationships between entities like movies, actors, and awards, along with tracking user subscriptions and watched movies.

The project is ideal for applications such as online streaming platforms, movie rental services, or a detailed movie catalog system for cinema enthusiasts.

Database Schema
The system comprises 17 interconnected tables, each capturing essential elements of the movie ecosystem:

Actor: Contains actor details including their first name, last name, nationality, and birth date.

Director: Stores information about movie directors, including their first name, last name, nationality, and birth date.

Movie: This central table captures movie details like the title, release year, director, rating, movie length, language, and the country of origin.

Genre: Defines different movie genres such as Action, Drama, Comedy, etc.

Award: Holds information about movie awards, including the name of the award (e.g., Oscars, Golden Globes).

Actor Award: Tracks awards won by actors, specifying the actor, the movie they won the award for, and the year the award was received.

Movie Actor: A many-to-many relationship table linking movies to the actors who starred in them.

Movie Genre: Maps movies to their respective genres.

Language: Stores the language details of the movies.

Country: Captures the country of origin of movies.

User: Stores user details such as first name, last name, nationality, birth date, email, and password.

Subscription Plan: Defines various subscription plans available to users, including price, duration, and a description of the plan.

Subscriptions: Tracks active and inactive subscriptions of users, with details such as the start and end date of the subscription.

Watched Movies: Records details of movies watched by users, including the date of viewing and the subscription plan used.

Key Features
Actor and Director Management: Allows easy management and retrieval of information related to actors and directors, along with their awards.

Movie Information: Provides comprehensive movie details including ratings, genres, directors, and associated actors.

Genre and Language Categorization: Enables filtering of movies by genre and language, making it easier for users to find content they are interested in.

User Subscription System: Tracks user subscriptions, allowing users to select different subscription plans and manage their viewing history.

Watch History: Tracks the history of watched movies for each user, linking it to their active subscription plan.

Usage
This database system can be used in several real-world applications such as:

Online Movie Streaming Platforms: Managing users, subscriptions, and viewing history.
Cinema Management Systems: Tracking movies, actors, and awards for a specific region or globally.
Movie Recommendation Systems: Using the rich metadata to recommend movies based on genres, actors, or user preferences.
Technologies
Database: Designed using SQL relational database systems.
Entities: The database consists of multiple interrelated tables that support normalized data storage and efficient querying.
