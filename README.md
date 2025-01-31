# Playwright with Cucumber and TypeScript

This project provides an automation testing setup using **Playwright**, **Cucumber**, and **TypeScript**, enabling BDD-style web automation.

## Features
- **Playwright for UI Automation**: Supports testing across Chromium, Firefox, and WebKit.
- **Cucumber for BDD**: Implements feature files and step definitions.
- **TypeScript Support**: Ensures type safety and better maintainability.
- **Page Object Model (POM)**: Organizes test scripts for reusability.
- **Custom Hooks & Fixtures**: Supports setup and teardown configurations.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ortoniKC/Playwright_Cucumber_TS.git
   cd Playwright_Cucumber_TS
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Running Tests
Run all tests:
```bash
npx cucumber-js
```

Run tests with Playwright:
```bash
npx playwright test
```

## Project Structure
- `features/` - Contains Cucumber feature files.
- `step-definitions/` - Includes step definition files.
- `pages/` - Implements the Page Object Model.
- `support/` - Holds custom hooks and configurations.

## Contributing
Feel free to contribute by submitting issues or pull requests!

## License
This project is licensed under the MIT License.
