# LinkedIn Jobs Scraper: Get Job Data Easily

Are you looking for a way to extract job information from LinkedIn? Our LinkedIn Jobs Scraper makes it super simple to gather data on job listings.

## What is a LinkedIn Jobs Scraper?

A LinkedIn Jobs Scraper is a tool that pulls details about job postings from the LinkedIn website. Instead of manually copying information, the scraper automatically collects and organizes the job data for you.

## Why Use Our LinkedIn Jobs Scraper?

Our LinkedIn Jobs Scraper is the best because it's:

- **Reliable**: You get accurate, up-to-date job data every time.
- **Easy**: Just provide your search criteria. We do the rest!
- **Powerful**: Extract a ton of valuable details with one click.

## How to Use the LinkedIn Jobs Scraper

Using our LinkedIn Jobs Scraper tool is a breeze:

1. Visit [LinkedIn Jobs Scraper](https://apify.com/scrapefull/linkedin-jobs-scraper) on Apify Store.
2. Set your job search parameters (keyword, location, etc.)
3. Start the scraper
4. Download your structured job data once it's ready in formats like JSON, CSV, Excel, XML, HTML Table, RSS and JSONL.

It's that simple! No coding required. 

If you prefer to integrate via an API, you can use the [LinkedIn Jobs Scraper API](https://apify.com/scrapefull/linkedin-jobs-scraper/api) too.

## Get Started with the LinkedIn Jobs Scraper

Don't waste time manually copying LinkedIn job listings. Let our trusted LinkedIn Jobs Scraper tool do the hard work for you. Accurate data, incredible ease of use, and time savings - what more could you ask for?

Sign up today and effortlessly extract all the job intelligence you need from LinkedIn. Try the best LinkedIn Jobs Scraper now!

## What Data Does It Collect?

| Field Name           | Data Structure | Description                                        |
|----------------------|-----------------|---------------------------------------------------|
| publishedAt          | String          | Date when the job was published                    |
| salary               | String          | Salary information (if available)                  |
| title                | String          | Job title                                          |
| jobUrl               | String          | URL of the job listing on LinkedIn                 |
| companyName          | String          | Name of the company offering the job               |
| companyLinkedInUrl   | String          | URL of the company's LinkedIn page                 |
| location             | String          | Job location                                       |
| numberOfApplications | String          | Number of applicants for the job                   |
| description          | String          | Detailed job description                           |
| employmentType       | String          | Type of employment (e.g., Full-time, Part-time)    |
| seniorityLevel       | String          | Seniority level of the position                    |
| jobFunction          | String          | Job function category                              |
| industries           | String          | Industries related to the job                      |
| companyId            | String          | LinkedIn's unique identifier for the company       |
| jobPosterProfileUrl  | String          | URL of the job poster's LinkedIn profile           |
| jobPosterName        | String          | Name of the person who posted the job              |
| jobPosterTitle       | String          | Title of the person who posted the job             |
| externalApplyUrl     | String          | URL for external application (if applicable)       |

## Input Parameters
You can filter the jobs on LinkedIn using these options.

| Parameter         | Type    | Description                                                                                               |
|-------------------|---------|-----------------------------------------------------------------------------------------------------------|
| keyword           | String  | Job search keyword                                                                                        |
| location          | String  | Job location                                                                                              |
| dateSincePosted   | Enum    | Filter jobs by date posted (Options: "past Month", "past Week", "24hr")                                   |
| jobType           | Enum    | Type of job (Options: "full time", "part time", "contract", "temporary", "volunteer", "internship")       |
| remoteFilter      | Enum    | Filter for remote jobs (Options: "on-site", "remote", "hybrid")                                           |
| salary            | String  | Minimum salary                                                                                            |
| experienceLevel   | Enum    | Required experience level (Options: "internship", "entry level", "associate", "senior", "director", "executive") |
| limit             | Integer | Maximum number of jobs to scrape (Range: 1-1000, Default: 20)                                             |
| companyName       | Array   | Filter jobs by company names                                                                              |
| proxyObj          | Object  | Proxy configuration for the scraper                                                                       |

