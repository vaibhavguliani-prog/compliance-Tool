# SEBI COMPLIANCE TOOL 2026
## Quick Implementation & User Guide

---

## 🚀 QUICK START (5 Minutes)

### Step 1: Deploy the Application
1. Copy the file: `SEBI-Compliance-Tool-2026-LATEST.jsx`
2. Deploy to: React application / Vercel / Netlify
3. Open in modern browser (Chrome, Safari, Edge)

### Step 2: Configure Company Data
Edit the `companyData` object:
```javascript
const [companyData, setCompanyData] = useState({
  name: 'Your Company Name',
  cin: 'L99999XX1999XYZ999999',
  bse: 'BSE_CODE',
  nse: 'NSE_CODE',
  isin: 'INE000A01010',
  registrar: 'Registrar Name',
  secretary: 'Company Secretary Name',
});
```

### Step 3: Start Creating Events
1. Click **"Create Event"** in dashboard
2. Select event type (Board Meeting, AGM, EGM, etc.)
3. System auto-generates required documents
4. Download & customize with your specifics

---

## 📋 DOCUMENT-BY-DOCUMENT GUIDE

### 1. BOARD MEETING NOTICE
**Regulation:** SEBI Listing Rules Regulation 17
**Notice Required:** 7 days minimum
**Contents to Customize:**
- Date, time, venue of meeting
- Specific agenda items (3-5 items typical)
- Any director disclosures
- Video conference details (if applicable)

**Compliance Check:**
- ✓ 7 days before meeting
- ✓ All directors notified
- ✓ Confidentiality maintained for material events
- ✓ Quorum specified

---

### 2. REGULATION 30 DISCLOSURE
**Regulation:** SEBI LODR Regulation 30 (Industry Standards Feb 2025)
**CRITICAL TIMELINES:**

| Event Type | Timeline |
|-----------|----------|
| Board decision approval | 30 minutes |
| Internal material event (fraud, regulatory action) | 12 hours |
| External material event (customer loss) | 24 hours |
| AGM/EGM outcomes | 2 working days |

**Materiality Assessment:**
- Impact on revenue >5-10%?
- EBITDA impact >3-5%?
- Strategic significance?
- Market perception impact?

**Always Disclose:**
✓ Board/AGM/EGM proceedings
✓ Major contract wins/losses
✓ M&A announcements
✓ Key personnel changes
✓ Fraud/regulatory action
✓ Dividend announcements

**Defense for Delay:**
If filing late, explain: materiality assessment time, regulatory approval wait, confidentiality agreement, technical issue.

---

### 3. RELATED PARTY TRANSACTION (RPT)
**Regulation:** SEBI Listing Rules Regulation 23 (Fifth Amendment applies)
**NEW Framework (November 2025):**

**Step 1: Determine Materiality Per Schedule XII**
- Transaction value as % of annual turnover
- If <10%: Board approval sufficient
- If 10-25%: Audit Committee + Board required
- If >25%: Shareholder approval mandatory

**Step 2: Get Approvals**
- Audit Committee review & approval (mandatory)
- Board approval
- Shareholder approval (if >25%)

**Step 3: Disclose**
- In Board minutes
- In quarterly compliance certificate
- In Regulation 30 (if material)
- In annual report

**Key Changes (Fifth Amendment):**
- Enhanced AC review for subsidiary transactions >₹1 Cr
- If subsidiary lacks 1-year audited financials, stricter review required
- Revised definitions of "related party"

---

### 4. ANNUAL GENERAL MEETING (AGM)
**Notice Required:** 21 days minimum
**Process:**

1. **Before AGM:**
   - Issue notice (21 days before)
   - Enable e-voting (33% shareholders eligible)
   - Prepare postal ballot (if needed)

2. **At AGM:**
   - Manage voting
   - Record minutes (comprehensive)
   - Director disclosures

3. **After AGM:**
   - File Regulation 30:
     - Basic details within 12 hours
     - Complete voting results within 2 working days
   - Prepare minutes (within 30 days)
   - BRSR disclosure (if top 1000 company)

**Integrated Filing (Mandatory since April 2025):**
- Submit results in PDF (within timeline)
- Submit XBRL Integrated Filing-Financial (same day)
- No separate utilities needed

