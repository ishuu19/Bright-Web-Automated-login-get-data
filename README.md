# Web Scraping for Web-Based Time Period Selection

This repository contains Python scripts designed for web scraping tasks, specifically focused on interacting with time period selection elements on web pages.

## Overview

The main purpose of this repository is to automate the process of selecting time period options (such as 30 minutes, hour, day, week, and month) on a web page using Python and Selenium. The time period buttons are part of an interactive UI that can either display a set of 5 or 6 options. Based on the number of buttons, the script selects the appropriate "30min" button.

### Key Features:
- **Flexible Button Handling**: The script handles cases where there are either 5 or 6 buttons in the time period selector.
  - **For 6 buttons**: The second button (30min) is selected.
  - **For 5 buttons**: The first button (30min) is selected.
  
- **JavaScript Execution**: The script executes JavaScript to interact with the page and click the relevant button based on the count of buttons.

## Requirements

- Python 3.x
- Selenium WebDriver
- A browser driver (e.g., ChromeDriver)

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/web-scraping-time-period.git
    ```

2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download and set up the appropriate WebDriver for your browser (e.g., ChromeDriver for Chrome).

## Usage

1. Ensure the necessary driver (e.g., ChromeDriver) is installed and added to your PATH.
2. Run the script to start the web scraping process:
    ```bash
    python scrape_time_period.py
    ```

This will execute the scraping and interact with the web page to select the "30min" option based on the number of buttons present.

## Contributing

Feel free to open issues or submit pull requests if you encounter bugs or have suggestions for improvements!

## License

This project is licensed under the MIT License.
