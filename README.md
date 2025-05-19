# playwright-ui-autotests
The project is centered around learning Playwright UI-autotest and their intergration into CI with Jenkins

Steps to start work with the project:
1. Clone the repository through IDE terminal with command: git clone HTTPS-repository-link
2. Initialize Playwright project through IDE terminal with command: npm init playwright
3. Chooose TypeScript as a programming language
4. Choose folder name for test (optional: tests)
5. Reject/Approve using GitHub Actions workflow (optional: reject=false)
6. Reject/Approve to download browsers (optional: agree=true)
7. After the steps above the project will be initialized. Files such as package-lock.json, package.json, playwright.config.ts should appear in the project. Directories "tests" with  example.spec.ts and "test-examples" with demo-todo-app.spec.ts should also appear in project.
8. To run tests in UI-mode use command: npx playwright test --ui
9. To run tests without UI-mode use command: npx playwright
10. To generate default Playwright's report after step 9 use command: npx playwright show-report
