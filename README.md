# econ-indicators-api
A RESTful API built in Laravel that manages and serves U.S. economic indicator data (GDP, CPI, unemployment rates, etc.). Designed with security, testing, Docker, and CI/CD in mind


# Economic Indicators API

A RESTful API built with Laravel for managing U.S. economic indicator data (GDP, CPI, Unemployment, etc.).

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
