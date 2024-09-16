# PORTFOLIO
This is my QA portfolio.
[Reyes Cuesta PORTFOLIO](https://bootcamp-qa.github.io/web-portfolio-template)

## BUILD WITH
* ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
* ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

## TEST PLAN

### 1. Introduction
This Test Plan outlines the strategy for testing the portfolio web application, focusing on manual functional and regression testing of five user stories. Testing will be conducted on both desktop and mobile platforms. Regression testing will be executed at the end of each sprint, following every release. The development and testing processes follow Behavior-Driven Development (BDD) and Agile Scrum methodologies.

### 2. Methodologies
- **Behavior-Driven Development (BDD)**: Test cases are defined prior to development based on user stories. These test cases guide the development process to ensure that the functionality meets the defined behavior. Scenarios are written in **Gherkin** language to specify the behavior in a clear and understandable format. Testing is conducted after development to validate that the implemented features align with the expected behavior.

- **Agile Scrum**: The project follows Agile Scrum methodology with **two-week sprints**. At the end of each sprint, a review is conducted, and regression testing is performed to ensure that newly implemented features do not negatively impact existing functionality.

### 3. Scope
The testing will validate the core functionalities of the portfolio web application. It includes:
- Manual testing of the features on desktop and mobile.
- Regression testing after each sprint to ensure that new releases do not impact existing functionality.

### 4. Objectives
- Ensure that the new features developed for the web portfolio function correctly on both desktop and mobile platforms.
- Verify that existing functionalities remain unaffected after releases through regression testing at the end of each sprint.

### 5. Features to be Tested
[JIRA PROJECT](https://bootcampqareyes.atlassian.net/jira/software/projects/CVP/boards/1)
The following user stories are included in the testing scope:
1. **Header Section**: Includes links to LinkedIn and GitHub, and displays the full name and title.
2. **About Me Section**: Presents a personal introduction.
3. **Projects Section**: Showcases links to GitHub projects.
4. **Education Section**: Provides a brief description of educational background.
5. **Contact Section**: Enables users to submit inquiries via a form.

## 6. Test Approach
- **Manual Functional Testing**: Test each user story independently on both desktop and mobile environments. The focus will be on verifying that each function works as per the specified requirements defined through BDD.

- **Regression Testing**: To be executed at the **end of each two-week sprint**, following the final release of the sprint, to ensure that previously working functionalities are not broken by recent changes.

## 7. Test Environment
- **Desktop**: Google Chrome (latest version).
- **Mobile**: Android (Chrome), iOS (Safari).

## 8. Test Documentation
- **Test Management Tool**: Tests and scenarios are documented using **AssertThat**, a test management tool that helps in organizing, executing, and tracking test cases.
- **Scenario Writing**: Test scenarios are written in **Gherkin** language, which provides a clear and structured way to describe the expected behavior of features in a human-readable format.

## 9. Test Cases
The test cases will cover the following:
- **Functional Test Cases**: Defined based on user stories using BDD principles and written in Gherkin. They verify the correct behavior of each feature for the five user stories.
- **Regression Test Cases**: Ensure that previously tested functionalities continue to work as expected after each sprint release.

## 10. Exit Criteria
Testing will be considered complete when:
- All functional test cases have been executed, with at least 90% passing.
- All critical bugs have been resolved.
- Regression tests have been successfully completed after each sprint, with no major issues found.

## 11. Deliverables
- **[Functional Test Results](/tests/test-plan.pdf)**: A document summarizing the execution and results of all functional test cases.
- **[BUG Report](/tests/regression-test-plan.pdf)**: Detailed documentation of any defects found during testing, including severity, steps to reproduce, and resolution.
- **[Regression Test Execution Report](/tests/regression-test-plan.pdf)**: A report outlining the results of regression tests executed at the end of each sprint.

## AUTHOR
Reyes Cuesta, QA Engineer
[LinkedIn Profile](https://www.linkedin.com/in/reyescuesta)
