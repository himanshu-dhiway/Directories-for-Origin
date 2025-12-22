***

## Hi, Himanshu this side, the task for compiling all the necessary directories is given to me and I feel that I should be more casual while sharing this data to you as I want to explain everything why each of the datasets are really necessary for the origin and how we can implement them in origin in the first place. 

this is the first draft and it will keep on changing I am mostly splitting my time learning rust and scraping directories across the internet , the moment I feel confident on rust I will start on developing the origin too, I hope this goes well.

the directories mentioned downward are just the glimpses of the directories that I scraped and can be used in origin apart from this I made one more doc called as priority doc which adds my personal commentory on which datasets should or must be used first to get the desired results.
I hope you love this;)

## Oasis Directories: BFSI Data Source Repository

Oasis provides a centralized library of public and commercial data sources crucial for compliance, verification, and due diligence in Banking, Financial Services, and Insurance (BFSI) operations. The repository covers identity verification, AML checks, sanctions screening, corporate and asset verification, and more.

### Documentation Structure

- **Sanctions and Watchlists**  
  International sanctions and watchlists: OFAC, UN, EU, UAPA, ASIC, SEC EDGAR—mandatory for AML/CFT.

- **Government Databases**  
  Indian official registries: MCA-21, company master data, DIN, financial statements—vital for KYC and due diligence.

- **Open Source Alternatives**  
  Cost-effective platforms: OpenSanctions, ICIJ Offshore Leaks, OpenCorporates—useful for startups and smaller players.

- **Global Identity Verification**  
  Global tools: LEI via GLEIF, Interpol Red Notices—support cross-border and trade finance checks.

- **Open Government Data**  
  Indian open data: Data.gov.in, India Data Portal, MoSPI, SEBI filings, NCRB stats—used for market research and risk.

- **Property and Asset Verification**  
  Land records: state portals, CERSAI, encumbrance certificates—critical for lending and collateral checks.

### Key Features

- **Direct URLs to databases/APIs**, with notes on cost/free access.
- **Update frequency** (daily/monthly/real-time).
- **Compliance context**: Mandates, penalties, privacy laws.
- **API, data formats, integration, and best practices guidance**.

### Use Cases

- **Compliance/risk**: Sanctions, PEP, adverse media, AML/CFT.
- **Credit/lending**: KYC, financial analysis, collateral checks.
- **Fraud**: Identity, criminal, offshore checks.
- **International banking**: Due diligence, transaction screening.

### Data Category Table

| Category            | Free Sources                   | Paid Options                | Use Case                   |
|---------------------|-------------------------------|-----------------------------|----------------------------|
| Sanctions           | OFAC, UN, EU, UAPA            | World-Check, Dow Jones      | AML/CFT Compliance         |
| Corporate Check     | MCA-21, OpenCorporates        | D&B, CMIE Prowess           | KYC, Due Diligence         |
| Identity            | PAN, Aadhaar (via providers)  | CIBIL, Experian             | Onboarding, Risk           |
| Property            | State portals, CERSAI         | Usually free                | Collateral Verification    |
| Criminal/PEP        | Interpol, NCRB, OpenSanctions | LexisNexis, World-Check     | Enhanced Due Diligence     |

### Contributions and Maintenance

- **Add/Correct sources**: Open issues or submit pull requests.
- **Monthly updates**: Links checked, new sources added.
- **Community feedback**: Share bugs, suggestions, and best practices.

### Legal & Compliance

- **Follow DPDP Act, IT Act, RBI, PMLA**
- **User consent needed for personal data**
- **Strict data security and compliance**

### Technical Details

- **Directory Structure**: Markdown docs under `/docs/` for easy access and editing.
- **Navigation**: Use GitHub search and table of contents.

### Support & Contact

- Open GitHub issues for questions, bugs, and features.
- Join discussions for best practices and community help.

### Version and License

- Version: 1.0 (Last update: Nov 2025)
- License: [Specify license type]
- Repo: [https://github.com/himanshu-dhiway/Directories-for-Oasis]

***
