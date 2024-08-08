# Health Monitor Android Application

## Project Description
The main goal of this project is to develop an Android-based health application that monitors users’ health metrics. The application is designed with a tabbed layout, providing users with an intuitive interface to manage their health data and access valuable health information.

## Key Features

### Personal Information Tab
- A signup/information collection page where users can create a profile.
- Fields to collect and display: Name, Age, Height, and Weight.
- Users can update this information at any time.

### Health Topics Tab
- A list view of links to common health topics (e.g., diet, diseases).
- Each link opens in a detailed view for more information.
- At least 5 different health-related links are provided.

### Daily Health Check Tab
- Allows users to enter daily health metrics: Blood pressure, Blood sugar level, and Calorie intake.
- Data is stored day-wise and trends (weekly, monthly, yearly) are presented.
- Users can either pick a date from the system or manually add it.

### Health Suggestions Tab
- Displays category-wise health improvement suggestions based on user-entered data.
- Offers specific advice if the blood pressure or blood sugar levels are not within the normal range, or if calorie intake is inconsistent.

## Snapshots
- **First Page**: Initial landing page.
- **Personal Info Page**: Interface for collecting and updating user information.
- **Health Topic Page**: List and detail views of health-related topics.
- **Daily Checkup Page**: Interface for daily health data entry.
- **Result Checkup Page**: Trends and suggestions based on health data.

## Technical Requirements
- Android-based application.
- Persistent data storage for user profiles and health data.
- Intuitive and user-friendly tabbed layout interface.
- Real-time data analysis and display of health trends and suggestions.

  ## Deployment Guide

### Steps to Deploy the Project on Another System

1. **Export Project**
   - In Android Studio, navigate to `File > Export > Export to ZIP file`.
   - Save the exported ZIP file.

2. **Transfer Files**
   - Move the ZIP file to the target system where you want to deploy the project.

3. **Extract Project**
   - On the target system, extract the ZIP file to your preferred directory.

4. **Open Project**
   - Launch Android Studio on the target system.
   - Select `Open an existing project` and locate the extracted project folder.

5. **Sync Gradle**
   - Android Studio will automatically sync the Gradle files.
   - Ensure that all dependencies are correctly resolved.

6. **Build and Run**
   - Click on the `Run` button to build and deploy the project on the new system.

