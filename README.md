# Katalon Studio Test Automation Project 🚀

# About Katalon Studio
Katalon Studio is a powerful automated testing IDE built on the Selenium and Appium frameworks. It enables teams to create, execute, and manage test cases across Web, API, Mobile, and Desktop applications efficiently. 
Katalon Studio enhances test coverage, integrates seamlessly with CI/CD pipelines, and provides rich reporting features.

📌 Project Overview
This project automates Web Application test cases using Katalon Studio. The test scripts are organized within a structured framework to ensure maintainability and scalability.

🛠️ Getting Started
### 1️ Prerequisites
Before you begin, make sure you have the following installed:
- Katalon Studio : [website](https://katalon.com/)
- Git : [website](https://git-scm.com/downloads)
- Any other necessary dependencies for your test automation

### 2️ Project Setup
Follow these steps to set up the project on your local machine:
- Clone this repository using Git - (git clone https://github.com/your-username/your-katalon-project.git)
- Open Katalon Studio and select File > Open Project.
- Navigate to the cloned project directory and select the .prj file.
- Set up test configurations as needed (e.g., browser settings, test data, etc.).

 ### 3 Running Tests
 You can execute test cases in two ways:
🔹 Running from Katalon Studio UI
 	- Open Katalon Studio.
	- Select the desired Test Case or Test Suite.
	- Click the Run button and choose the browser/environment.
	
🔹 Running from Command Line
To execute a test suite from the terminal:
katalon -noSplash -runMode=console -projectPath="$(pwd)/your-project.prj" \
-testSuitePath="Test Suites/YourTestSuite" -browserType="Chrome"

### Project Structure
your-katalon-project/
│── Test Cases/           # Test case scripts
│── Test Suites/          # Organized test case groups
│── Object Repository/    # UI elements repository
│── Data Files/           # External test data (if applicable)
│── Reports/              # Test execution reports
│── Include/              # Custom keywords, utilities, etc.
│── .gitignore            # Git ignore rules
│── README.md             # Project documentation
│── your-project.prj      # Katalon project file

📌 Best Practices
Follow the Page Object Model (POM) to maintain reusable test scripts.
Keep test data separate from test scripts using Data Files.
Use Custom Keywords for complex actions to improve maintainability.
Leverage Katalon Reports & Logs for debugging and analysis.

### References
- Katalon Course - https://drive.google.com/file/d/1-8cJyLBuWb-tGfv2TyRiYIxDjcsA6SbU/view
- Youtube link - https://www.youtube.com/watch?v=lcUgrciUCPg


  
