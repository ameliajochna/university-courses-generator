# University Courses Generator

This repository contains the final project for the "Objective Programming" course at the University of Wrocław.

## Overview

Choosing subjects each semester can be challenging for many university students. To address this, our group of two developed an application that generates a list of courses for each semester.

## Running

```console
git clone https://github.com/ameliajochna/university-courses-generator.git
javac Main.java
java Main

```

## Features

- **Requirement Fulfillment:** The application ensures that all degree requirements are met, including the total number of ECTS points and completion of group projects.
- **Randomized Course Selection:** Subjects are selected randomly, taking into account compulsory courses that must be completed in specific semesters. If a student is unsatisfied with the generated list, they can simply generate a new set of courses.

## How It Works

1. **Input Requirements:** Students input the degree they are pursuing.
1. **Generate Course List:** The application randomly generates a set of subjects that fulfill the specified requirements.
1. **Regenerate if Needed:** If the generated list is not satisfactory, students can regenerate the list to get a new set of courses.

This tool aims to simplify the process of course selection, allowing students to focus on their studies without the added stress of meeting administrative requirements.

## UML Class Diagram

![UMLClassDiagram](https://github.com/ameliajochna/university-courses-generator/assets/62848107/e6b3fdf0-2070-48ba-8064-31cab92f7ef4)

## Examples

### Engineer degree

![engineerFIXED](https://github.com/ameliajochna/university-courses-generator/assets/62848107/cd57d059-311b-47db-8f46-4c8a9d95c2f3)

### Bachelor degree

![bachelorFIXED](https://github.com/ameliajochna/university-courses-generator/assets/62848107/80bf5805-f5a4-4f41-8723-f93772dfd161)





