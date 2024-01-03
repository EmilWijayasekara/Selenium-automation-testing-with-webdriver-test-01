# Selenium Test Example

This is a simple Selenium test example using Java and the Chrome WebDriver to automate interactions with the [Guru99 Demo Website](http://demo.guru99.com/test/newtours/).

## Prerequisites

- Java installed on your machine
- Maven enviroment variables
- Chrome browser installed
- ChromeDriver executable downloaded and placed in the appropriate directory (in this case, `src/main/resources/drivers/`)

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/EmilWijayasekara/Selenium-automation-testing-with-webdriver-test-01.git
    ```

2. Open the project in your preferred Java IDE.

3. Update the ChromeDriver executable path in the code if necessary:

    ```java
    System.setProperty("webdriver.chrome.driver", System.getProperty("user.dir") +
            "\\src\\main\\resources\\drivers\\chromedriver.exe");
    ```

4. Run the `Example2` class to execute the Selenium test.

## Description

This Selenium test automates the following steps:

1. Navigate to the Guru99 Demo Website.
2. Log in with a username and password.
3. Go to the flight reservation page.
4. Set various flight details such as one-way trip, passenger count, departing and arriving airports, dates, service class, and airline.
5. Display and print the list of available airlines.
6. Find and display available flights.
7. Close the browser.

## Note

- The `Thread.sleep` statements are used for demonstration purposes and may need adjustment based on the speed of your system and network.
- Make sure to update the ChromeDriver version if necessary.

  ### Maven Enviroment
user variables for [user]

[![Screenshot-2024-01-03-213900.png](https://i.postimg.cc/mgQ5pW1F/Screenshot-2024-01-03-213900.png)](https://postimg.cc/K18f4VNZ)


system variables

[![Screenshot-2024-01-03-213916.png](https://i.postimg.cc/yY359ZVj/Screenshot-2024-01-03-213916.png)](https://postimg.cc/561nWjQQ)


### Feel free to customize this code according to your needs or use it as a reference for your Selenium testing projects.
