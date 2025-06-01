# ALX Travel App (0x00)

This is a Django-based travel booking application built for educational purposes.
It includes models for listings, bookings, and reviews, along with API serializers and a seed script for populating sample data.

## Features

- 📌 Listings with destination details
- 📅 Bookings for listed destinations
- ⭐ User reviews for listings
- 🔄 Seed command to generate sample data
- ✅ SQLite database (no external DB required)

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/alx_travel_app_0x00.git
   cd alx_travel_app_0x00/alx_travel_app

2.Create and activate virtual environment
    - python -m venv ../env
    - ../env/Scripts/activate  # or source ../env/bin/activate (Linux/macOS)
3. Run migrations
- python manage.py makemigrations
- python manage.py seed