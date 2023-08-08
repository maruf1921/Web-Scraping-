

# Web Scraping

This Python script allows you to scrape and download images from the PNGMart website. 
It extracts image URLs from the sitemap and downloads a specified number of images.

## Prerequisites

Before using this script, ensure you have the following dependencies installed:

- Python 3.x
- [Requests library](https://docs.python-requests.org/en/latest/)
- [Beautiful Soup library](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

You can install these dependencies using the following command:

```bash
pip install requests beautifulsoup4
```

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/pngmart-web-scraper.git
```

2. Navigate to the project directory:

```bash
cd pngmart-web-scraper
```

3. Run the script:

```bash
python scraper.py
```

## Configuration

You can modify the `scraper.py` script to adjust the behavior according to your needs:

- `site_map`: The URL of the sitemap you want to scrape.
- `num_images`: The number of images you want to download (change `master_list[1:10]` to your desired range).
- Ensure that you have the appropriate permissions to scrape and download from the PNGMart website.

## Disclaimer

Please use this script responsibly and follow the terms of use of the PNGMart website. This script is intended for educational and personal use only.

## License

This project is licensed under the [MIT License](LICENSE).