---

### 5. BRSR CORE ESG REPORTING
**Applicable:** Top 1000 companies by market cap

**For FY 2025-26:**
- Top 150: Mandatory with 3rd-party assessment
- Top 151-500: Mandatory, assessment optional
- All top 1000: BRSR Core mandatory

**49 KPIs to Report:**
- 18 Environmental (energy, emissions, water, waste)
- 18 Social (gender, safety, health, training, community)
- 13 Governance (board, ethics, CSR, tax)

**Data Points to Collect:**
✓ Energy consumption (GJ) - renewable & non-renewable
✓ GHG emissions (Scope 1, 2, 3 in tCO2e)
✓ Water usage (ML)
✓ Waste generated & diverted
✓ Gender diversity (workforce % & board %)
✓ Safety metrics (accidents, LTIFR)
✓ Training hours per employee
✓ CSR spend (₹ Crores)
✓ Board composition (independence %)

**Timeline:**
- Data collection: Q4 (Jan-March)
- Report preparation: April-May
- 3rd-party assurance: May-June
- Filing with annual report: June 30 (for Mar 31 FY)

---

## 🎯 MONTHLY COMPLIANCE CALENDAR

### Month 1 (Jan)
- ☑ Materiality Policy Review
- ☑ Internal SOP for material event disclosure
- ☑ Regulation 30 training for officers
- ☑ RPT approval process updated (Fifth Amendment)

### Month 2 (Feb)
- ☑ Q3 Results filing (integrated XBRL system)
- ☑ Related party transactions reviewed & approved
- ☑ Board meetings scheduled (7-day notice sent)
- ☑ BRSR data collection ongoing

### Month 3 (Mar)
- ☑ Board meeting minutes prepared
- ☑ Regulation 30 filings reviewed for Q3
- ☑ BRSR data validation & assurance initiated
- ☑ Annual report drafting commenced

### Month 4-5 (Apr-May)
- ☑ AGM notice issued (21 days notice)
- ☑ Annual report finalized with BRSR
- ☑ Proxy forms & e-voting enabled
- ☑ BRSR assurance completed (if required)

### Month 6 (Jun)
- ☑ AGM conducted
- ☑ Minutes prepared & filed
- ☑ Regulation 30: AGM outcome filing (12 hr + 2 day)
- ☑ Annual report & BRSR filed
- ☑ Dividend announcement (if approved)

### Month 7-12 (Jul-Dec)
- ☑ Q1, Q2 results filing (integrated XBRL)
- ☑ H1 financials + governance disclosures
- ☑ Board meetings (7-day notice)
- ☑ RPT quarterly summary filed
- ☑ Material events disclosed (Reg 30)

---

## ⚠️ CRITICAL COMPLIANCE PITFALLS TO AVOID

### 1. Regulation 30 Timeline Breach
❌ **WRONG:** "I'll file the disclosure tomorrow"
✅ **RIGHT:** 30 min (board decision) / 12 hrs (internal) / 24 hrs (external) / 2 days (AGM)

**Impact:** SEBI enforcement, penalties ₹1-50 Lakh, repeated breaches attract show cause.

---

### 2. RPT Approval Sequence Error
❌ **WRONG:** "Let me get Audit Committee approval after Board approval"
✅ **RIGHT:** Audit Committee → Board → (Shareholders if >25%)

**Impact:** RPT deemed unapproved, potential director liability.

---

### 3. Missing BRSR Disclosures
❌ **WRONG:** "We'll skip BRSR as we're not in top 150"
✅ **RIGHT:** Top 1000 companies = BRSR Core mandatory

**Impact:** Delisting risk, SEBI enforcement, reputational damage.

---

### 4. Materiality Policy Undefined
❌ **WRONG:** "Materiality is what I think is material"
✅ **RIGHT:** Document thresholds (5% revenue, 3% EBITDA, etc.)

**Impact:** Inconsistent disclosures, Regulation 30 violations, regulatory action.

---

### 5. Integrated Filing Non-Compliance
❌ **WRONG:** "PDF submission is sufficient, XBRL optional"
✅ **RIGHT:** PDF + XBRL mandatory since April 1, 2025

