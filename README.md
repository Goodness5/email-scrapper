# Email Scraper Setup Guide

## Introduction

This tool allows you to extract email addresses from a given website. To get started, follow the instructions below to set up the application on your local machine.

## Prerequisites

Before you begin, make sure you have the following installed on your machine:

- Python 3.x
- pip (Python package installer)

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/goodness5/email-scrapper.git
    ```

2. Change to the project directory:

    ```bash
    cd email-scraper
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Now that you have the Email Scraper installed, you can use it to extract email addresses from a website. Follow these steps:


- Run the script:

    ```bash
        python app.py
    ```

   The script will prompt you to enter the URL, and then it will print the extracted email addresses to the console.

## Customization

If you want to customize the application or integrate it into your project, feel free to modify the code according to your needs. The email extraction is currently based on a regular expression (`EMAIL_REGEX`). You can adjust this regex or implement additional logic as required.

## Additional Notes

- The application uses the `requests_html` library to scrape websites, and it also renders JavaScript-driven content. Ensure that you have a stable internet connection and that the website you are scraping allows web scraping.

- If you encounter any issues or have questions, feel free to [open an issue](https://github.com/goodness5/email-scraper/issues) on the GitHub repository.

Happy scraping!