# Docker-Compose Setup Menu

<img width="866" alt="image" src="https://github.com/user-attachments/assets/7e400be4-3057-48c0-ba5f-c2fb262042ce">
<hr style="border: 2px solid red; margin-top: 20px; margin-bottom: 20px;">
This document provides an overview of the Docker-Compose Setup Menu, which allows users to manage their Docker containers and related tasks via a simple text-based interface.
<hr style="border: 2px solid red; margin-top: 20px; margin-bottom: 20px;">
---
## Menu Options

1. **Option A - Run the Lunch Environment**
   - **Description:** Starts the Docker containers for the lunch environment.
   - **Usage:** Initializes all related containers.

2. **Option B - Display All Container Statuses**
   - **Description:** Displays the current status of all Docker containers.
   - **Usage:** Get a quick overview of the state of your containers.

3. **Option C - Stop the Lunch Environment**
   - **Description:** Stops all Docker containers related to the lunch environment.
   - **Usage:** Safely shut down the environment when no longer needed.

4. **Option D - Run Backup of the MySQL Database**
   - **Description:** Creates a backup of the MySQL database.
   - **Usage:** Regularly back up your MySQL database to prevent data loss.

5. **Option E - Run Backup of the WordPress Files**
   - **Description:** Creates a backup of the WordPress files.
   - **Usage:** Ensure your WordPress site can be restored in case of issues.

6. **Option F - Remove All Lunch Containers**
   - **Description:** Removes all Docker containers associated with the lunch environment.
   - **Usage:** Clean up and free resources.

7. **Option G - List All SQL Files**
   - **Description:** Displays a list of all SQL files available in the specified directory.
   - **Usage:** Identify available SQL scripts for various tasks.

8. **Option H - List All Backup Files**
   - **Description:** Displays a list of all backup files available in the specified directory.
   - **Usage:** Manage and restore backups.

9. **Option I - Display Monitor Logs**
   - **Description:** Shows logs from the monitoring system.
   - **Usage:** View monitoring logs and troubleshoot any issues with your environment.

10. **Option J - Exit Safely from This Setup**
    - **Description:** Safely exits from the setup menu, ensuring necessary cleanup operations are performed.
    - **Usage:** Exit the setup menu safely when done.

11. **Option K - User Manual**
    - **Description:** Provides additional help and information about the menu options and their usage.
    - **Usage:** View detailed help and instructions for using the menu.

12. **Option O - Open Web to Launch Site and Database**
    - **Description:** Opens the web interface to launch the site and database.
    - **Usage:** Access the site and database through the web interface for further interaction.

13. **Option Q - Exit Normally**
    - **Description:** Exits the setup menu immediately without performing additional operations.
    - **Usage:** Quickly exit the setup menu.
---
## Usage

The menu is displayed line by line in cyan color to enhance readability. Users are prompted to enter their choice from the available options.

### Enter this command to start the program.
- **Open the Git Bash terminal and execute this command to start the program.** ``` sh main.sh ``` 

<img width="908" alt="image" src="https://github.com/user-attachments/assets/481522bf-a61d-4cee-975e-a11703c81e2d">

- **For example, press option 1.**
- Starts the Docker containers for the lunch environment.

<img width="911" alt="image" src="https://github.com/user-attachments/assets/8f06cded-60ce-43d2-bd27-12af8839fe03">

- Check the running status of all containers after opening Docker Desktop.
<img width="956" alt="image" src="https://github.com/user-attachments/assets/cc27e954-f2a3-44a7-a2d6-35bbed775f71">

- **Press Option 2**
- Presents the real-time status of all Docker containers.
  <img width="897" alt="image" src="https://github.com/user-attachments/assets/e47b67ef-cfd4-4013-b396-9d1dfc55d11c">
- You can view all WordPress files, MySQL files, and the database set up locally.
<img width="182" alt="image" src="https://github.com/user-attachments/assets/5bee96b1-ca19-4471-ba64-c74e439d86dd">
<img width="182" alt="image" src="https://github.com/user-attachments/assets/40fd348d-b287-41e0-9d39-2ad0b9e1629c">

- **Press  Option 3**
- Stops all Docker containers related to the lunch environment.
  <img width="950" alt="image" src="https://github.com/user-attachments/assets/fb14bef3-3c8d-43f6-bc3d-2ab76a9949a3">

- **Press Option 6**
- Removes all Docker containers associated with the lunch environment
  <img width="947" alt="image" src="https://github.com/user-attachments/assets/aace85ca-92de-4136-ab91-aad4874c7439">

- **Press Option 13**
- Exits the setup menu immediately without performing additional operations.
<img width="601" alt="image" src="https://github.com/user-attachments/assets/ec9ebdcc-a025-4569-8c0d-724a3457ae00">

- **Press Option 12**
- Safely exits the setup menu, ensuring necessary cleanup operations are performed and creating backups of WordPress files and the SQL database.
<img width="479" alt="image" src="https://github.com/user-attachments/assets/3b8c8f38-7718-4795-90d5-9ecb23901159">


## You can utilize the options based on your specific requirements.

###  Change URL in Database
You can access your MySQL database through phpMyAdmin and Run the following SQL queries:
```
UPDATE wp_options SET option_value = 'http://localhost:9000/' WHERE option_name = 'home';
UPDATE wp_options SET option_value = 'http://localhost:9000/' WHERE option_name = 'siteurl';
```

- **Press Option 7**
- Opens the web interface to launch the site and database.
  <img width="674" alt="image" src="https://github.com/user-attachments/assets/dfdd0049-8498-4a2d-b591-4c6d86786759">

- **Launch the WordPress site and phpMyAdmin page in Microsoft Edge**
- **WordPress Site**
  <img width="958" alt="image" src="https://github.com/user-attachments/assets/01c67896-ba81-4586-8753-d338a60b1f02">
  <img width="957" alt="image" src="https://github.com/user-attachments/assets/e82a36fe-158f-40c2-881c-dc2f9ecf28ee">

- **PhpMyAdmin Page**
  <img width="958" alt="image" src="https://github.com/user-attachments/assets/46cc6162-5640-450f-bbd0-bf2ce9fe3cd1">
  <img width="959" alt="image" src="https://github.com/user-attachments/assets/5b5ae6cf-d2dc-4bb5-bafe-c47071c51a16">

      


