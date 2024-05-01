"# web-scraping-Linkedin---Selenium-" 
# LinkedIn Job Scraper

This Python script uses Selenium to scrape job listings from LinkedIn based on specified search criteria, such as keywords and location. It then saves the scraped data to a CSV file.

## Prerequisites

- Python 3. x
- Selenium library (`pip install selenium`)
- ChromeDriver is compatible with your Chrome browser version

## Usage

1. Clone the repository:

```bash
git clone https://github.com/hrishikeshonmars/web-scraping-Linkedin---Selenium.git
Navigate to the project directory:
cd linkedin-job-scraper

Install dependencies:
pip install -r requirements.txt
Download and place the ChromeDriver executable in the project directory. You can download ChromeDriver from here.
Modify the scrape_linkedin_jobs.py script with your desired LinkedIn job search URL and output file name:
Python
Copy code
url = 'https://www.linkedin.com/jobs/search?keywords=Marketing%20Data%20Analyst&location=Berlin%2C%20Berlin%2C%20Germany&geoId=106967730&trk=public_jobs_jobs-search-bar_search-submit&position=1&pageNum=0'
output_file = 'linkedin_jobs.csv'
Run the script:
python scrape_linkedin_jobs.py
The script will scrape the job listings, save them to a CSV file, and then terminate.
