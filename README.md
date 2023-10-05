# java-repo-template
## CS9223 - Java Repo Template - Team J

This repository serves as a template for Java projects:
- JDK for the runtime environment
- JUnit for the testing framework
- GitHub Actions for the continuous integration solution 
- Checkstyle for the static analysis solution
- Google Java Format for the code formatting solution
- Maven for the package manager solution

## Getting Started

- Clone the repository: `git clone https://github.com/ZFarooqi24/java-repo-template.git`
- Navigate to the project directory: `cd java-repo-template/tech-template`
- Build the project: `mvn package`
- Run tests: `mvn test`

## Successful Build
![Test build in terminal](./images/Successful%20Build.png)

## GitHub Actions CI

This template includes a GitHub Actions workflow that automatically runs tests on every push and pull request.

## Code Analysis

The project is set up with Checkstyle for static code analysis. We use Google's Checkstyle configuration, which is directly fetched from Checkstyle's official GitHub repository.

## .gitignore

Chose Java from the dropdown menu as it's specifically tailored for Java and will correctly ignore the relative files and directories for a Java project 

## License

This project is licensed under the [MIT License](LICENSE) as it allows for minimal restrictions in its usage

