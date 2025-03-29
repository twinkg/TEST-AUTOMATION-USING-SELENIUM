# TEST-AUTOMATION-USING-SELENIUM

COMPANY: CODTECH IT SOLUTIONS

NAME: TWINKLE GAJBHIYE

INTERN ID: CTO6WR217

DOMAIN: SOFTWARE TESTING

DURATION: 6 WEEEKS 

MENTOR: NEELA SANTOSH 

## Description of Task-1

This test script is designed to automate basic functionality testing on Amazon India's website. It checks whether users can log in, search for a product, select the product, add it to the cart, and navigate the pages seamlessly. It uses Selenium WebDriver, a popular automation tool for web application testing.

### Tools Used:
1. **Selenium WebDriver**: This is the main tool used for automating interactions with the web application. It allows the script to simulate real user actions, such as clicking buttons, entering text, and navigating between pages.
2. **ChromeDriver**: A browser-specific driver for Selenium that controls the Chrome browser. It is used to open and interact with the browser for testing.
3. **Java**: The programming language used to write the test script.
4. **Actions Class**: A feature in Selenium used to handle complex user actions, like hovering over elements (mouse movement).
5. **JavascriptExecutor**: A Selenium tool that executes JavaScript commands directly in the browser, like scrolling the page.
6. **WebDriver Methods**: Functions such as `findElement` for locating elements, `sendKeys` for entering text, and `click` for performing button clicks.
7. **Window Handles**: Selenium’s feature for managing multiple tabs or browser windows during testing.

### What the Script Does:
1. **Browser Setup**: The script sets up ChromeDriver to control the Chrome browser and opens Amazon India's homepage (`https://www.amazon.in/`). It maximizes the browser window and sets an implicit wait to handle dynamic elements.
2. **Login**: The script hovers over the "Hello, sign in" element and clicks on "Sign in" to open the login page. It enters the user's email and password into the appropriate fields and submits the form to log in.
3. **Search**: Once logged in, the script locates the search box, inputs "puma shoes," and clicks the search button to find products.
4. **Scroll and Product Selection**: Using JavaScript, the script scrolls down the page to simulate a user browsing for products. It clicks on a specific shoe link to open its details page.
5. **Handling New Tabs**: Since the product details open in a new tab, the script manages browser windows using window handles. It switches to the new tab to continue interacting with the product page.
6. **Adding to Cart**: The script locates the "Add to Cart" button and clicks it to add the product to the cart.
7. **Page Navigation**: It performs backward, forward, and refresh actions using Selenium's navigation methods, testing smooth functionality.
8. **Browser Close**: Finally, the script closes the browser, ending the test session.

### Where It Can Be Performed:
This script can be executed on any system with the following setup:
- A machine with Windows, Mac, or Linux operating system.
- Java installed (preferably JDK).
- Chrome browser and matching ChromeDriver version.
- Selenium libraries added to the project.
- An IDE such as Eclipse or IntelliJ IDEA for writing and running the script.
