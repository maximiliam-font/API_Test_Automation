<p align="center">
  <img src="https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-yellow" alt="Status">
  <img src="https://img.shields.io/badge/PYTEST-Passing-brightgreen" alt="Pytest Badge">
  <img src="https://img.shields.io/badge/Coverage-85%25-blue" alt="Coverage Badge">
  <img src="https://img.shields.io/github/stars/yourusername?style=social" alt="GitHub Stars">
</p>

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*xNQKHj5vR7w9AcY_bDKYYw.gif" alt="Project Logo">
</p>

## API Test Automation of Product Kit Creation
> "Those who enforce the law must obey the law."

<br/>
In this project, I developed a complete automation workflow, technical analysis, and test design to validate the creation of product kits within the Urban Grocers API.
The main focus was verifying the name field in the endpoint responsible for generating custom kits, ensuring business rules, data validations, and consistent server responses.
As a QA Engineer Junior, I implemented an end-to-end testing flow that included requirement analysis, checklists, automated tests using Pytest + Requests, version control with Git/GitHub, and clear technical documentation.

## 🎯 Project Objective
Ensure that the API properly validates the name parameter when creating custom kits, covering boundary values, formats, data types, missing parameters, and error handling — guaranteeing functional reliability, backend consistency, and a stable user experience.

> [!WARNING]
>The system currently allows the creation of kits with values that do not meet the defined functional criteria.
This defect may cause unexpected behavior in production and should be addressed with priority to avoid scalability and stability risks.

## Features
-	🔐 Dynamic user creation with automatic authToken retrieval
- 🧪 Full automation of positive and negative cases using Pytest
- 📦 Functional validation of the POST /api/v1/kits endpoint
- 🛠️ Reusable helper functions ensuring scalability of the test framework
- 📁 Professionally structured project with clean modular organization
> [!NOTE]
>Some backend responses showed behaviors not aligned with the functional documentation. These inconsistencies should be reviewed by the development team to prevent future regressions.

## 🛠️ Technical Skills
#### Requirements Analysis & Documentation
- Interpretation of business rules, identification of grey areas, and creation of clear acceptance criteria.
---
#### Foundation QA & Testing
- Application of core QA techniques: equivalence partitioning, boundary value analysis, positive/negative scenarios, and expected-behavior validation.
---
#### Technical Documentation & Traceability
- Creation of checklists, technical README, and mapping of tests → requirements → results.
---
#### Tools Used
- `Python `
- `Pytest `
- `Requests `
- `Git & GitHub ` (SSH)
- `Local development environment `
- `Command-line terminal `
- `VS Code `
> [!IMPORTANT]
>The `POST /api/v1/kits ` endpoint lacks strong validation for certain data types, allowing atypical parameters to be accepted. This represents a functional integrity risk and must be corrected.

## ⚙️ Validated Functionality
#### ✔️ Positive Cases
- Name with 1 character → 201
- Name with 511 characters → 201
- Special characters → 201
- Leading/trailing spaces → 201
- Numeric strings → 201
#### ❌ Negative Cases
- Empty name → 400
- Name with 512 characters → 400
- Missing parameter → 400
- Incorrect data type (int) → 400

## 📦 Skills Demonstrated
- Requirements analysis and structured test design
- API test automation
- Error detection and inconsistency analysis
- Clear documentation for QA and development teams
- Proper version control practices and professional project structure
- Application of fundamental QA techniques on a real-world system

## 🧩 Key Points
- Scalable and modular test framework
- Full validation of the name field across multiple scenarios
- Coverage of limits, formats, missing parameters, and error handling
- Demonstrated technical judgment in identifying backend functional gaps

## Conclusion
This project showcases my ability to design, automate, and document API tests from scratch.
I applied core QA techniques, performed requirement analysis, and built a clean, professional repository.
It reflects my technical growth as a QA Engineer Junior, with strong focus on quality, precision, and professional standards.

---

## To run the tests:
- Clone the repository to your local environment using SSH. Replace “username” with your GitHub username:
  ```sh
  git clone git@github.com:maximiliam-font/API_Test_Automation.git
  ```
- If you don’t have them installed, install pytest and requests packages to run the tests:
  ```sh
  pip install requests pytest
  ```
- Run all tests with pytest:
  ```sh
   pytest

  
 
##
Thank you for taking the time to review this project. This work reflects my ability to analyze requirements, detect backend inconsistencies, design structured test scenarios, and build reliable API automation from the ground up. I am ready to apply this level of technical rigor, problem-solving, and QA discipline in real engineering environments.
If you’re looking for a QA professional who combines critical thinking, test strategy, and hands-on automation skills, I’d be glad to discuss how I can contribute to your team or upcoming projects. Feel free to connect with me through the links below.



Professional Contacts
<div align="left">
  <a href=https://www.linkedin.com/in/maximiliano-fuentes-morales-qa/><img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="32" height="20" alt="linkedin logo"  /></a>
  <a href=https://discordapp.com/users/maximilian_21./><img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="32" height="20" alt="discord logo"  /></a>
  <a href=maximiliano.fuentes.mor@gmail.com><img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="32" height="20" alt="gmail logo"  />
</div>
    

