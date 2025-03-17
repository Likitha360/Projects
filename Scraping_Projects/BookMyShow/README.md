# BookMyShow_scraper
A Python-based web scraper that extracts movie data from BookMyShow and sends it via email in a formatted HTML report.

## Description
This project scrapes movie listings from the BookMyShow website for Hyderabad, allowing users to filter by language (Telugu, Hindi, or English). It retrieves movie names, images, and booking URLs, then compiles the data into an HTML email sent to specified recipients. The scraper uses Selenium for dynamic page loading and BeautifulSoup for parsing HTML content.

### Purpose 
Automate the collection of movie data and deliver it in a user-friendly format.

### Tech Stack 
Python, Selenium, BeautifulSoup, smtplib (for email), MIME (for HTML formatting).

### Status 
Functional as of March 2025, tested with Chrome WebDriver.

## Features
- Language selection for movie listings (Telugu, Hindi, English).
- Extracts movie titles, poster images, and booking links.
- Sends a styled HTML email with movie details.
- Handles dynamic content using Selenium.

## Prerequisites
- Python 3.x
- Chrome browser installed
- Chrome WebDriver (compatible with your Chrome version)

## Configure Email Settings
- Open the script (e.g., scraper.py) in a text editor.
- Replace sender_email and sender_password with your Gmail credentials.
- Use an App Password if 2FA is enabled on your Gmail account.
- Update receiver_email with the recipient’s email address.

After running the script, when prompted, enter :
1 for Telugu
2 for Hindi
3 for English etc.

## Output
- The script fetches movie data from BookMyShow.
- Print the results to the console.
- Sends an HTML email to the specified recipient{s} with movie details.

## Sample Output
The email includes a list of movies with:
- Movie title
- Booking link
- Poster image
- Total movie count

# NOTES
** Legal Disclaimer: This project is for educational purposes only. Respect BookMyShow’s terms of service and use responsibly.
** Dependencies: Ensure your Chrome WebDriver version matches your Chrome browser version.
** Improvements: Add error handling for network issues, support for multiple cities, or save data to a file (e.g., CSV).

