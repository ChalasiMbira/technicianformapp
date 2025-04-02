# Create README.md

# Technician Form Application

A simple web application for technicians to submit installation/activation details and for admins to manage submissions.

## Structure
- 'src/index.html': Technician form page
- 'src/admin.html': Admin dashboard page
- 'docs/`: Documentation (currently empty)

## Features
- Technician form with photo upload and comment option
- Admin dashboard with user creation, submission viewing, and Excel export with embedded images
- Base64 to image conversion tool

## Setup
1. Open 'index.html' or 'admin.html' in a browser for local testing.
2. For production, deploy to a static hosting service (e.g., GitHub Pages) and consider a backend for scalability.

## Limitations
- Uses 'localStorage', limited to ~100-200 images (5-10MB).