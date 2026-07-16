# econ-indicators-api
A RESTful API built in Laravel that manages and serves U.S. economic indicator data (GDP, CPI, unemployment rates, etc.). Designed with security, testing, Docker, and CI/CD in mind


# Economic Indicators API

## A Sample simple Demo RESTful API built with Laravel for managing U.S. economic indicator data (GDP, CPI, Unemployment, etc.).

## Features
- RESTful CRUD API for indicators and time-series data points
- Seeded with 10,000+ data points for large dataset handling
- Laravel Sanctum API authentication
- Rate limiting (60 req/min) per OWASP best practices
- 508-compliant Blade view for accessible data browsing
- Dockerized with PostgreSQL
- GitLab CI/CD pipeline with automated testing
- Comprehensive feature tests

## Tech Stack
PHP 8.3, Laravel 11, PostgreSQL, Docker, GitLab CI

## Quick Start
```bash
docker-compose up -d
docker-compose exec app php artisan migrate:fresh --seed
# API: http://localhost:8080/api/indicators
# View: http://localhost:8080/indicators
```
<img width="547" height="477" alt="Laravel" src="https://github.com/user-attachments/assets/7f443929-d09f-4ed8-81d5-44284246044f" />

## Laravel Index Page

<img width="1399" height="988" alt="Laravel_index_page" src="https://github.com/user-attachments/assets/04419cb5-0af1-4b8c-9ce6-ad44e0c7300f" />

## Laravel Registration Page
<img width="1428" height="963" alt="Laravel_registration_page" src="https://github.com/user-attachments/assets/21ffd07c-dbbc-4775-bcab-d94b0c7b14a6" />

## Laravel Login Page
<img width="1425" height="989" alt="Laravel_Loging_page" src="https://github.com/user-attachments/assets/bec3ce53-7bde-4c20-bb7f-c0009f4ca757" />

## Dashboard Page

<img width="1496" height="998" alt="Laravel_Dashbord" src="https://github.com/user-attachments/assets/1c6e5224-ee2f-4bb2-a59c-f64b17730675" />

## User Profile setting Page
<img width="1498" height="994" alt="Laravel_user_profile" src="https://github.com/user-attachments/assets/908c897f-ef46-4ee9-8797-43ad83cb567a" />












