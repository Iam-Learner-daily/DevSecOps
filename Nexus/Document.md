# 📘 What is Nexus?

Nexus is a powerful repository manager used for storing, managing, and retrieving build artifacts and dependencies. It plays a vital role in software development by serving as a centralized platform that simplifies the management of binary components and releases.

---

## ⚙️ 1. Nexus in Our Project

# Steps Covered in the Project:
    1. Nexus Installation and Setup:

    Installed on an AWS EC2 instance (e.g., Ubuntu or Red Hat).
    Configured the Nexus server for hosting and managing artifacts.

    2. Maven Integration with Nexus:
    • Created Maven hosted repositories (Snapshot and Release).
    • Configured pom.xml and settings.xml for deployment of artifacts to Nexus.
    • Deployed artifacts using the mvn deploy command to ensure artifacts are pushed to the Nexus server.


##  ⚙️ How to Access Artifacts in Nexus
    • Navigate to the Nexus Dashboard:
        Access the Nexus web interface at http://<your-nexus-ip>:8081.
    • Retrieve Artifacts:
        Use wget or curl commands to download artifacts directly from Nexus to your server or local machine.
