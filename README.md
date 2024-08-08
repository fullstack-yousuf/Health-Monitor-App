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
  ![e](https://github.com/user-attachments/assets/607c5e29-df47-4bd8-a4fd-511b61efe76e)
- **Personal Info Page**: Interface for collecting and updating user information.
  ![g](https://github.com/user-attachments/assets/3aa8f9fb-a5ce-4e72-9b63-3121c3aa5bef)
- **Health Topic Page**: List and detail views of health-related topics.
  ![d](https://github.com/user-attachments/assets/24f724cd-2649-4879-a72f-3b2fc106cdd1)
- **Daily Checkup Page**: Interface for daily health data entry.
  ![h](https://github.com/user-attachments/assets/b7e8a82a-6e59-4e54-b324-5949691c9d4e)
- **Result Checkup Page**: Trends and suggestions based on health data.
  ![F](https://github.com/user-attachments/assets/cf0b58d2-a21c-4c55-9242-4b5cd2d72408)
- **Other Page**:
  ![c](https://github.com/user-attachments/assets/f7b0ce21-728b-4912-b8d1-8a0b40aa59ad)

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

