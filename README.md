# dataplus20

# Program Outline: 

Answering questions of interest for the Duke Energy Access Project and the Duke Energy Initiative:

* To convert pdf scans of archival documents into usable, spreadsheet-style data about electricity usage in rural areas.
* To use this data to understand the impact of two New-Deal Era government programs intended to expand rural access to electricity and promote electricity usage.
* Evaluate the potential for similar programs to expedite the expansion of electricity access in developing countries around the world.

Exploring historical data on the U.S. Electric Farm Equipment (EFE) demonstration show that ran between 1939 and 1941, which aimed to increase usage of electricity in rural areas. 

Comparing data from the EFE and a related, smaller-scale project from 1923 (“Red Wing Project”) to current data on appliance promotion programs in villages in East Africa that have recently gained access to electricity.

# Week 1-2: 

* Scraping data from 1941.Directory of electric utilities in the US pdf.pdf through package `pdftools`, `pdftables`, `tabulizer`, and `tabulizerjars` in R. 
* Attempting to scrape data using package `tabula` and `camelot` in python but did not succeed.
* Successfully scrape data from 50 states, including their companies and statistics: Electric Utility Plant, Electric Operating Revenues, Electric Customers, and Energy Purchased. 
