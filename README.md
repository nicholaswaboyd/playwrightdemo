# Hudl Regression Suite using Playwright/TypeScript in VSCode

This is a Playwright automation suite written in TypeScript, designed to be used in VSCode.

## Prerequisites

Before you can use this automation suite, you need to have the following tools installed:

-   [Node.js](https://nodejs.org/)
-   [npm](https://www.npmjs.com/)
-   [VSCode](https://code.visualstudio.com/)

## Getting Started

To get started with the automation suite, follow these steps:

1.  Clone the repository:
 
    `git clone https://github.com/nicholaswaboyd/playwrightdemo.git` 
    
2.  Install dependencies:
    
    `npm install` 
    
3.  Run the tests:
    
    `npx playwright test` 
    
    This will run the example tests included in the `tests` directory.
    
## Useful Tips

1. If you wish to run the tests with a visible browsed (headed), add --headed as an option to your run command, e.g.:
    `npx playwright test --headed` 
2. If you wish to pause the test to inspect a page or use the inbuilt recorder, add the following line to your test:
    `await page.pause();`

## Playwright Configuration

The Playwright configuration is located in the `config` directory in the `playwright.config.ts` file. You can modify this file to configure the browser to use, the viewport size, and other options.

## Conclusion

That's it! You now have a Playwright automation suite that you can use to write tests for your web applications. If you have any questions or issues, please open an issue on the GitHub repository.

> Written with [StackEdit](https://stackedit.io/).
