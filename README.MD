# Student Portal
## Overview
A Student Portal Web App for managing courses, grades, attendance and mess bookings.
## Requirements
- C++ compiler with C++17 support (e.g., g++, clang++, MSVC)
- CMake >= 3.10 (optional)
## Installation
```bash
git clone https://github.com/neel-d9/student-portal.git
cd student-portal
g++ -std=c++17 src/app.cpp -o app
```
## Running the App
```bash
./app
```
## Project Structure
- /src - application source code
- /tests - unit and integration tests
- /docs - additional documentation
## Contributing
Please open a feature branch and submit a pull request for review.
## Login Module
Handles credential validation, lockouts, and session tokens.
## Profile Module
Manages user profile data and avatars.
## Dashboard Module
Shows enrolled courses, grades, and notifications.
## Settings Module
Handles user preferences and password management.
## Roadmap
- CSV export for grades (in progress)