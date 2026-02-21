# State-Chartered Credit Union Data

## About this dataset

Contains listings of state-chartered credit unions in the United States, sourced from state regulatory agencies.

## Texas

- Data source: [Texas Credit Union Department (CUD)](https://cud.texas.gov/)
- Data period: August 2025
- Credit unions: 160
- File: [texas.csv](texas.csv)
- Raw source: [Texas-State-Chartered-Credit-Unions-08-2025.pdf](Texas-State-Chartered-Credit-Unions-08-2025.pdf)
- Disclaimer: authors not affiliated with CUD

### Methodology

1. Download the "List of Texas State-Chartered Credit Unions" PDF from https://cud.texas.gov/consumer-resources/list-texas-state-chartered-credit-unions/
2. Extract credit union name, city, and phone number into [texas.csv](texas.csv)

## Virginia

- Data source: [Bureau of Financial Institutions, State Corporation Commission (SCC)](https://www.scc.virginia.gov/consumers/banks-consumer-lenders/regulated-financial-institutions/)
- Data period: February 18, 2026
- Credit unions: 18
- File: [virginia.csv](virginia.csv)
- Raw source: [Virginia-State-Chartered-Credit-Unions-02-2026.pdf](Virginia-State-Chartered-Credit-Unions-02-2026.pdf)
- Disclaimer: authors not affiliated with SCC

### Methodology

1. Download the "State-Chartered Credit Unions" PDF from https://www.scc.virginia.gov/consumers/banks-consumer-lenders/regulated-financial-institutions/
2. Extract credit union name and city into [virginia.csv](virginia.csv)

## Washington

- Data source: [Department of Financial Institutions (DFI), Division of Credit Unions](https://dfi.wa.gov/credit-unions)
- Data period: February 2026
- Credit unions: 48
- File: [washington.csv](washington.csv)
- Disclaimer: authors not affiliated with DFI

### Methodology

1. Scrape the list of Washington state-chartered credit unions from https://dfi.wa.gov/credit-unions/list-washington-state-chartered-credit-unions
2. Extract credit union name, city, and phone number into [washington.csv](washington.csv)

## Florida

- Data source: [Office of Financial Regulation (OFR)](https://flofr.gov/divisions-offices/division-of-financial-institutions/credit-unions)
- Data period: 2025
- Credit unions: 63
- File: [florida.csv](florida.csv)
- Raw source: [Florida-Financial-Institution-Resource-List.pdf](Florida-Financial-Institution-Resource-List.pdf)
- Disclaimer: authors not affiliated with OFR

### Methodology

1. Download the "Florida Financial Institution Resource List" PDF from https://flofr.gov/divisions-offices/division-of-financial-institutions/credit-unions
2. Extract credit union charter number, name, and website into [florida.csv](florida.csv)

## Illinois

- Data source: [NCUA Federally Insured Credit Union List](https://ncua.gov/analysis/credit-union-corporate-call-report-data) (filtered for Illinois state-chartered credit unions)
- Data period: Q3 2025 (September 2025)
- Credit unions: 137
- File: [illinois.csv](illinois.csv)
- Disclaimer: authors not affiliated with NCUA or IDFPR

### Methodology

1. Download the NCUA Federally Insured Credit Union List (Q3 2025) from https://www.ncua.gov/files/publications/analysis/federally-insured-credit-union-list-september-2025.zip
2. Filter for Illinois (`State = IL`) and state-chartered (`Credit Union type = 2`)
3. Extract credit union charter number, name, and city into [illinois.csv](illinois.csv)

Note: The Illinois Department of Financial and Professional Regulation (IDFPR) does not currently publish a downloadable list of state-chartered credit unions, so the NCUA data was used as an alternative source.

## North Carolina

- Data source: [Credit Union Division, NC Department of Commerce](https://cud.nc.gov/)
- Data period: December 31, 2024
- Credit unions: 30 (29 natural person + 1 corporate)
- File: [north_carolina.csv](north_carolina.csv)
- Raw source: [NC-Credit-Union-Annual-Report-2024.pdf](NC-Credit-Union-Annual-Report-2024.pdf)
- Disclaimer: authors not affiliated with NC Credit Union Division

### Methodology

1. Download the 2024 Annual Report PDF from https://cud.nc.gov/Portals/CUD/2024%20NC%20Credit%20Union%20Division%20Annual%20Report.pdf
2. Extract credit union name, city, and phone number from the balance sheet pages into [north_carolina.csv](north_carolina.csv)

## Louisiana

- Data source: [Office of Financial Institutions (OFI)](https://ofi.la.gov/depository/credit-unions/active-credit-unions/)
- Data period: February 20, 2026
- Credit unions: 25
- File: [louisiana.csv](louisiana.csv)
- Disclaimer: authors not affiliated with OFI

### Methodology

1. Scrape the list of active credit unions from https://ofi.la.gov/depository/credit-unions/active-credit-unions/
2. Extract credit union name, city, and phone number into [louisiana.csv](louisiana.csv)

## Maryland

- Data source: [Office of the Commissioner of Financial Regulation, Maryland Department of Labor](https://labor.maryland.gov/finance/consumers/cusc.shtml)
- Data period: September 19, 2025
- Credit unions: 7
- File: [maryland.csv](maryland.csv)
- Disclaimer: authors not affiliated with Maryland Office of the Commissioner of Financial Regulation

### Methodology

1. Scrape the directory of chartered financial institutions from https://labor.maryland.gov/finance/consumers/frdirfininst.shtml
2. Extract credit union name, city, and phone number into [maryland.csv](maryland.csv)

## Oregon

- Data source: [Division of Financial Regulation (DFR), Department of Consumer and Business Services](https://dfr.oregon.gov/financial/manage/pages/state-chartered-credit-unions.aspx)
- Data period: February 2026
- Credit unions: 20
- File: [oregon.csv](oregon.csv)
- Disclaimer: authors not affiliated with DFR

### Methodology

1. Scrape the list of state-chartered credit unions from https://dfr.oregon.gov/financial/manage/pages/state-chartered-credit-unions.aspx
2. Extract credit union name, city, and phone number into [oregon.csv](oregon.csv)

Note: Northwest Community Credit Union merged into TwinStar Credit Union (Washington-chartered) effective June 12, 2023 and is excluded from this dataset.

## Wisconsin

- Data source: [NCUA Federally Insured Credit Union List](https://ncua.gov/analysis/credit-union-corporate-call-report-data) (filtered for Wisconsin state-chartered credit unions)
- Data period: Q3 2025 (September 2025)
- Credit unions: 99
- File: [wisconsin.csv](wisconsin.csv)
- Disclaimer: authors not affiliated with NCUA or WI DFI

### Methodology

1. Download the NCUA Federally Insured Credit Union List (Q3 2025) from https://www.ncua.gov/files/publications/analysis/federally-insured-credit-union-list-september-2025.zip
2. Filter for Wisconsin (`State = WI`) and state-chartered (`Credit Union type = 2`)
3. Extract credit union charter number, name, and city into [wisconsin.csv](wisconsin.csv)

Note: The Wisconsin Department of Financial Institutions publishes quarterly Credit Union Bulletins with aggregate financial data, but these do not include individual credit union listings, so the NCUA data was used as an alternative source.

## See also

- [NCUA Data for Federally Insured Credit Unions](https://github.com/credit-union-datasets/credit-union-ncua) - NCUA listing of federally insured credit unions
- [Credit Union Website Addresses](https://github.com/credit-union-datasets/credit-union-websites) - website addresses scraped from NCUA, keyed by charter number
- [Credit Union Membership Data](https://github.com/credit-union-datasets/credit-union-membership) - membership data scraped from credit union websites
- [Credit Union HYSA Rates](https://github.com/credit-union-datasets/credit-union-hysa) - high-yield savings account rates at credit unions
