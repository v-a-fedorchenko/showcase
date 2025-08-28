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

## 4. Version Control & Git Workflow

- I use Git for version control
- I use a default .gitignore file from Spring Initializr
- I use GitHub for hosting the repository
- I use a trunk-based development workflow for smaller projects
- I would consider using GitFlow for bigger projects with more contributors
- I use conventional commits for commit messages
- I use simple CI for basic checks (e.g., build, test, lint)

## 5. Domain Modeling & Architecture Design

- I use DDD for domain modeling
- I use Microservices architecture for scaling
- I use one microservice per bounded context
- Within each application, I use one module per aggregate
- In this showcase project, for simplicity, I use very few aggregates
- Most of the work here is being done externally and will be documented in the next section

## 6. Documentation & Knowledge Sharing

- I use MkDocs for documentation
- I use a simple CI for publishing the documentation to GitHub Pages
- 
