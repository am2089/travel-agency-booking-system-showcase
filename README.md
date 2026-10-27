# Travel Agency Booking System

A Java Spring Boot backend for a vacation booking application, completed as part of my Software Engineering degree at Western Governors University.

The application uses an Angular frontend and a MySQL database to manage customers, vacation packages, excursions, shopping carts, and purchases.

## Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- MySQL
- REST APIs
- Angular (provided frontend)

## What I Worked On

The project started with an existing application structure. My responsibility was to implement the backend functionality needed to support the booking and checkout process.

I worked on:

- Creating REST endpoints to communicate with the Angular frontend.
- Setting up JPA entities and relationships for customers, vacations, excursions, and shopping carts.
- Using Spring Data JPA repositories to handle database operations.
- Implementing checkout logic with `@Transactional` to save orders and generate unique tracking numbers.
- Connecting the backend to MySQL for persistent storage.

## How It Works

The Angular frontend sends requests to the Spring Boot backend, which handles the application logic and communicates with MySQL through Spring Data JPA.

When a customer completes a purchase, the checkout service processes the cart, saves the order information, and returns a tracking number.

## About the Repository

This project was completed for WGU's D288 Back-End Programming course.

The original source code is kept private because of coursework distribution restrictions. This repository provides an overview of the project and the backend functionality I implemented.
