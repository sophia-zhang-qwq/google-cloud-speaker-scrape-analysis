# google-cloud-speaker-scrape-analysis
Python scrape&amp;analysis of the Google Cloud Speaker Lists (https://cloud.withgoogle.com/next/25/speakers).
The ipynb code scrapes all the speakers info(name, job, company) in the Googld Cloud Speaker webpage:

Step 1: Setup chrome driver (API-like) dynamically.

Step 2: Open the googld cloud speaker-list webpage.

Step 3: Scrape all speaker name, job, company on this current page.

Step 4: Click the next button for all pages. 

Step 5: Repeat Step 3-4 for all pages. 

Final speaker results are saved inside Results directory. 
Results: 
- There are 1570 speakers attending in total. 
- The most common companies are Googld Cloud, Google, NVIDIA, Shopify. 
- The most common job types are Product Manager, Software Engineer, CEO, CTO. 

