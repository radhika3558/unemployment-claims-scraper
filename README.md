# Unemployment-claims-scraper
 
 Auto-updating US jobless claims website

 This code scrapes and auto-update a website that visualizes data!

 Every Thursday the US Department of Labor announces the weekly jobless claims data on its website in PDF format.
 This code scrapes the PDFs for data and auto updates a visualization on a website.

 Step 1:
 - Find PDF on the US DOL website using BeautifulSoup
 - Scrape PDF using Camelot
 - Find the relevant <table> elements and clean up data
 - Turn the data into a CSV named statewise-claims.csv

 Step 2:
 - Make it a GitHub repository
 - Turn on GitHub Actions
 - Set up the .yml file
 
 Step 3:
 - Create a html page for the visualization, name it index.html
 - Add it to repo and push it up to GitHub
 - Turn on GitHub Pages 
 
 Step 4:
 - Make a visualization for the webpage usng DataWrapper
 - Linking to CSV data
 - Update our html with the embed code for the visualization
 - Push it on up to GitHub Pages
 - GitHub actions will finish deploying  web page


