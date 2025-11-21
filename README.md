# Directories for Oasis

A comprehensive repository of publicly accessible databases and data sources used by the Banking, Financial Services, and Insurance (BFSI) sector for compliance, verification, and due diligence operations.

---

## Overview

This repository serves as a centralized knowledge base for data sources essential to BFSI operations, including identity verification, anti-money laundering (AML) compliance, sanctions screening, corporate due diligence, and asset verification. All sources documented here are either publicly accessible or available through standard commercial licensing.

---

## Documentation Structure

### Sanctions and Watchlists
**File:** [sanctions-watchlists.md](docs/sanctions-watchlists.md)

Comprehensive coverage of international sanctions lists and watchlists including:
- OFAC (Office of Foreign Assets Control, US Treasury)
- UN Security Council Sanctions
- EU Sanctions Map and Consolidated Lists
- UAPA (Unlawful Activities Prevention Act, India)
- ASIC (Australian Securities and Investments Commission)
- SEC EDGAR (US Securities Filings)

These sources are critical for AML/CFT compliance and mandatory screening requirements under various regulatory frameworks.

---

### Government Databases
**File:** [government-databases.md](docs/government-databases.md)

Official Indian government databases for corporate verification:
- MCA-21 (Ministry of Corporate Affairs)
  - Company Master Data Search
  - Director Identification Number (DIN) Search
  - Corporate filings and financial statements
  - Beneficial ownership information

Essential for KYC compliance, credit assessment, and corporate due diligence.

---

### Open Source Alternatives
**File:** [open-source-alternatives.md](docs/open-source-alternatives.md)

Free and open-source tools providing cost-effective alternatives to commercial databases:
- **OpenSanctions** - Consolidated sanctions and PEP data with API access
- **ICIJ Offshore Leaks Database** - Panama Papers, Pandora Papers, beneficial ownership data
- **OpenCorporates** - Global company database with 200+ million entities

Particularly valuable for startups, small financial institutions, and organizations with budget constraints.

---

### Global Identity Verification
**File:** [global-identity-verification.md](docs/global-identity-verification.md)

International verification systems for cross-border transactions:
- **LEI (Legal Entity Identifier)** - GLEIF database for corporate entity verification
- **Interpol Notices** - Red Notices and international criminal database

Critical for correspondent banking, trade finance, and international risk assessment.

---

### Open Government Data
**File:** [open-government-data.md](docs/open-government-data.md)

Indian government open data portals providing economic and corporate intelligence:
- Data.gov.in - National open data platform
- Company Master Data - Bulk corporate information
- India Data Portal - Economic indicators and statistics
- MoSPI Compendium - Comprehensive registry of all government datasets
- SEBI Securities Market Data - Stock market and regulatory filings
- NCRB Data - Crime statistics for risk profiling

Valuable for market research, credit policy decisions, and risk assessment.

---

### Property and Asset Verification
**File:** [property-asset-verification.md](docs/property-asset-verification.md)

Land records and asset registries for collateral verification:
- State-wise land record portals (Maharashtra, Karnataka, Delhi, Tamil Nadu, etc.)
- CERSAI (Central Registry of Securitisation Asset Reconstruction and Security Interest)
- Encumbrance certificates and property ownership records

Essential for mortgage lending, secured loans, and asset-backed financing.

---

## Use Cases by Department

### Compliance and Risk Management
- Sanctions screening (OFAC, UN, EU lists)
- PEP (Politically Exposed Persons) identification
- Adverse media monitoring
- Regulatory reporting requirements
- AML/CFT compliance

### Credit and Lending
- Corporate verification (MCA-21, company registries)
- Credit bureau integration
- Financial statement analysis
- Director background checks
- Collateral verification (land records, CERSAI)

### Fraud Prevention
- Identity verification
- Criminal background screening (Interpol)
- Offshore entity tracking (ICIJ)
- Duplicate account detection
- Synthetic identity detection

### International Banking
- Correspondent banking due diligence
- Trade finance verification (LEI, foreign company registries)
- Cross-border transaction screening
- Foreign entity validation

---

## Key Features

### Direct Access
All database entries include direct URLs to search portals, download pages, or API endpoints. No unnecessary navigation required.

### Cost Transparency
Each source clearly indicates whether it is:
- Free and publicly accessible
- Requires registration but no cost
- Commercial/paid service with pricing information

### Update Frequency
Documentation specifies how often each database is updated (daily, monthly, annual, real-time) to help assess data freshness.

