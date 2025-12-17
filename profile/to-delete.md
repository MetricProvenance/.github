# Welcome to Authentic Intelligence Labs 🇳🇱

### The Home of the Open Governance Standard (OGS)

**Authentic Intelligence Labs** is an open-source initiative dedicated to solving the "Definition Drift" problem in modern data stacks. We build vendor-neutral protocols that decouple business logic from BI tools, enabling a true **Headless Data Governance** architecture.

---

## 🚀 Our Mission

In the modern data stack, business logic is often fragmented. A "Gross Margin" calculation in **dbt** might conflict with the DAX formula in **Power BI**, which differs again from **Tableau**.

**We believe that:**
1.  **Definitions should be defined once**, not reinvented in every tool.
2.  **Governance should be "Headless"**—managed as code (JSON/YAML) and synced downstream.
3.  **Standards should be open**, not locked into a proprietary catalog.

---

## 📂 Featured Project: Headless Data Governance

Our flagship project provides the schemas and validators needed to implement the **Open Governance Standard**.

### [headless-data-governance](https://github.com/Authentic-Intelligence-Labs/headless-data-governance)
*The vendor-neutral JSON standard for Headless Data Governance.*

**What it does:**
- Acts as the "API" for your business metrics.
- Defines a single source of truth for KPIs, Data Quality rules, and Lineage.
- Syncs definitions automatically to dbt, Power BI, Tableau, and Data Catalogs.

**Core Components:**
- `standard_metrics.json`: The "Golden Record" for KPIs.
- `standard_dq_dimensions.json`: 60+ industry-standard data quality dimensions.
- `standard_data_rules.json`: Technical validation rules (Regex, null checks).
- `root_cause_factors.json`: Standardized taxonomy for data incidents.

[**Explore the Repository →**](https://github.com/Authentic-Intelligence-Labs/headless-data-governance)

---

## 🛠️ The "Art of the Possible"

We don't just define standards; we demonstrate how they work in the real world.

- **Write Once, Sync Everywhere:** See how a single JSON change triggers updates across your entire stack.
- **CI/CD for Governance:** Validate your metrics with Python-based validators before they break your dashboards.

🌐 **Live Demo:** [metricprovenance.com](https://metricprovenance.com)

---

## 🤝 Get Involved

We are an open community and welcome contributions from Data Engineers, Analytics Engineers, and Governance Leads.

- **🐛 Found a bug?** Open an issue in our [main repository](https://github.com/Authentic-Intelligence-Labs/headless-data-governance/issues).
- **💡 Have an idea?** Submit a Pull Request to expand the OGS schema.
- **💬 Discuss:** Connect with us to shape the future of Headless BI [Discussions](https://github.com/Authentic-Intelligence-Labs/headless-data-governance/discussions).

---

## 🧩 Why now, why this?
![Infographic](https://res.cloudinary.com/dcfadz2uh/image/upload/v1764220237/infographic-bdm-potrait-reduced_flwuu3.jpg)

---

<div align="center">

© 2025 Authentic Intelligence Labs • Licensed under Apache 2.0
<br>
<a href="https://metricprovenance.com/">Website</a> • <a href="https://github.com/Authentic-Intelligence-Labs">GitHub</a>

</div>
