# Kaufland Product Scraper

This project is designed to scrape product details from the Kaufland and 1688 websites. Using Selenium and BeautifulSoup, the script extracts information such as product titles, specifications, and seller details, and stores the data in an Excel file.

## Features

- Handles cookie popups.
- Scrolls and loads more products dynamically.
- Extracts product titles, specifications, and seller details.
- Saves the scraped data into an Excel file.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- Selenium
- BeautifulSoup
- Requests
- Pandas
- ChromeDriver (automatically installed by `chromedriver_autoinstaller`)

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/kaufland-product-scraper.git
    ```

2. Navigate to the project directory:
    ```bash
    cd kaufland-product-scraper
    ```


## Usage

1. Ensure you have Chrome installed.

2. Run the script:
    ```bash
    python scrape_kaufland.py
    ```

3. The script will open the browser, navigate to the specified URLs, and start scraping product details.

4. The scraped data will be saved into an Excel file named `kaufland_data.xlsx` in the project directory.

## Project Structure

- `scrape_kaufland.py`: The main script containing the web scraping logic.


## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project uses the following open-source libraries:

- [Selenium](https://selenium.dev/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
- [Pandas](https://pandas.pydata.org/)
- [chromedriver_autoinstaller](https://pypi.org/project/chromedriver-autoinstaller/)