### Compliance Context
Includes information on:
- Regulatory mandates requiring specific checks
- Legal frameworks (RBI guidelines, PMLA, FATF recommendations)
- Penalties for non-compliance
- Data privacy requirements (DPDP Act 2023)

### Implementation Guidance
Practical information including:
- API availability and documentation links
- Data formats (CSV, XML, JSON, etc.)
- Integration considerations
- Best practices for each source

---

## Target Audience

### Financial Institutions
- Public Sector Banks
- Private Sector Banks
- Foreign Banks operating in India
- Non-Banking Financial Companies (NBFCs)
- Housing Finance Companies
- Microfinance Institutions

### Insurance Companies
- Life Insurance
- General Insurance
- Health Insurance

### Fintech Organizations
- Digital Lending Platforms
- Payment Service Providers
- Neobanks
- Wealth Management Platforms
- RegTech Solutions

### Professional Services
- Compliance Consulting Firms
- Risk Advisory Services
- Audit and Assurance Firms
- Legal Advisory Services
- KYC Service Providers

---

## Getting Started

### For Compliance Officers
1. Begin with the Sanctions and Watchlists documentation for mandatory screening requirements
2. Review Government Databases for corporate KYC procedures
3. Consult Open Government Data for enhanced due diligence

### For Credit Analysts
1. Start with Government Databases (MCA-21) for company verification
2. Review Property and Asset Verification for collateral assessment
3. Use Open Government Data for industry analysis and economic indicators

### For Risk Managers
1. Examine Global Identity Verification for international exposure assessment
2. Review Sanctions and Watchlists for regulatory compliance
3. Consider Open Source Alternatives for cost-effective screening solutions

### For Developers and IT Teams
1. Each documentation file includes API endpoints where available
2. Data format specifications for integration planning
3. Update frequencies to design refresh schedules
4. Rate limiting and authentication requirements

---

## Data Categories Summary

| Category | Free Sources | Paid Options | Primary Use Case |
|----------|-------------|--------------|------------------|
| Sanctions Screening | OFAC, UN, EU, UAPA | World-Check, Dow Jones | AML/CFT Compliance |
| Corporate Verification | MCA-21, OpenCorporates | Dun & Bradstreet, CMIE Prowess | KYC, Due Diligence |
| Identity Verification | Aadhaar (via providers), PAN | CIBIL, Experian | Customer Onboarding |
| Property Records | State Land Registries, CERSAI | None typically required | Collateral Verification |
| Criminal Records | Interpol (limited), NCRB Stats | Background check services | Enhanced Due Diligence |
| PEP Screening | OpenSanctions | World-Check, LexisNexis | High-Risk Customer Review |

---

## Contributing

Contributions to this repository are welcome and encouraged. You can contribute by:

### Adding New Sources
If you discover additional databases or data sources relevant to BFSI operations:
1. Fork the repository
2. Add the information to the appropriate documentation file
3. Include: URL, description, cost, update frequency, and use case
4. Submit a pull request with clear description

### Updating Existing Information
If you find outdated information, broken links, or pricing changes:
1. Open an issue describing the problem
2. Or submit a pull request with corrections
3. Include verification source for factual updates

### Suggesting Improvements
For structural improvements, new categories, or enhanced documentation:
1. Open an issue with your proposal
2. Provide rationale and examples
3. Engage in discussion with maintainers

---

## Legal and Compliance Considerations

### Data Privacy
All data access must comply with:
- Digital Personal Data Protection Act (DPDP) 2023
- Information Technology Act 2000
- RBI Master Directions on KYC
- PMLA (Prevention of Money Laundering Act) 2002

### User Consent
Explicit user consent is required before accessing personal data from most sources, particularly:
- Credit bureau information
- Aadhaar-based verification
- Bank account details
- Biometric data

### Purpose Limitation
Data accessed from these sources must be used only for stated legitimate business purposes. Unauthorized use, resale, or misuse of data is prohibited and may result in legal action.

### Data Security
Organizations must implement appropriate security measures:
- Encryption of data at rest and in transit
- Access controls and authentication
- Audit trails for all data access
- Regular security assessments
- Incident response procedures

### Regulatory Compliance
Financial institutions must maintain:
- Documentation of all data sources used
- Audit trails of verification activities
- Periodic reviews of data accuracy
- Compliance with sector-specific regulations (RBI, SEBI, IRDAI)

---

## Important Disclaimers

