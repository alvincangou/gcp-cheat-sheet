# GCP Cloud Architect Cheat Sheet

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A comprehensive, single-page HTML reference guide for Google Cloud Platform (GCP) Cloud Architect certification preparation and daily cloud architecture work. This cheat sheet covers core GCP services, architectural patterns, exam traps, and real-world case studies in a clean, searchable interface.

## Features

- **📚 12 Thematic Sections** — Security, Networking, Compute, Storage, BigQuery, Load Balancing, Messaging, Hybrid/Multi-Cloud, Deployments, Disaster Recovery, FinOps, and Architect Strategy
- **🎯 Exam-Focused Content** — Highlights common certification exam traps, decision matrices, and comparison tables
- **📖 4 Full Case Studies** — Altostrat (Media & GenAI), Cymbal Retail (E-Commerce), EHR Healthcare (SaaS & DR), KnightMotives Automotive (IoT)
- **🔍 Quick-Reference Tables** — Service comparisons, storage classes, deployment strategies, and cost optimization patterns
- **💡 Decision Matrices** — "When to use what" guides for databases, networking, analytics, and more
- **📱 Responsive Design** — Works on desktop, tablet, and mobile devices

## Sections Overview

| Section | Topics Covered |
|---------|---------------|
| **Security & Governance** | DLP API, IAP, IAM, VPC Service Controls, Cloud Armor, Binary Auth, Encryption (CMEK/CSEK/GMEK), Workload Identity |
| **Data Pipelines & Messaging** | Pub/Sub, Cloud Tasks, Datastream, Dataflow, CDC patterns |
| **Networking & Connectivity** | VPC, Shared VPC, VPC Peering, PSC, Direct VPC Egress, Interconnect, NCC, Cloud NAT, Cloud DNS |
| **Load Balancing** | External/Internal App LB (L7), External/Internal Net LB (L4), Global Access |
| **Compute & Modernization** | App Engine, Cloud Run, GCE, Spot VMs, GKE Autopilot, Istio, Eventarc, Migration tools |
| **Hybrid & Multi-Cloud** | Anthos/GKE Enterprise, Cross-Cloud Interconnect, ACM, Connect Gateway, Cloud Service Mesh, GDC |
| **Storage & Data** | GCS classes, Memorystore, Cloud SQL, Spanner, Bigtable, Firestore, Knowledge Catalog, DMS, Transfer Service |
| **BigQuery & Analytics** | Federated queries, Cross-Cloud Lakehouse, Lakehouse for Iceberg, BQ Sharing, BQML, Spanner Columnar Engine |
| **Deployments & Rollouts** | Rolling Update, Canary, Blue/Green, A/B Testing, Shadow deployments |
| **Disaster Recovery** | RTO/RPO, Cold/Warm/Hot DR strategies |
| **Architect Strategy & Traps** | Decision matrix, Ops Suite, common exam pitfalls |
| **FinOps & Cost Optimization** | Budgets & Alerts, Resource Labels, Automated Responses, Quotas |

## Case Studies

The cheat sheet includes four detailed case studies based on the Google Cloud Professional Cloud Architect exam format:

1. **Altostrat Media** — Media & Generative AI modernization with GKE Enterprise, Vertex AI, Dialogflow CX, and GCS lifecycle policies
2. **Cymbal Retail** — E-Commerce & database modernization with Firestore, Apigee, Retail Search, and supply chain security
3. **EHR Healthcare** — SaaS high-availability DR with Dedicated Interconnect, GKE Config Sync, Cloud SQL replicas, and DLP
4. **KnightMotives Automotive** — IoT & global consistency with Bigtable, Pub/Sub, Dataflow, Spanner, and Analytics Hub

Each case study includes key requirements, proposed architectural solutions, and exam traps with detailed explanations.

## Usage

Simply open `index.html` in any modern web browser. No build tools, dependencies, or server required.

The cheat sheet is also hosted live on GitHub Pages:

🔗 **[https://alvincangou.github.io/gcp-cheat-sheet/](https://alvincangou.github.io/gcp-cheat-sheet/)**

```bash
# Clone the repository
git clone https://github.com/alvincangou/gcp-cheat-sheet.git

# Open the cheat sheet locally
open index.html
```

## Customization

The cheat sheet uses CSS custom properties for easy theming:

```css
:root {
    --gcp-blue: #4285F4;
    --gcp-red: #EA4335;
    --gcp-yellow: #FBBC04;
    --gcp-green: #34A853;
    --bg-gray: #f8f9fa;
    --text-dark: #202124;
}
```

Card colors are categorized by service domain (security, networking, compute, storage, etc.) for quick visual scanning.

## Target Audience

- **GCP Cloud Architect exam candidates** preparing for the Professional Cloud Architect certification
- **Cloud architects** designing GCP solutions for enterprise workloads
- **DevOps and platform engineers** working with GCP services daily
- **Technical leads** evaluating GCP for their organization

## Contributing

Contributions are welcome! If you have suggestions for additional content, corrections, or improvements:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new section on ...'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Disclaimer

This cheat sheet is an independent study resource and is not affiliated with, endorsed by, or sponsored by Google LLC. Google Cloud, GCP, and related marks are trademarks of Google LLC. The content is based on publicly available documentation and exam guides, and may not reflect the most current exam content. Always refer to the official [Google Cloud documentation](https://cloud.google.com/docs) and [certification guide](https://cloud.google.com/certification) for the most up-to-date information.