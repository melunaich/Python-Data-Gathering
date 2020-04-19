## Extract Profiles from Xero

Here, we go through the [search result pages](https://www.xero.com/uk/advisors/find-advisors/?type=advisors&tag[]=xero:advisor-directory/industries-served/repairs-and-personal-services&orderBy=ADVISOR_RELEVANCE&sort=ASC&pageNumber=1) on Xero.com where our filter criteria is to select advisors from UK for 'Repair and Personal Services'. From the search results, we extract certain details (described below) into a pandas dataframe and also write into a csv file.

Example Profile URL:
https://www.xero.com/uk/advisors/accountant/mha-macintyre-hudson-db7b338a4f1d/

Required fields:
- Name (e.g. MHA MacIntyre Hudson)
- Type (e.g. Accountant)
- Address (e.g. 1 The Forum, Minerva Business Park, Lynchwood, Peterborough, England)
- About us text
- Website
- Phone number
- Facebook address (if available)
- Twitter address (if available)
- Linkedin address (if available)




