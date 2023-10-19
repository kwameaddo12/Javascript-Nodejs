
# JavaScript NodeJS Repository for AFMC2

## Summary

Caretakers of the Repo will update the Repo
The Repository will have a design documentation that will include;
1. Required Software 
2. Bitbucket Access
3. Clone the Repository
4. Installing Dependencies
5. Running the project Locally
6. VS Code Extensions
7. Testing
- 
##### Quality Gates
- Implement Sonar quality checks with a target of achieving 80% code coverage for new code.

How can developers determine if their quality check threshold is below the required 80%? 
For instance, if a developer's threshold is set at 60%, what steps should they take to identify this and meet the project's required threshold?
- Test cases include:
  - Unit tests
  - Super tests
  - End-to-end tests
- We're exploring the possibility of having different lines of coverage/tests for specific aspects of the project.

##### JavaScript Code Coverage
- `Jarred` will assist in setting up JavaScript code coverage for the repository.
- The JavaScript repository will also include Husky to prevent the build/test process if there are failures.

### Test Coverage Below the Bar (80%)?
If the test coverage falls below the 80% threshold, please take one or more of the following actions:
- Review uncovered code sections.
- Write additional test cases.
- Consider code reviews to identify potential improvements.


## Description

This repository is linked to the AFMC2 project and its associated sub-projects. It serves as a central hub for JavaScript NodeJS development.

## Getting Started

To get started, follow these steps:

1. Clone the repository from Bitbucket.
2. Refer to the README file attached to each sub-repository for specific instructions on setting up and running the project.
3. The README and package.json files within each sub-repository will provide detailed guidance.

### Dependencies

Ensure you have the following dependencies installed:

- NodeJS v18.16.1
- Node Package Manager (npm)
- Text Editor or Integrated Development Environment (IDE)
- Docker

Additionally, consider installing the following VS Code extensions to streamline your development process:

1. **ESLint**:
   - Description: Integrates ESLint with VS Code for real-time code style and syntax error detection.
   - [ESLint Extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

2. **Prettier - Code Formatter**:
   - Description: Integrates Prettier into VS Code for code formatting.
   - [Prettier Extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

3. **Debugger for Chrome**:
   - Description: Enables debugging of client-side JavaScript in Google Chrome directly from VS Code.
   - [Debugger for Chrome Extension](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)

4. **Node.js Modules Intellisense**:
   - Description: Offers intelligent code completion and suggestions for Node.js core modules and installed packages.
   - [Node.js Modules Intellisense Extension](https://marketplace.visualstudio.com/items?itemName=leizongmin.node-modules-intellisense)

5. **npm Intellisense**:
   - Description: Autocompletes npm module imports for easier package management.
   - [npm Intellisense Extension](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)

6. **REST Client**:
   - Description: Allows sending HTTP requests and viewing responses directly from VS Code for RESTful API development.
   - [REST Client Extension](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)

### Installing

Follow these steps to install and set up the application:

1. Install all required dependencies.
2. Ensure Git is installed.
3. Have access to Bitbucket.
4. Run and test the project locally.

### Executing program

Refer to the `package.json` script section for the necessary commands, each preceded by 'npm'. For example:

```sh
npm run start
```

## Help

For any questions or assistance, please reach out to the respective caretaker associated with the repository. Here are the repo names and their caretakers:

- Mhmi - Jarred
- ms-api - Jarred
- ms-cli - Ed Garcia
- ms-common - Ed Garcia
- ms-devops - Ed Garcia
- ms-hmi - Jarred
- ms-lifecycle - Martin/Ana
- ms-player - Elliot
- ms-monitor - Zack Parker
- ms-registry - Ed Garcia
- ms-rest-api-sandbox - Agenda item for late(Tavit)
- ms-sim player - Elliot/Mike
- ms-store - Martin

## License

This project is licensed under the AFMC2 License.
