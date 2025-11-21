# Global Identity Verification

> International databases for corporate entity verification and criminal background checks

---

## Table of Contents
1. [LEI (Legal Entity Identifier)](#lei-legal-entity-identifier)
2. [Interpol Notices](#interpol-notices)

---

## LEI (Legal Entity Identifier)

**Authority:** Global Legal Entity Identifier Foundation (GLEIF)

### What It Is
The Legal Entity Identifier (LEI) is a 20-character, alpha-numeric code that uniquely identifies legally distinct entities that engage in financial transactions.

### What It Contains
- Unique 20-character identifier for each legal entity
- Official company name
- Registered address
- Headquarters address
- Registration details
- Parent company information (if applicable)
- Status (active/inactive)

### Direct Access

| Resource | URL | Cost |
|----------|-----|------|
| **GLEIF Search Portal** | https://search.gleif.org | FREE |
| **GLEIF API** | https://www.gleif.org/en/lei-data/gleif-api | FREE |
| **Download Data** | https://www.gleif.org/en/lei-data/gleif-concatenated-file | FREE |

### Why BFSI Uses This
**Global corporate identity standard** - LEI is the internationally recognized identifier for entities in financial transactions. **Regulatory reporting requirement** - Mandatory under MiFID II, EMIR, Dodd-Frank, and other regulations for financial market participants.

### Key Features
- Universal identifier across borders
- Hierarchical relationship data (parent-subsidiary)
- No duplicates possible
- Validated by accredited issuers
- Annually renewed and verified

### Use Cases for BFSI
1. **Trade Finance** - Verify foreign counterparties
2. **Regulatory Reporting** - Required for derivatives and securities transactions
3. **KYC Compliance** - Standardized entity identification
4. **Credit Risk Management** - Track corporate groups and subsidiaries
5. **AML Screening** - Cross-reference with sanctions lists

### How to Search
1. Go to https://search.gleif.org
2. Search by:
   - Company name
   - LEI code
   - Registration number
   - Country
3. View complete entity profile
4. Download data as needed

### LEI Structure
```
Example LEI: 549300PKPA2SNBB3HZ09

First 4 characters: LOU (Local Operating Unit) ID
Characters 5-6: Reserved (00)
Characters 7-18: Entity-specific identifier
Characters 19-20: Check digits
```

---

## Interpol Notices

**Authority:** International Criminal Police Organization (Interpol)

### What It Is
Interpol Notices are international alerts that allow police in member countries to share critical information about criminals and crime.

### Types of Notices

| Color | Purpose |
|-------|---------|
| **Red Notice** | To seek arrest/extradition of wanted persons |
| **Blue Notice** | To collect additional information about a person's identity |
| **Green Notice** | Warning about habitual criminals |
| **Yellow Notice** | To help locate missing persons |
| **Black Notice** | Information on unidentified bodies |
| **Orange Notice** | Warning about threats from disguised weapons or terrorist attacks |
| **Purple Notice** | Information on modus operandi used by criminals |

### Direct Access

| Resource | URL | Cost |
|----------|-----|------|
| **Red Notices (Public)** | https://www.interpol.int/en/How-we-work/Notices/View-Red-Notices | FREE |
| **Search Portal** | https://www.interpol.int/How-we-work/Notices/View-Notices | FREE |

### Why BFSI Uses This
**Criminal background screening** - Prevents banking services to fugitives and wanted criminals. **Cross-border risk mitigation** - Essential for international accounts and correspondent banking relationships.

### What's Publicly Available
- Red Notices for wanted persons
- UN Sanctions List entries
- Search by name, nationality, age

### What's NOT Public
- Most Blue, Green, Yellow notices
- Full case details
- Investigation information

### Use Cases for BFSI
1. **Customer Onboarding** - Screen against wanted persons
2. **High-Risk Customer Review** - Enhanced due diligence
3. **Correspondent Banking** - Verify international partners
4. **Compliance Audits** - Regulatory requirement for some jurisdictions
5. **Fraud Prevention** - Identify known criminals

### How to Use
1. Go to https://www.interpol.int/en/How-we-work/Notices/View-Red-Notices
2. Click "Search Red Notices"
3. Enter search criteria:
   - Name (last name, first name)
   - Nationality
   - Age range
4. Review results
5. Note: Only publicly available notices are shown

### Important Notes
⚠️ **Not all wanted persons appear on public Red Notices**
⚠️ **Some countries request notices remain confidential**
⚠️ **Presence on list doesn't confirm guilt** - legal presumption of innocence applies

### Integration Tips
- Check against Interpol during enhanced due diligence
- Automate screening for PEPs and high-risk customers
- Manual review recommended for positive matches
- Document all searches for audit trail

---

## Comparison: LEI vs Interpol

| Aspect | LEI | Interpol Notices |
|--------|-----|------------------|
| **Purpose** | Entity identification | Criminal tracking |
| **Scope** | Corporate entities | Individuals |
| **Coverage** | Global | 195 member countries |
| **Cost** | Free search | Free |
| **Update** | Annual renewal | Real-time |
| **Use Case** | Corporate KYC | Criminal background |
| **API** | Yes | No public API |

---

*Last Updated: November 2025*
