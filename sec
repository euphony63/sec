#import libraries
import requests
from bs4 import BeutifulSoup

#define base url
base_url=r"https://www.sec.gov/Archives/edgar/data"

#define CIK number
cik_num='842790'

#create a filing url
filings_url=base_url+cik_num+"/index.json"

#request the url
content=requests.get(filings_url)
decoded_content=content.json()

#go and grab a single filing number
filing_number=
