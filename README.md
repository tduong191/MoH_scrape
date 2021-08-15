# MoH_covid_scrape
This script is used to mine COVID-19 related news on the Ministry of Health.

`MoH_scrape` uses Rvest to scrape html text on the website.
`MoH_dataset` wrangles free-text news articles into a linelisting. Each row contains a patient's ID and a patient's information.
`nihe_moh` compares the data consistency of NIHE with the dataset mined from MoH.
