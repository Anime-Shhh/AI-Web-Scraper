# AI-Web-Scraper
An AI based webscraping web app utilizing ollama, streamlit, python, and selenium

Using streamlit, the webapp has a simple interface for the user to enter the website they wish to scrape.

The scraping process is automated using python and selenium, which opens a headless browser in the background and opens the website.
From this headless browser, beautifulsoup is used to extract all the content.
All the content is then saved and shown back to the user to view if they wish. 

Then the user can prompt what they wish to know from the site, which is then fed to ollama which answers the user's prompt and is then returned to the user.
