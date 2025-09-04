# Django Pet Clinic Application

This is a Django-based Local Pet Clinic Application project.

## Features

    Owner Management: Add new owners, view their details, update their information, and search for specific owners.

    Pet Management: Add new pets and associate them with their owners, edit pet details (name, birth date, type), and view a pet's complete profile.

    Visit/Appointment Tracking: Schedule new visits (appointments) for pets, record the reason for the visit, and view a complete history of all past visits for a specific pet.

    Veterinarian Management: Add new veterinarians to the clinic and assign them specialities.


## Installation

Follow these steps to set up and run the Django Pet Clinic Application:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/GGurol/petclinic.git
   ```

2. Navigate to the project directory:

   ```bash
   cd petclinic
   ```

3. Build the docker and build:

   ```bash
   docker compose up --build -d
   ```

4. Apply database migrations:

   ```bash
   docker compose exec web python manage.py makemigrations
   docker compose exec web python manage.py migrate
   ```

5. Create a superuser to access the admin interface:

   ```bash
   docker compose exec web python manage.py createsuperuser
   ```

6. Access the application in your web browser at `http://localhost:8000`.


