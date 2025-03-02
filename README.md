Investment Management App

🚀 Overview

Investment Management App is a portfolio and investment tracking web application that allows users to:

✅ Create and manage portfolios.

✅ Track and analyze investments.

✅ Set favorite portfolios for easy access.

✅ Calculate total portfolio value and view percentage-based distribution of investments.

The application follows a secure authentication system using JWT and HttpOnly cookies. It also provides an intuitive user interface using Thymeleaf and Bootstrap.

🚀 Features

✅ User Authentication & Authorization

<img width="1434" alt="Screenshot 2025-03-02 at 15 14 57" src="https://github.com/user-attachments/assets/14da2515-e966-4d25-90d1-c4cee3484c0f" />


✅ Secure user registration and login.

✅ JWT-based authentication with HttpOnly cookies.

✅ Spring Security ensures protected API endpoints.

✅ BCrypt password hashing for enhanced security.

🚀 Portfolio Management

<img width="1432" alt="Screenshot 2025-03-02 at 15 20 53" src="https://github.com/user-attachments/assets/8400e50f-cacd-43ac-a1cf-d452a8857a23" />

✅ Create, view, and delete portfolios.

✅ Mark portfolios as favorites for quick access.

✅ View a categorized list of favorite and other portfolios.

✅ Each portfolio has a dedicated investment tracking page.

🚀 Investment Management
<img width="1433" alt="Screenshot 2025-03-02 at 15 22 56" src="https://github.com/user-attachments/assets/4270b3e6-8fcf-454f-9a5d-d395109e5a19" />

✅ Add investments to portfolios with quantity and price details.

✅ View all investments within a portfolio.

✅ Delete investments when needed.

✅ Automatic total portfolio value calculation.

✅ Percentage-based distribution of investments within a portfolio.

🚀 Security

✅ HttpOnly cookies for JWT token storage (no LocalStorage).

✅ Stateless authentication with Spring Security.

✅ Input validation for forms to prevent invalid entries.

🚀 Pages & Functionalities

1️⃣ Portfolio Management Page (my-portfolios.html)
This is the main dashboard where users can create, view, and manage their portfolios.

Features:

✅ Add a new portfolio using a simple input form.

✅ View all portfolios in two sections:
Favorite Portfolios (Marked as primary by the user).
Other Portfolios (Non-primary portfolios).

✅ Access the investments of a portfolio via a dedicated button.

✅ Mark/unmark portfolios as favorites.

✅ Delete portfolios when no longer needed.


2️⃣ Investment Tracking Page (investments.html)
This page is portfolio-specific and allows users to track investments within a selected portfolio.

Features:
✅ View the total value of a portfolio (automatically calculated).

✅ Visualize percentage-based investment distribution using a list and progress bars.

✅ Add new investments by entering:

Investment name

Quantity

Price

✅ View all investments with:

Investment name

Quantity and price

Total value

Created and last updated timestamps

✅ Delete an investment when no longer needed.

Technologies Used

Backend
Java 17

Spring Boot 3

Spring Security (authentication & authorization)

Spring Data JPA (database access)

PostgreSQL (production database)

JWT Authentication

BCrypt Password Hashing

Frontend

Thymeleaf (dynamic HTML rendering)

Bootstrap 5 (UI styling & responsiveness)

JavaScript & AJAX (dynamic updates)

Build & Deployment

Maven (dependency management)

Spring Boot DevTools (hot-reloading)
