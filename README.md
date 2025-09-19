# City of Owosso Community Engagement Platform RFP
## IBM Cloud Partner Architecture Analysis

### 🎯 Project Overview
Strategic analysis of four IBM Business Partners for responding to the City of Owosso's Community Engagement Platform RFP. This repository contains architectural diagrams, requirements matrices, and partner evaluations for a cloud-based civic engagement solution.

**RFP Details:**
- **Client:** City of Owosso, Michigan (~14,500 residents)
- **Issue Date:** September 11, 2025
- **Due Date:** October 7, 2025 @ 3:00 PM EST
- **Platform:** IBM Cloud (OpenShift, watsonx.ai, API Connect, Db2)

### 📁 Repository Contents

#### Core Documents
- `index.html` - Main portal page with partner overview and navigation
- `Executive Briefing City of Owosso Community Engagement Platform RFP.docx` - Strategic analysis and key insights
- `Owosso Community Engagement Platform RFP.pdf` - Official RFP document

#### Partner Architecture Diagrams
- `perficient-civic-engagement.html` - Perficient architecture (Prime Application + Systems Integrator)
- `glasshouse-civic-platform.html` - GlassHouse Systems architecture (Infrastructure Security Anchor)
- `accelbi-civic-platform.html` - AccelBI architecture (Data/AI-Forward Application)
- `lantrasoft-civic-platform.html` - Lantrasoft architecture (Cost-Effective Custom + ISV Fallback)

#### Analysis Matrix
- `owosso_rfp_requirements_owner_matrix_ibm_bp.html` - Comprehensive requirements ownership matrix comparing all partners

### 🚀 Quick Start

#### View the Analysis Portal
1. Visit: [https://sm911.github.io/owosso-rfp/](https://sm911.github.io/owosso-rfp/)
2. Or clone locally: `git clone https://github.com/sm911/owosso-rfp.git`
3. Open `index.html` in your browser

### 🏗️ Architecture Patterns

#### 1. **Perficient** - Prime Application + Systems Integrator
- **Strengths:** Front-end expertise, WCAG compliance, municipal experience
- **Key Tech:** OpenShift ROKS, API Connect, watsonx.ai, Laserfiche integration
- **Pattern:** Full application ownership with optional ISV integration

#### 2. **GlassHouse Systems** - Infrastructure Security Anchor
- **Strengths:** 24×7 SecOps, 99.9% SLA, compliance automation
- **Key Tech:** Security & Compliance Center, Key Protect, Multi-zone architecture
- **Pattern:** Security-first with curated ISV (Granicus/PublicInput)

#### 3. **AccelBI** - Data/AI-Forward Application
- **Strengths:** Advanced analytics, sentiment analysis, demographic insights
- **Key Tech:** watsonx.ai Studio, Db2 Warehouse, Knowledge Catalog
- **Pattern:** Analytics depth with curated ISV (Zencity)

#### 4. **Lantrasoft** - Cost-Effective Custom + ISV Fallback
- **Strengths:** Midwest proximity, flexible runtime, fast iterations
- **Key Tech:** Kubernetes/OpenShift options, Event Notifications
- **Pattern:** Custom development with ISV fallback option

### 📊 Key RFP Requirements

#### Mandatory Features
- ✅ Online surveys with customizable questions
- ✅ Digital polling/voting tools
- ✅ AI-powered data analysis
- ✅ ADA/WCAG 2.1 AA compliance
- ✅ Multilingual support
- ✅ Real-time analytics dashboards
- ✅ Demographic tracking
- ✅ Sentiment analysis
- ✅ Public-facing dashboards
- ✅ Data encryption (transit & rest)
- ✅ 99.9% uptime SLA

#### Desired Features
- 📍 Interactive mapping for geographic feedback
- 📱 SMS/text message input capability
- 📊 Census benchmark comparisons
- 📧 Email notification system
- 🔐 Data anonymization tools

### 🛠️ Technology Stack

#### IBM Cloud Services (Common Across Partners)
- **Runtime:** OpenShift (ROKS) / Kubernetes Service
- **API Management:** API Connect
- **AI/ML:** watsonx.ai, watsonx.governance
- **Databases:** Db2, PostgreSQL, Db2 Warehouse
- **Messaging:** Event Notifications, Event Streams (Kafka)
- **Security:** Key Protect, Security & Compliance Center
- **Identity:** IBM Verify / App ID
- **Monitoring:** Cloud Monitoring, Activity Tracker, Flow Logs

#### Integration Points
- Laserfiche (Document Management)
- City Website (CMS)
- Social Media Platforms
- Video Streaming Services

### 📈 Evaluation Criteria

1. **Responsiveness to RFP** - Clarity, completeness, compliance
2. **Ability to Perform** - Municipal experience, Michigan presence
3. **References** - Service quality, support history
4. **Cost Proposal** - 3-year total cost of ownership

### 🔍 Interactive Features

Each architecture diagram includes:
- Visual flow differentiation (8 distinct flow types)
- Interactive zoom controls (25%, 50%, 75%, 100%)
- Color-coded components by provider
- Detailed flow labels and descriptions
- Legend for flow type identification

### 📝 Notes

- All architectures leverage IBM Cloud's enterprise platform
- External integrations flow through API Connect gateway
- Encryption uses CMKs (Key Protect/Hyper Protect)
- Multi-zone deployment ensures 99.9% availability
- Each partner brings unique strengths while maintaining core IBM Cloud foundation

### 📞 Contact Information

**RFP Coordinator:**
- Nathan Henne, City Manager
- City of Owosso
- 301 West Main Street, Owosso, MI 48867
- Email: Nathan.henne@ci.owosso.mi.us
- Phone: (989) 725-0568

### ⚖️ License

This analysis is prepared for IBM Cloud partner evaluation purposes. All RFP materials are property of the City of Owosso, Michigan.

---

*Prepared by: Jim Venuto of IBM Cloud, Public Market*  
*Last Updated: September 2025*
