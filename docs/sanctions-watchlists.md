# Sanctions & Watchlists (Publicly Accessible)

> Free, publicly accessible sanctions lists used by BFSI sector for AML/CFT compliance

---

## Table of Contents
1. [OFAC (US Treasury)](#ofac-us-treasury)
2. [UN Security Council Sanctions](#un-security-council-sanctions)
3. [EU Sanctions Map](#eu-sanctions-map)
4. [UAPA Sanctions (India)](#uapa-sanctions-india)
5. [ASIC (Australia)](#asic-australia)
6. [SEC EDGAR (US)](#sec-edgar-us)

---

## OFAC (US Treasury)

**Authority:** Office of Foreign Assets Control, US Department of Treasury

### What It Contains
- Specially Designated Nationals (SDN) List
- Blocked persons and entities
- Sector sanctions
- Country-based sanctions

### What is OFAC?
- OFAC is a U.S. Treasury agency that administers and enforces economic and trade sanctions against targeted countries, regimes, individuals, and entities involved in terrorism, narcotics trafficking, proliferation of weapons of mass destruction, and other threats to U.S. national security and foreign policy.

### Purpose of the OFAC Sanctions Registry
- The OFAC registry helps users search for individuals, entities, vessels, and aircraft that are subject to U.S. sanctions. It combines several lists, most importantly:​
- The Specially Designated Nationals (SDN) List: Names of individuals, organizations, and vessels whose assets are blocked and with whom U.S. persons are generally prohibited from dealing.​
- The Consolidated Non-SDN List: Contains names subject to specific, targeted restrictions (sectoral sanctions, transaction limits, etc.) but not complete asset freezes.

### Compliance Importance(reason why BFSI use this)
- U.S. persons and organizations must screen against both lists (SDN and Non-SDN) to avoid direct or indirect dealings with sanctioned parties, which can carry heavy legal and financial penalties.
- Compliance protects businesses not only from regulatory action, but also from reputational and financial risk linked to inadvertent involvement with sanctioned individuals or organizations.

### Updates and Usage.
- The SDN list and Non-SDN consolidated list are frequently updated as global events occur; the tool shows the last update date and provides recent downloadable datasets.(you can access them through the officail website of OFAC here : https://ofac.treasury.gov/sanctions-list-service)
- The tool supports compliance officers, financial institutions, exporters, and others that need to verify counterparties.​

| List Name     | Description                                                                    | Consequence of Listing                    |
| ------------- | ------------------------------------------------------------------------------ | ----------------------------------------- |
| SDN List      | Comprehensive blocking: all assets frozen, all dealings generally prohibited . | Full asset freeze, U.S. dealings banned . |
| Non-SDN Lists | Targeted sanctions: limits on transactions, sectors, or export controls .      | Limited restrictions, not full block .    |

### Direct Access

| Resource | URL | Format |
|----------|-----|--------|
| **Web Search** | https://sanctionssearch.ofac.treas.gov | Web Interface |
| **SDN List (TXT)** | https://www.treasury.gov/ofac/downloads/sdnlist.txt | TXT |
| **SDN List (XML)** | https://www.treasury.gov/ofac/downloads/sdn.xml | XML |
| **Consolidated List (XML)** | https://www.treasury.gov/ofac/downloads/consolidated/consolidated.xml | XML |

**Note:** Click on "Download SDN List" option on the search page

The OFAC SDN (Specially Designated Nationals) list and the Non‑SDN consolidated list differ fundamentally in the scope and severity of restrictions imposed:
### SDN List: Comprehensive Blocking Sanctions
- The SDN list contains individuals, entities, vessels, and aircraft whose assets are blocked and with whom U.S. persons are generally forbidden to engage in any transactions.
- Being listed as an SDN means complete asset freezes and near-total prohibition on financial dealings or provision of services with the listed parties.
- SDNs may include those acting on behalf of targeted countries, international terrorists, narcotics traffickers, and proliferators of weapons of mass destruction, among others.

### Non‑SDN Consolidated List: Targeted, Limited Restrictions
- The Non‑SDN consolidated list brings together entities and individuals subject to specific restrictions that do not amount to a full asset block.
- Restrictions may include financial transaction limits, sectoral bans (such as finance or energy), export controls, or participation prohibitions, but not a comprehensive freeze.
- Examples of lists within the consolidated Non-SDN list include the Sectoral Sanctions Identifications (SSI) list and Menu-Based Sanctions lists, which focus on targeted policy objectives.
- Parties on these lists can still engage in some business activity but within strict, narrowly defined limits.

### Comparison Table
| Aspect     | SDN List                                        | Non‑SDN Consolidated List                   |
| ---------- | ----------------------------------------------- | ------------------------------------------- |
| Scope      | Full asset block; all U.S. dealings forbidden   | Targeted sanctions; limited restrictions    |
| Programs   | International terrorism, WMD, country sanctions | Sectoral, menu-based, export controls, etc. |
| Compliance | Any transaction triggers severe penalties       | Certain types of dealings are prohibited    |

### Update Frequency
Daily

---

## UN Security Council Sanctions

- The UN Security Council (UNSC) Consolidated List contains all individuals and entities subject to UN sanctions across all active sanctions regimes (terrorism, DPRK, Iran, country conflicts, etc.). Sanctions can include asset freezes, arms embargoes, travel bans, and other restrictions, and all UN member states (including India) are expected to implement them via domestic law and regulation.
- Data typically includes: full name, aliases, date/place of birth, nationality, addresses, reasons for listing, and the specific sanctions regime. The list is provided in structured formats and is the “base layer” for many national lists (including OFAC and EU).​
- For Indian BFSI: RBI and Indian government notifications effectively require banks and NBFCs to ensure they are not dealing with parties on the UN list; many screening systems consume the UNSC consolidated list as a standard feed.

**Authority:** United Nations Security Council

### What It Contains
- Individuals and entities under UN sanctions
- Terrorism-related sanctions
- Country-specific sanctions
- 1267 Al-Qaida Sanctions List
- 1988 Taliban Sanctions List
- 1718 DPRK (North Korea) Sanctions List

### Why BFSI Uses This
**International compliance** - UN sanctions are globally binding. Terrorism financing prevention through Al-Qaida/Taliban/ISIL lists.

### Direct Access

| Resource | URL |
|----------|-----|
| **Consolidated List** | https://www.un.org/securitycouncil/content/un-sc-consolidated-list |
| **XML Download** | https://scsanctions.un.org/resources/xml-htm/consolidated.xml |
| **Search Portal** | https://scsanctions.un.org/search/ |

### Update Frequency
As Amended

---

## EU Sanctions Map

**Authority:** European Union

### What It Contains
- EU sanctions against individuals, entities, countries
- Asset freezes
- Travel bans

### Why BFSI Uses This
**European banking compliance** - Required for banks with EU exposure. Russia sanctions critical for geopolitical risk management post-2022.

### Direct Access

| Resource | URL |
|----------|-----|
| **Sanctions Map** | https://www.sanctionsmap.eu |
| **EU Data Portal** | https://data.europa.eu/data/datasets/consolidated-list-of-persons-groups-and-entities-subject-to-eu-financial-sanctions?locale=en |
| **Download Portal** | https://webgate.ec.europa.eu/fsd/fsf |
| **API Access** | https://webgate.ec.europa.eu/fsd/fsf/public/files/xmlFullSanctionsList_1_1/content?token=dG9rZW4tMjAxNw |

### Update Frequency
Daily

---

## UAPA Sanctions (India)

**Full Name:** Unlawful Activities (Prevention) Act

**Authority:** Ministry of Home Affairs, Government of India

### What It Contains
- Organizations and individuals designated as terrorists
- Fourth Schedule: Banned organizations
- First Schedule: Terrorist acts
- RBI Master Direction requires banks to screen against UAPA

### Why BFSI Uses This
**Domestic terrorism prevention** - RBI mandates screening against UAPA. Legal obligation under Indian law; non-compliance leads to prosecution.

### Direct Access

| Resource | URL |
|----------|-----|
| **MHA Website** | https://www.mha.gov.in |
| **Banned Organizations** | https://xn--i1b5bzbybhfo5c8b4bxh.xn--11b7cb3a6a.xn--h2brj9c/en/divisionofmha/counter-terrorism-and-counter-radicalization-division/Banned-Organizations |

### Update Frequency
As Notified

---

## ASIC (Australia)

**Full Name:** Australian Securities and Investments Commission

### What It Contains
- Australian companies
- Directors and officers
- Financial reports

### Why BFSI Uses This
**Australian entity verification** - For Australia-India trade finance. Director disqualification check for foreign directors.

### Direct Access

| Resource | URL | Cost |
|----------|-----|------|
| **Main Website** | https://asic.gov.au | - |
| **Register Search** | https://www.asic.gov.au/online-services/search-asic-registers/ | A$39-100 per search |
| **Free Datasets** | https://www.data.gov.au/data/organization/australian-securities-and-investments-commission-asic | FREE |

---

## SEC EDGAR (US)

**Authority:** US Securities and Exchange Commission

### What It Contains
- All US public company filings
- 10-K, 10-Q, 8-K reports
- Proxy statements

### Direct Access

| Resource | URL |
|----------|-----|
| **Search Portal** | https://www.sec.gov/edgar/search |
| **Example Query** | https://efts.sec.gov/LATEST/search-index?keysTyped=apple |

**Note:** Results are in PDF format - requires conversion to CSV for bulk processing

### Search Capabilities
- Search by company name
- Search by document number
- Search by location

---

*Last Updated: November 2025*
