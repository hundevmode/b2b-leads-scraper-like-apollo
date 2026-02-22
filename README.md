# B2B Leads Scraper (Like Apollo) | Verified Emails, LinkedIn URLs, Phones

**Pay-as-you-go B2B lead generation actor on Apify** for teams that need targeted contacts with rich enrichment data.

- Actor: [B2B Leads Scraper (Like Apollo)](https://console.apify.com/actors/LurATYM4hkEo78GVj/source)
- Model: Standard (non-rental)
- Pricing: **$1 per 1,000 leads**
- Capacity: **up to 50,000 leads per run**

This repository is intentionally **README-only** and serves as an index page for the live actor.

---

## Why this actor

If you are searching for an **Apollo alternative**, **LinkedIn leads scraper**, or a **B2B prospecting actor** with flexible filters, this actor is built for production lead generation workflows.

### Core value

- Extract B2B leads with professional profile fields
- Get email and contact enrichment where available
- Pull LinkedIn profile URLs for outreach workflows
- Build filtered lists by role, seniority, industry, location, and company size
- Run on-demand from Apify with export-ready output

---

## Powered by Dievio

This actor is part of the Dievio data workflow ecosystem.

- Dievio preview: [https://dievio.com/dashboard/preview](https://dievio.com/dashboard/preview)
- Use pagination-ready list building
- Save and manage lead lists for repeat exports
- Integrate into API-based automation
- Share output with team workflows

If you already use Dievio, this actor fits directly into existing lead sourcing pipelines.

---

## Pricing and limits

### Standard pay-per-use plan

- **$1 per 1,000 leads**
- **Max 50,000 leads per run**
- No subscription required
- Good for flexible/variable monthly usage

For current live settings, always check the actor page:
[https://console.apify.com/actors/LurATYM4hkEo78GVj/source](https://console.apify.com/actors/LurATYM4hkEo78GVj/source)

---

## Input schema (typical)

The exact schema is available in the actor UI, but common inputs include:

- `max_results`
- `job_titles`
- `job_title_seniority`
- `person_location_country`
- `person_location_region`
- `employee_size`
- `industries`
- `email_status`
- `include_emails`
- `include_phones`

### Example input

```json
{
  "max_results": 10000,
  "job_titles": ["CEO", "VP Sales", "Head of Marketing"],
  "job_title_seniority": ["cxo", "vp", "director"],
  "person_location_country": ["United States"],
  "person_location_region": ["California", "Texas"],
  "employee_size": ["11-50", "51-200", "201-500"],
  "industries": ["Computer Software", "Information Technology"],
  "email_status": "verified",
  "include_emails": true,
  "include_phones": true
}
```

---

## Output data (typical fields)

Depending on match quality and availability, output can include:

- Full name, first/last name
- Job title and seniority
- Company name, website, size, industry
- Country / region / city
- Work email, additional emails
- Mobile phone (if available)
- LinkedIn URL and profile metadata
- Social/profile enrichment fields

### Example output item

```json
{
  "full_name": "Jane Smith",
  "job_title": "VP of Sales",
  "job_company_name": "Tech Corp",
  "job_company_website": "https://techcorp.com",
  "industry": "Computer Software",
  "location_country": "United States",
  "location_region": "California",
  "work_email": "jane.smith@techcorp.com",
  "mobile_phone": "+1-415-555-0123",
  "linkedin_url": "https://linkedin.com/in/janesmith"
}
```

---

## Best use cases

- B2B sales prospecting
- Outbound campaign list building
- Agency lead delivery
- Recruiter sourcing support
- Market mapping and account research

---

## Performance expectations

Runtime depends on filters, depth, and selected volume.
Typical workflows are optimized for **high-volume extraction up to 50K records per run**.

---

## Rental/subscription version

If you need fixed monthly pricing, use the subscription actor:

- [B2B Leads PRO Subscription (Rental)](https://console.apify.com/actors/JZ1PjtruiQSJeMQ6i/source)

---

## SEO keywords

b2b leads scraper, apollo alternative, linkedin lead scraper, b2b prospecting tool, verified email leads, b2b contact extractor, apify b2b actor, sales leads automation

---

## Open actor

**Run now:** [https://console.apify.com/actors/LurATYM4hkEo78GVj/source](https://console.apify.com/actors/LurATYM4hkEo78GVj/source)
