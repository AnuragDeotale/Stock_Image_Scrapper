# Stock Image Scraper

## Overview
Stock Image Scraper is a Python-based tool designed to scrape stock images from a given website. It extracts image URLs, associated metadata (such as tags, likes, and comments), and downloads the images to a local directory.

## Features
- Scrapes image URLs from the target website
- Extracts metadata like tags, likes, and comments
- Downloads images in bulk
- Saves data in a structured CSV format

## Technologies Used
- **Python**: Core programming language
- **Selenium**: Web scraping automation
- **BeautifulSoup**: HTML parsing
- **Requests**: Fetching image data
- **Pandas**: Data processing and storage
- **TQDM**: Progress bar for bulk downloads


## Output 
- data.csv: Stores image URLs, tags, likes, and comments
- Imgs/: Folder containing downloaded images
- Imgs.csv: Stores image metadata along with local file paths
## Installation
Ensure you have Python installed (>=3.7), then install the required dependencies:

```bash
pip install selenium beautifulsoup4 requests pandas tqdm


