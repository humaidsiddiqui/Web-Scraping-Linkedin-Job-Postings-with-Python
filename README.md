Here's a clean and professional `README.md` for your **LinkedIn Job Scraper** project:

---

## 📄 Web Scraping LinkedIn Job Postings with Python

This project scrapes job postings for a given title and location from LinkedIn using Python and stores the results in a CSV file. It extracts key details like job title, company name, posting date, and number of applicants.

---

### 📌 Features

- Scrapes job postings from LinkedIn using public guest APIs.
- Extracts:
  - Job Title
  - Company Name
  - Posting Date
  - Number of Applicants (if available)
- Saves the data to a clean CSV file.
- Designed for extensibility: can be enhanced to support more job platforms or a UI.

---

### 🛠️ Dependencies

Install the required Python libraries:

```bash
pip install requests beautifulsoup4 pandas
```

---

### 🚀 How It Works

1. Define job title and location.
2. Construct the search URL using LinkedIn’s guest job API.
3. Parse job listings to extract individual job IDs.
4. Use the job IDs to scrape detailed job info from job pages.
5. Store the data in a list of dictionaries.
6. Convert to a DataFrame and save as a CSV file.

---

### 📊 Output Example

| job_title                        | company_name           | time_posted   | num_applicants    |
|----------------------------------|------------------------|---------------|-------------------|
| Software Engineer (Intern)       | Naptha AI              | 1 month ago   | None              |
| Senior Backend Engineer, Python | Klue                   | 4 months ago  | 151 applicants     |
| Web Developer                   | SenseNet Inc.          | 3 months ago  | 55 applicants      |

The full output is saved in `Vancouver_Python_Developer.csv`.

---

### 📂 File Structure

```
📁 Web-Scraping-Linkedin-Job-Postings-with-Python/
│
├── Web-Scrapper.ipynb        # Main Jupyter Notebook
├── Vancouver_Python_Developer.csv  # Scraped job data
├── README.md                 # Project overview
```

---

### 💡 Future Enhancements

- Support additional job boards (Indeed, ZipRecruiter, etc.)
- Add pagination to scrape more results
- Build a user-friendly web UI to interact with the scraper
- Add date filters and keyword tags

---

### ⚠️ Disclaimer

This scraper uses LinkedIn's guest job posting endpoints which may change or limit access at any time. Use for educational purposes only and respect LinkedIn’s [terms of service](https://www.linkedin.com/legal/user-agreement).

---

Let me know if you'd like a badge, logo, or sections like "Getting Started" or "Contributing"!
