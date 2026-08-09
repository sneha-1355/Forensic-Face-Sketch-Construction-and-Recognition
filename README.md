# Forensic Face Sketch Construction and Recognition

A comprehensive Java-based application designed to construct forensic facial sketches and match them against known face databases for suspect identification and recognition.

##  Project Overview
This project addresses the forensic challenge of identifying suspects from verbal descriptions or composite sketches. It provides tools to assemble facial components (eyes, nose, mouth, hair, etc.) into a cohesive sketch and utilizes recognition algorithms to search and match generated sketches with target database images.

##  Tech Stack & Dependencies
* **Programming Language:** Java (JDK 8+)
* **GUI / Frameworks:** Java Swing / NetBeans
* **Cloud Integration:** AWS Java SDK
* **Version Control:** Git & GitHub

##  Key Features
* **Facial Sketch Construction:** Modular assembly of different facial elements to build accurate composite sketches.
* **Face Matching System:** Automated comparison between constructed sketches and stored suspect records.
* **Cloud Enabled:** Integration with AWS services for storage and remote data processing.

## 📂 Project Structure
```text
├── Project Code (forensic face sketch)/
│   ├── ThirdEye v2/            # Primary application source & facial composition module
│   └── ThirdEye_FaceMatch/     # Sketch-to-photo matching engine & database integration
