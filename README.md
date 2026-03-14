# SDLC Assignment – Smart Attend App

## Project Overview

Smart Attend is a mobile application designed for universities to automate student attendance using geo-fencing technology. When a student enters the classroom area, the system automatically marks attendance.

Later, biometric Face ID verification is added to prevent proxy attendance.

---

## Development Methodology

The project follows the **Agile Scrum Framework**, where development is divided into short iterations called sprints.

Sprint 1 focuses on building the **Minimum Viable Product (MVP)** including login, geo-fencing detection, and attendance dashboard.

Sprint 2 integrates **biometric Face ID verification** and improves reporting features.

---

## Why CI/CD is Used

CI/CD (Continuous Integration and Continuous Deployment) is used to automate the development and release process.

### Continuous Integration (CI)

Developers frequently push their code to a shared GitHub repository. Automated systems then:

* Build the application
* Run automated tests
* Detect bugs early

This ensures that new features do not break the existing system.

### Continuous Deployment (CD)

Once the code passes all tests, it can automatically be deployed to the mobile application server or app store updates.

Benefits include:

* Faster feature delivery
* Reduced manual errors
* Quick bug fixes
* Continuous improvement based on user feedback

## Conclusion

Using Agile and CI/CD helps the team quickly adapt to new requirements such as biometric verification while continuously delivering improvements to students and teachers.
