# API Automation testing using Stepci

## Table of Contents:
- [Overview - Stepci](#overview---stepci)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage & Features](#usage--features)
- [License](#license)

## Overview - Stepci

Step CI is an open-source API Quality Assurance framework:

- Language-agnostic. Configure easily using YAML, JSON or JavaScript
- Test different API types in one workflow: REST, GraphQL, gRPC, tRPC, SOAP
- Self-hosted. Test services on your network, locally and CI/CD
- Integrated. Play nicely with others

Check the official documentation for more details: [Step CI Documentation](https://docs.stepci.com/)

## Installation

### Project Initialization:

```bash
git clone https://github.com/hariprasathvs/stepci.git
```

### Install Redhat YAML extension for VS Code:
You can install the Redhat YAML extension for Visual Studio Code to assist with YAML file editing.

Extension ID: redhat.vscode-yaml

You can install it from the Visual Studio Code Extensions Marketplace.

## Project Structure:

- **schemas**: Folder containing linting schemas.
  - `step.schema.json`: Defines linting schema for steps.
  - `test.schema.json`: Defines linting schema for tests.
  - `workflow.schema.json`: Defines linting schema for workflows.

- **test**: Contains test-related folders for easier maintenance.
  - **contract**: Holds contract tests.
  - **regression**: Contains regression tests.
    - **steps**: Reusable steps.
    - **testcases**: Test files.
    - **testdata**: Test data.
  - `.env`: Environment variables file.

## Usage & Features

### Installation:

```bash
npm install
```

### Run Test:

```bash
npm run test
```

### Features:

- Provides a basic boilerplate for creating an API test automation framework.
- Well-organized folder structure for easy maintenance.
- Static linting for faster development.

## License:

This project is licensed under the MIT License. Feel free to pull and make your contributions.