### Accuracy
While every effort is made to ensure accuracy, this repository provides links and information for reference only. Users must:
- Verify information from official sources
- Cross-check critical data across multiple databases
- Maintain their own compliance procedures
- Not rely solely on this documentation for regulatory compliance

### Availability
External databases and APIs are maintained by third parties. Links, pricing, and availability may change without notice. Users should:
- Verify current access methods directly with providers
- Establish direct relationships with critical data sources
- Maintain alternative sources for mission-critical verification

### Legal Advice
This repository does not constitute legal advice. Organizations should:
- Consult qualified legal counsel for compliance requirements
- Engage regulatory experts for interpretation of guidelines
- Maintain internal legal review of data usage practices
- Stay updated on regulatory changes independently

### Data Ownership
All databases and data sources referenced remain the property of their respective owners. This repository merely provides links and information about publicly accessible resources.

---

## Maintenance and Updates

### Update Schedule
This repository is reviewed and updated on a monthly basis to ensure:
- Links remain functional
- Pricing information stays current
- New data sources are added
- Regulatory changes are reflected
- User feedback is incorporated

### Version History
Major updates are tracked through:
- Git commit history
- Release tags for significant versions
- Changelog documentation
- Issue tracking for requested changes

### Community Feedback
Users are encouraged to:
- Report broken links or outdated information
- Suggest additional sources
- Share implementation experiences
- Contribute best practices

---

## Repository Statistics

- **Total Databases Documented:** 25+
- **Free/Public Sources:** 18+
- **Countries Covered:** 12+
- **Documentation Files:** 6 comprehensive guides
- **Last Major Update:** November 2025
- **Active Maintenance:** Ongoing

---

## Technical Details

### Repository Structure
```
Directories-for-Oasis/
├── README.md
└── docs/
    ├── sanctions-watchlists.md
    ├── government-databases.md
    ├── open-source-alternatives.md
    ├── global-identity-verification.md
    ├── open-government-data.md
    └── property-asset-verification.md
```

### File Format
All documentation is maintained in Markdown format for:
- Easy readability in plain text
- Proper rendering on GitHub
- Version control compatibility
- Simple editing and contribution
- Cross-platform accessibility

### Navigation
- Use GitHub's built-in search (press '/' key)
- Browse by category through table of contents
- Direct links to specific sections
- Cross-references between related topics

---

## Support and Contact

### Questions and Issues
For questions, problems, or discussions:
- Open an issue in the GitHub repository
- Use issue templates for bug reports or feature requests
- Check existing issues before creating duplicates
- Provide detailed information for faster resolution

### Feature Requests
To suggest new features or improvements:
- Open an issue with "Feature Request" label
- Describe the proposed addition or change
- Explain the use case and benefits
- Be open to discussion and iteration

### General Discussion
For broader topics, best practices, or community discussion:
- Use GitHub Discussions feature
- Share implementation experiences
- Ask for advice from community
- Contribute your own insights

---

## Acknowledgments

This repository aggregates information from numerous sources including:
- Reserve Bank of India regulatory guidelines
- Government of India open data initiatives
- International regulatory bodies (FATF, UN, EU)
- Open-source projects and communities
- BFSI industry practitioners
- Compliance and risk management professionals

### Data Providers
Special acknowledgment to organizations maintaining public databases:
- Ministry of Corporate Affairs, Government of India
- Financial Intelligence Unit - India (FIU-IND)
- Securities and Exchange Board of India (SEBI)
- US Treasury Department (OFAC)
- United Nations Security Council
- European Union
- Global Legal Entity Identifier Foundation (GLEIF)
- International Criminal Police Organization (Interpol)
- International Consortium of Investigative Journalists (ICIJ)
- OpenSanctions and OpenCorporates projects

---

## License

This repository and its documentation are provided for informational and reference purposes. The information compiled here is based on publicly available sources and does not constitute official guidance from any regulatory authority.

Individual databases and data sources are owned and operated by their respective authorities. Users must comply with the terms of use, licensing requirements, and access restrictions of each individual source.

The documentation in this repository is available under [specify license - e.g., MIT License, CC BY 4.0, or state as proprietary].

---

## Version Information

**Current Version:** 1.0  
**Last Updated:** November 2025  
**Maintained By:** Dhiway  
**Repository URL:** https://github.com/himanshu-dhiway/Directories-for-Oasis

---

**For the BFSI Compliance and Risk Management Community**

*Providing accessible, verified, and comprehensive information on data sources essential for financial sector operations.*
