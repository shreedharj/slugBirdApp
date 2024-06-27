# Project: BirdTracker App

## Overview

BirdTracker is a comprehensive bird-watching application designed to facilitate bird enthusiasts in tracking and managing their bird sightings. The application provides features such as creating checklists, viewing existing checklists, and managing user data related to bird sightings. The project utilizes Py4web for the backend and Vue.js for the frontend, styled with Bulma.

## Demo

Watch the demo of the application here: [YouTube Demo](https://www.youtube.com/watch?v=bywouthMIcY&ab_channel=ShreedharJangam)

## Features

- **Create Checklists**: Users can create new checklists by adding bird species and their counts.
- **View Checklists**: Users can view all their checklists, including details such as species names, counts, date, time, and location of the sightings.
- **Edit Checklists**: Users can edit existing checklists to update the bird species counts and other details.
- **Delete Checklists**: Users can delete checklists they no longer need.
- **Search Species**: Users can search for bird species while creating or editing checklists.

## Project Structure

- `controllers/`
  - `controllers.py`: Contains the main application logic and route handling.
  - `controllers_checklists.py`: Handles routes and logic specific to checklists.
  - `controllers_location.py`: Handles routes and logic specific to location data.
  - `controllers_stats.py`: Handles routes and logic for user statistics.

- `models/`
  - `models.py`: Defines the database models for the application.

- `static/`
  - `js/`: Contains JavaScript files used in the application.
    - `checklists.js`: Manages the checklist creation and editing logic.
    - `my_checklists.js`: Handles the display and management of user checklists.
  - `css/`: Contains CSS files for custom styling.

- `templates/`
  - `layout.html`: The main layout file for the application.
  - `checklists.html`: Template for creating and editing checklists.
  - `my_checklists.html`: Template for displaying user checklists.

- `translations/`: Contains translation files for the application.

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/slugBirdApp.git
2. Navigate to the project directory:
   ```bash
   cd slugBirdApp
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
4. Run the application
    ```bash
    ./py4web.sh

## Usage

### Creating a Checklist:
1. Navigate to the "Enter Checklist" page.
2. Search for bird species and add them to the checklist.
3. Enter the date, time, and location of the sightings.
4. Click "Submit Checklist" to save the checklist.
### Viewing Checklists:
1. Navigate to the "My Checklists" page.
2. Click on a checklist to view its details.
3. Expand the checklist to see the species and their counts.
### Editing a Checklist:
1. On the "My Checklists" page, click the "Edit" button next to the checklist you want to edit.
2. Update the species counts and other details as needed.
3. Click "Submit Checklist" to save the changes.
### Deleting a Checklist:
1. On the "My Checklists" page, click the "Delete" button next to the checklist you want to delete.
2. Confirm the deletion.

## Collaborators
- Shreedhar Jangam: Worked on checklists. Responsible for implementing the checklist creation, viewing, and editing functionalities.
- Vibhu: Worked on the index page. Ensured a smooth and user-friendly landing page experience.
- Alec: Worked on location management. Implemented the features related to tracking and displaying location data.
- Om: Worked on user statistics. Handled the logic and display of user statistics within the application.

## Conclusion
This project was a collaborative effort to create a functional and user-friendly bird-watching application. Each team member contributed significantly to different parts of the project, ensuring a high-quality and cohesive final product. The application is designed to enhance the bird-watching experience by providing an easy way to manage and track bird sightings.

For more details, refer to the demo video linked above.
