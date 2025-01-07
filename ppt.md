
# Presentation: GitHub Actions CI/CD Pipeline and Docker-Based WordPress Setup

## Slide 1: Title Slide
**Title:**
- GitHub Actions CI/CD Pipeline 
- WordPress Setup for Local Development & Testing

**Subtitle:**
- Using a Containerization Approach with Docker & Docker Compose

**Presenter:**
- Sandeep Kumar Patel  
- Platform Team

---

## Slide 2: Introduction
**Title:** Welcome
- **Hello, everyone!** Good morning and good afternoon.
- **Introduction:** 
  - My name is Sandeep Kumar Patel.
  - I work with the Platform Team, closely collaborating with the Web Development and Marketing Team.
- **Objective of the Session:**
  - Demonstrate the GitHub Actions CI/CD Pipeline.
  - Showcase WordPress Local Development and Testing Setup using Docker.

---

## Slide 3: Agenda
1. Overview of GitHub Actions (GHA) Implementation.
2. Key Milestones Achieved.
3. Live Demo of the Setup and Deployment Process.
4. Docker-Based WordPress Local Development Setup.
5. Questions & Discussion.

---

## Slide 4: Milestones Achieved
**Phase One Completed:**
- GHA enabled for all WordPress sites.
- Unified, automated, and reliable CI/CD pipeline.

**Next Phase:**
- Automate GitHub tags, releases, and release notes.
- Improved versioning and documentation.
- Enhanced transparency in release processes.

---

## Slide 5: GitHub Actions Workflow
**Title:** First Phase: GHA CI/CD Pipeline

**Before GHA:**
- Fragmented deployment processes.
  - Jenkins for some sites.
  - FTP-based deployments for others.
- Challenges: delays, errors, inefficiencies.

**With GHA:**
- Unified CI/CD pipeline.
- Standardized and automated deployments.

---

## Slide 6: GHA Workflow Stages
**Steps:**
1. Create a branch for the ticket and implement changes.
2. Submit a Pull Request (PR) to the master branch and assign reviewers.
3. **Staging Pipeline:** Automatically updates the staging site.
4. Changes validated by Developers and QA Team.
5. **Production Pipeline:** Merges PR into the master branch, triggering the final deployment.

**Reference Link:** [CI/CD GHA Workflow Notion Page](https://www.notion.so/bmjgroup/CI-CD-GHA-in-Web-Development-and-Marketing-Teams-14c3e9f14398804682acd34cb728d02d)

---

## Slide 7: Demo Time!
**Title:** Demo: GHA Workflow in Action
- Overview of Phase One accomplishments.
- Live demonstration of the CI/CD pipeline.

---

## Slide 8: Second Phase: Docker Containerization
**Title:** WordPress Local Development & Testing

**Advantages:**
- No need for manual installations or software (XAMPP, MAMP, etc.).
- Quick, efficient, and ready-to-use setup.
- Seamless operation across systems.

**Components:**
1. **WordPress Container:** Hosts the application.
2. **MySQL Container:** Manages the database.
3. **phpMyAdmin Container:** GUI for database management.

---

## Slide 9: Pre-requisites
**Verify Docker Installation:**
1. Check Docker: `docker --version`.
2. Check Docker Compose: `docker-compose --version`.

**Ensure Sudo Privileges:**
- Execute setup with administrative access.

---

## Slide 10: Getting Started with Docker Setup
**Instructions:**
1. **Clone the Repository:**
   - [wp-docker-compose-poc](https://github.com/BMJ-Ltd/wp-docker-compose-poc)

2. **Navigate to the Setup Folder:**
   - `cd basic-wordpress-setup`

3. **Run the Setup:**
   - `docker-compose up -d`

4. **Access the WordPress Site:**
   - `http://localhost:8081`

5. **Access phpMyAdmin:**
   - `http://localhost:8080`

**Reference Link:** [WordPress Docker Setup Notion Page](https://www.notion.so/bmjgroup/Containerized-WordPress-Setup-for-Local-Development-and-Testing-1723e9f143988060839ac75d2d067353)

---

## Slide 11: Demo Time!
**Title:** Demo: WordPress Docker Setup
- Live demonstration of the local WordPress development environment.

---

## Slide 12: Q&A
**Title:** Questions & Discussion
- Open floor for queries.
- Suggestions and feedback.

**Closing Note:**
- Let’s continue working together to optimize our workflows for success!

---