**Impact:** Exchange rejection, compliance failure, non-timely filing record.

---

## 🔍 QUARTERLY COMPLIANCE CHECKLIST

### Q1 (April-June)
```
☐ AGM conducted & minutes filed within 30 days
☐ Regulation 30: AGM outcome filed (12 hr + 2 day)
☐ Q1 results filed in PDF + XBRL (within 30 mins / 3 hrs)
☐ Related party transactions reviewed
☐ Board composition/independence verified
☐ BRSR data collection initiated
```

### Q2 (July-September)
```
☐ Q2 results filed in PDF + XBRL
☐ Dividend (if any) announced & Reg 30 filed
☐ Board meetings noticed (7 days minimum)
☐ Material events disclosed per Regulation 30
☐ RPT summary filed
☐ BRSR data validation ongoing
```

### Q3 (October-December)
```
☐ Q3 results filed in PDF + XBRL
☐ Board meetings conducted
☐ Related party transactions approved
☐ Regulation 30 filings current
☐ BRSR data consolidation completed
```

### Q4 (January-March)
```
☐ Q4/FY results filed in PDF + XBRL
☐ AGM notice prepared (21-day notice)
☐ Annual report drafted with BRSR
☐ 3rd-party BRSR assurance completed (if required)
☐ Directors' report finalized
☐ Audit report & CARO compliance verified
```

---

## 📞 REGULATORY CONTACTS

**For Clarifications on Regulation 30:**
- SEBI: www.sebi.gov.in > Legal > LODR Master Circular (Jan 30, 2026)
- NSE: www.nseindia.com > Circulars (NSE/CML/2025/XX)
- BSE: www.bseindia.com > Notices & Circulars

**For BRSR Queries:**
- SEBI ESG: www.sebi.gov.in > BRSR Core Framework
- Industry Associations: FICCI, ASSOCHAM, CII

**For Technical (XBRL Filing):**
- NSE: neaps.nseindia.com > Support
- BSE: investor@bseindia.com

---

## 🎓 TRAINING SCHEDULE FOR COMPANY

**Quarterly Board Training:**
- Regulation 30 materiality assessment (30 min session)
- RPT approval process updates
- Governance compliance updates
- Data protection & cybersecurity disclosures

**Annual Training:**
- Full SEBI LODR framework
- BRSR ESG reporting requirements
- Stock exchange filing procedures
- Enforcement trends & penalties

---

## 📊 SAMPLE MATERIALITY POLICY

**Company:** [Your Company Name]
**Annual Turnover:** ₹500 Crores
**EBITDA:** ₹100 Crores

### Quantitative Thresholds:
- Revenue Impact: >₹25 Cr (5% turnover) = Material
- EBITDA Impact: >₹3 Cr (3% EBITDA) = Material
- Balance Sheet Impact: >₹50 Cr (10% assets) = Material
- RPT Value: >₹50 Cr (10% turnover) = Material

### Qualitative Factors:
- Strategic importance to business model
- Change in corporate structure/control
- Regulatory implications
- Key personnel changes
- Reputation/market impact

### Disclosure Timeline:
- Board decisions: 30 minutes
- Internal events: 12 hours
- External events: 24 hours
- Meeting outcomes: 2 working days

**Approved By:** Board of Directors
**Effective Date:** [DATE]
**Review Frequency:** Annually or on SEBI guidance

---

## ✅ FINAL SIGN-OFF CHECKLIST

Before going live with SEBI Compliance Tool:

- ☑ Company data configured correctly (CIN, ISIN, codes)
- ☑ Materiality Policy documented & approved
- ☑ Internal SOP for Regulation 30 disclosure created
- ☑ Board & management trained on timelines
- ☑ Audit Committee charter updated (Fifth Amendment)
- ☑ RPT approval process per Schedule XII framework
- ☑ BRSR data governance structure established
- ☑ XBRL integrated filing system tested
- ☑ Regulation 30 monitoring dashboard operational
- ☑ Monthly compliance calendar implemented

**Status:** _____ READY TO DEPLOY
**Date:** ___________
**CS Sign-off:** ______________

---

*Document Last Updated: January 30, 2026*
*Next Review: Upon SEBI circular issuance*
