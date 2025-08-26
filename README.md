# Showcase

This repository demonstrates my approach to setting up a development environment, structuring
infrastructure, and writing code and tests.

## 1. Project Foundation & Setup

- I generate a project using Spring Initializr (last release version)
- I use Java 21 as the language level (last LTS version)
- I add Spring Boot DevTools for hot deployment
- I choose Maven as the build tool (simplicity in small projects)
- I would consider using Gradle for better performance in complex projects

## 2. IDE Configuration & Developer Experience

- I use IntelliJ IDEA as my IDE
- I use Save Actions plugin for code formatting
- I choose Google Java Style for code formatting
- I don't use any special profilers or code coverage tools at this point

## 3. Code Quality & Standards

- I add Checkstyle plugin for static code analysis
- I add PMD plugin for static code analysis
- I add Spotbugs plugin for static code analysis
- I add SonarLint plugin for static code analysis within IDE
- I would consider using Error Pron and SonarQube for bigger projects