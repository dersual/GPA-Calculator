# GPA Calculator

A GPA Calculator that allows users to input their courses, grade scales, and individual assignment grades, and calculates GPA both for individual courses and for multiple courses selected by the user.

## Table Of Contents

- [Features](#features)
- [Installation](#installation)
- [User Guide](#user-guide)
  - [Inputs](#inputs)
  - [Outputs](#outputs)
- [Contributing](#contributing)
- [Licensing](#licensing)

## Features

**Course Input:** Add courses with custom names.

- **Grade Scale Input:** Define grade scales for each course (e.g., A = 90-100, B = 80-89).
- **Assignment Input:** Input grades for individual assignments within each course.
- **Course GPA Calculation:** Calculate GPA for each course based on assignment grades.
- **Multiple Course GPA Calculation:** Calculate cumulative GPA across multiple selected courses.

## Installation

To be worked on later

## User Guide

#### Inputs

- **Courses:** Users will be asked to enter course names.
- **Assignment Types:** Users will define whether their graded work is a test grade, quiz grade, homework grade, etc.
- **Grade Scale:** Users will define how much weight is put on particular assignment types.
- **Assignments:** Enter individual assignment grades as percentage values and what type of work they are.

#### Outputs

- **Individual Course GPA:** The calculator computes the GPA for each course based on assignment grades and the user-defined grade scale.
- **Multiple Courses GPA:** The user can select multiple courses, and the tool will calculate a cumulative GPA based on the grades of those selected courses.

## Contributing

Quick Guide For Contributers Who Working On This Project:

1. **Clone The Repository:**
   - First, make sure you have Git installed on your machine. You can download it [here](https://git-scm.com/).
   - Clone the repository to your local machine by running the following command in your terminal:
   ```bash
   git clone https://github.com/dersual/gpa-calculator.git
   ```
   - Navigate To Folder
   ```bash
   cd gpa-calculator
   ```
2. **Create a new branch:**
   - It's recommended to create a new branch for each feature or bug fix. This keeps your work organized and separate from the main branch:
   ```bash
   git checkout -b feature-branch-name
   ```
3. **Make Your Changes:**
   - Implement your changes in the project. Make sure to follow any contribution guidelines, if applicable.
4. **Commit your changes:**
   - Once you've made your changes, commit them with a descriptive message:
   ```bash
   git add .
   git commit -m "Description of the changes made"
   ``` 
5. **Push the changes to your branch:** 
    - Push your changes to your GitHub repository: 
    ```bash 
    git push origin feature-branch-name
    ``` 
6. **Create Pull Request** 
    - Go to the original repository on GitHub and submit a pull request (PR) from your feature branch. In the PR description, explain the changes and why they're beneficial. 
    - After submitting your pull request, the project maintainers will review it and provide feedback or approve the changes.

## Licensing
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.