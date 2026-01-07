This dashboard was created independently for personal research and analysis. It is not affiliated with, endorsed by, or produced in partnership with the City of Montréal
or the Service de police de la Ville de Montréal (SPVM). All data is sourced from a publicly available open dataset provided through the City of Montréal’s open data portal.
Any interpretations, analyses, or conclusions presented here are solely my own.

As of 2025-12-31: This dashboard is in the process of revision for reasons stated below:
1. Updated offences from the month of December 2025, to fully capture the calendar year.
2. Reverse geocoding is being performed through R and Nomatim for geographical, neighbourhood, and police district analysis. Due the Nomatim's nature of being a public API,
   the geocoding rate limit is capped at a maximum of one per second. With a dataset of over 76,000 rows of data, and speed at which my MacBook processes reverse geocodes
   all spatial coordinates, additional time is required. 

Due to ongoing issues with uploading the dashboard to the Public Power BI Service for publishing, screenshots of pages have been added to the repository,
showcasing the generated visuals, and DAX measures computed.
