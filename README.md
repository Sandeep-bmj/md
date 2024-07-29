# Docker-Compose Setup Menu

<img width="866" alt="image" src="https://github.com/user-attachments/assets/7e400be4-3057-48c0-ba5f-c2fb262042ce">

This document provides an overview of the Docker-Compose Setup Menu, which allows users to manage their Docker containers and related tasks via a simple text-based interface.
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

###  Change URL in Database
You can access your MySQL database through phpMyAdmin and Run the following SQL queries:
```
UPDATE wp_options SET option_value = 'http://localhost:9000/' WHERE option_name = 'home';
UPDATE wp_options SET option_value = 'http://localhost:9000/' WHERE option_name = 'siteurl';
```


