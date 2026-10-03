# Cinema E-Booking System

Welcome to the **Cinema E-Booking** site! This application is a mock theatre website where users can browse movies, view trailers, and book tickets for available showings. The system also provides administrative functionality for managing the movie catalog and keeping current and upcoming showings up to date.

## Overview

The Cinema E-Booking System is designed to simulate an online movie-ticket booking platform. Users can browse movies that are **Now Showing** or **Coming Soon**, search for movies by title or genre, watch movie trailers, and book tickets for available showings.

Administrators have additional privileges that allow them to manage the movie catalog by adding new movies, editing existing movie information, and deleting movies from the site.

## Features

### User Features

* Browse movies that are currently **Now Showing**
* Browse movies that are **Coming Soon**
* Search for movies by:

  * Title
  * Genre
* View movie information
* Watch movie trailers
* Select available showings
* Book movie tickets through the booking system

### Admin Features

Administrators can manage the movies available on the website:

* **Add** new movies
* **Edit** existing movie information
* **Delete** movies
* Keep the movie catalog and showings up to date

## Application Structure

The application provides two primary types of functionality:

```text
Cinema E-Booking System
│
├── User
│   ├── Browse Movies
│   ├── Search Movies
│   ├── View Movie Details
│   ├── Watch Trailers
│   └── Book Tickets
│
└── Admin
    ├── Add Movies
    ├── Edit Movies
    └── Delete Movies
```

## Getting Started

### Prerequisites

Make sure you have **Node.js** and **npm** installed on your system.

You can verify your installation with:

```bash
node --version
npm --version
```

### Running the Application

Install the project dependencies if needed:

```bash
npm install
```

Then start the application using:

```bash
npm run start:all
```

The application will start the required components for the Cinema E-Booking System.

## Movie Browsing

The site separates movies into two categories:

### Now Showing

Movies currently available for users to view and book.

Users can select a movie to view its information, watch its trailer, and proceed with ticket booking for an available showing.

### Coming Soon

Movies that are scheduled to be available in the future.

These movies allow users to explore upcoming releases before they become available for booking.

## Movie Search

Users can search the movie catalog to quickly find movies they are interested in.

Search functionality supports:

* **Movie title**
* **Movie genre**

This allows users to narrow down the available movies without manually browsing the entire catalog.

## Movie Trailers

Users can watch trailers for movies they are interested in before deciding whether to book tickets.

The trailer functionality provides users with additional information about the movie and its content.

## Ticket Booking

The application allows users to select a movie and book tickets for an available showing.

A typical booking workflow is:

```text
Browse Movies
     │
     ▼
Select Movie
     │
     ▼
View Movie Details
     │
     ▼
Watch Trailer
     │
     ▼
Select Showing
     │
     ▼
Book Tickets
```

## Administration

The administrative portion of the application allows authorized administrators to maintain the movie catalog.

The basic movie-management workflow is:

```text
             Admin
               │
       ┌───────┼────────┐
       ▼       ▼        ▼
     Add      Edit     Delete
    Movie    Movie     Movie
       │       │        │
       └───────┼────────┘
               ▼
        Updated Catalog
```

This allows the website's movie listings to remain current as movies are added, updated, or removed.

## Running the Project

The primary command for running the complete application is:

```bash
npm run start:all
```

If dependencies have not yet been installed, run:

```bash
npm install
npm run start:all
```

## Example User Workflow

A typical user interaction with the site might look like:

```text
1. Open the Cinema E-Booking website
2. Browse "Now Showing" movies
3. Search for a movie by title or genre
4. Select a movie
5. View movie information
6. Watch the trailer
7. Select an available showing
8. Book tickets
```

## Example Admin Workflow

An administrator can maintain the movie catalog by:

```text
1. Log in as an administrator
2. Open the movie management section
3. Add a new movie
       OR
   Edit an existing movie
       OR
   Delete a movie
4. Save the changes
5. Verify that the movie catalog is updated
```

## Technologies

The project is run using the **Node.js/npm** environment. The complete technology stack and individual framework versions depend on the project's configuration.

## Summary

The Cinema E-Booking System is a mock online theatre platform that combines movie discovery with ticket booking functionality. Users can browse current and upcoming movies, search by title or genre, watch trailers, and book tickets. Administrators can manage the movie catalog by adding, editing, and deleting movies.

### Quick Start

```bash
npm install
npm run start:all
```

