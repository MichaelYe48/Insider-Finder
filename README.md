# Insider-Finder

Insider Finder is a webscraper that parses SEC form filings to locate company insiders, who are the "senior executives, directors, and 10%+ shareholders" of a given company.
The script utilizes the Electronic Data Gathering, Analysis, and Retrieval (EDGAR) API to produce datasets containing forms 3 (ownership disclosures) and 4 (insider transactions) required by the SEC for insiders to report. 
To identify the insider, I used an HTML parser (Beautiful Soup) to look for the "reporting person."

I used the Flask framework to build a website that allows users to search up insiders for different companies. You can find the link here:
