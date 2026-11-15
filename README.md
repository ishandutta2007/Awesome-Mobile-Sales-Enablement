# Awesome-Mobile-Sales-Enablement

# Awesome Mobile Sales Enablement

> A curated list of top Mobile Sales Enablement platforms — both SaaS/Hosted commercial solutions and open-source alternatives for equipping sales teams with content, coaching, and CRM access on mobile devices.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Highspot](#highspot)
  - [Seismic](#seismic)
  - [Showpad](#showpad)
  - [Mediafly](#mediafly)
  - [Bigtincan](#bigtincan)
  - [Mindtickle](#mindtickle)
- [Open-Source Software](#-open-source-software)
  - [Sales Playbook](#sales-playbook)
  - [NocoCRM](#nococrm)
  - [Playcall](#playcall)
  - [erxes](#erxes)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Mobile Sales Enablement platforms. These are not open-source but are included as reference points for feature comparison.

### Highspot
**Type:** Sales enablement platform with mobile content access
Highspot provides sales content management, training, and coaching with native mobile apps for iOS and Android. It allows reps to access approved collateral, share content with prospects, and receive coaching from managers while in the field.

### Seismic
**Type:** Enterprise sales enablement with mobile capabilities
Seismic provides a comprehensive sales enablement platform covering content management, buyer engagement, and training. Its mobile app allows reps to access content, present to buyers, and track engagement from their phones.

### Showpad
**Type:** Sales enablement with mobile-first presentation
Showpad specializes in mobile sales presentations, allowing reps to present content, share collateral, and track buyer engagement from tablets and phones. It is positioned for field sales teams wanting a polished mobile experience.

### Mediafly
**Type:** Sales enablement with mobile content delivery
Mediafly provides sales content management, buyer engagement, and value selling tools with mobile access. It is positioned for enterprise sales teams needing to deliver content and calculate ROI from mobile devices.

### Bigtincan
**Type:** Sales enablement with AI and mobile access
Bigtincan provides sales enablement with content management, training, and AI-powered coaching, with mobile apps for field reps. It is positioned for organizations wanting an all-in-one platform with mobile access.

### Mindtickle
**Type:** Sales readiness and training with mobile learning
Mindtickle focuses on sales training and readiness, with mobile-friendly learning modules, role-play practice, and knowledge assessments. It is positioned for organizations wanting to train reps on the go.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Mobile Sales Enablement tools. The open-source ecosystem is **fragmented**, with most projects focused on CRM, playbook automation, or agentic sales assistance rather than dedicated mobile sales enablement suites.

### Sales Playbook
**Stack:** .NET 8 / WPF / SQLite | **License:** MIT
Sales Playbook is a **local-first, single-user sales CRM for solo sellers**, available as a native Windows desktop app with a drag-and-drop deal pipeline, contacts, tasks, and follow-up decision trees [citation:17]. Key characteristics:
- **Offline-first**: everything works without internet; optional Google Calendar + Tasks sync runs in the background
- **Private**: all data lives in a local SQLite file; Google token encrypted with Windows DPAPI
- **Pipeline**: Kanban board with drag-and-drop deal progression
- **Follow-ups**: visual decision-tree ("Did the prospect pick up? → Yes / No") with an interactive runner
- **Dashboard**: live KPIs (open deals, pipeline value, win rate, average cycle), overdue tasks, "Reconnect with" contacts
- **Platform**: Windows 10/11 only, native WPF

**Important limitation:** This is a **Windows desktop application**, not a mobile app. It is included as an open-source sales tool with strong follow-up automation, but it does not provide mobile access.
**Best for:** Solo sellers on Windows wanting a private, offline-first CRM with follow-up decision trees, accepting the desktop-only limitation.

### NocoCRM
**Stack:** Node.js / NocoBase / SQLite/PostgreSQL/MySQL | **License:** Open Source (NocoBase-based)
NocoCRM is an open-source B2B sales CRM built on NocoBase, with **six built-in sales Agents** and email/WhatsApp integration [citation:21]. Key characteristics:
- **Automated follow-ups**: new leads, new opportunities, customer replies, task completion, and daily morning inspections trigger Agents to read context and send next-step suggestions to the inbox
- **Unified timeline**: each person connects their own email (Gmail, Microsoft 365, or any IMAP/SMTP) and the company connects WhatsApp Business; incoming messages auto-match to leads and contacts
- **Smart record creation**: paste an email, chat, or business card, and AI organizes it into a lead or opportunity for your confirmation
- **Company intelligence**: every morning, the intelligence Agent researches news about companies with active opportunities (funding, hiring, leadership changes, risks)
- **Approval assistance**: Approval Agent compares your rules and past cases, calculates discounts and terms, and drafts recommendations
- **Customizable**: write pricing, discount limits, and follow-up cadence into business guidance in plain language

It is **web-based** (NocoBase Admin UI) rather than a native mobile app, but its responsive interface and WhatsApp integration make it accessible on mobile browsers.
**Best for:** B2B sales teams wanting an AI-agent-driven CRM with WhatsApp integration and automated follow-ups, accepting a web-based interface rather than a native app.

### Playcall
**Stack:** TypeScript | **License:** Open Source
Playcall is an **open-source alternative to Gong**, positioned for AI-native GTM teams [citation:18]. It scores every sales call against your playbook and the buyer context your rep was talking to, with no vendor lock-in or $30K/year contracts. It is a **call scoring and coaching tool** rather than a mobile enablement suite, but it addresses the coaching component of sales enablement.
**Best for:** Teams wanting open-source call scoring and coaching without Gong's pricing, accepting a narrower scope than full sales enablement platforms.

### erxes
**Stack:** Node.js / MongoDB / React | **License:** AGPL-3.0 (Community Edition)
erxes is an open-source **Experience Operating System (XOS)** combining marketing, sales, operations, and support in one self-hostable platform, positioned as a HubSpot replacement [citation:7][citation:12]. Key features include:
- **Team Inbox**: real-time client and team communication with in-app messaging, live chat, email, and form
- **Deals**: sales funnels with pipeline control
- **Leads**: capture visitors with customizable landing pages, forms, pop-ups, or embed placements
- **Engage**: convert prospects through email, SMS, messenger, and more
- **CRM**: all-in-one customer relationship management
- **Knowledge base**: help center for brands, products, and services

It provides a **web-based CRM with mobile-responsive interfaces** rather than dedicated native mobile apps. The platform is GraphQL-native with OAuth 2.0 Device Authorization Grant support [citation:12].
**Best for:** Organizations wanting a self-hostable HubSpot alternative with sales, marketing, and support in one platform, accepting a web-based rather than native mobile experience.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Native Mobile App | Sales Enablement Focus | Self-Hosted | Best For |
|----------|---------|-------|-------------------|------------------------|-------------|----------|
| **Highspot** | Proprietary | Cloud | ✅ iOS/Android | ✅ Content + coaching | ❌ | Enterprise sales enablement |
| **Seismic** | Proprietary | Cloud | ✅ Mobile app | ✅ Content + training | ❌ | Enterprise content management |
| **Showpad** | Proprietary | Cloud | ✅ Tablet/phone | ✅ Mobile presentations | ❌ | Field sales presentations |
| **Sales Playbook** | MIT | .NET/WPF/SQLite | ❌ Windows only | ✅ Follow-ups + pipeline | ✅ (Desktop) | Solo sellers on Windows |
| **NocoCRM** | Open Source | NocoBase | (Web-responsive) | ✅ AI Agents + WhatsApp | ✅ | B2B sales with automated follow-ups |
| **Playcall** | Open Source | TypeScript | ❌ | ✅ Call scoring | ✅ | Open-source Gong alternative |
| **erxes** | AGPL-3.0 | Node.js/React | (Web-responsive) | ✅ CRM + sales + support | ✅ | Self-hostable HubSpot alternative |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Mobile Sales Enablement tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

**Note on the open-source ecosystem:** The open-source landscape for **mobile sales enablement** is **extremely limited**. Dedicated mobile sales enablement platforms like Highspot, Seismic, and Showpad are entirely commercial, with no open-source equivalents that replicate their content management, mobile presentation, and coaching capabilities. The available open-source projects address adjacent needs: **Sales Playbook** provides a private, offline-first Windows desktop CRM for solo sellers [citation:17], **NocoCRM** offers an AI-agent-driven B2B CRM with WhatsApp integration accessible via mobile browser [citation:21], **Playcall** addresses call scoring and coaching [citation:18], and **erxes** provides a self-hostable HubSpot alternative with a responsive web interface [citation:7][citation:12]. For any production requirement for dedicated mobile sales enablement with native apps, commercial platforms remain the only viable option.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
