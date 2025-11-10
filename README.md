

<a id="readme-top"></a>

<h3 align="center">Emerging Computing Systems (D798)</h3>

  <p align="center">
    Course D798 – Virtual Learning Environment (VLE) System Design  
    <br /><br />
</div>

## About the Project

This project was completed for **WGU’s D798 – Emerging Computing Systems**, focusing on the design and analysis of a **Virtual Learning Environment (VLE)**.
The system builds upon the legacy of early **Learning Management Systems (LMS)** by integrating modern cloud infrastructure, interactive learning tools, and advanced scalability mechanisms to support online education at institutional scale.
The project demonstrates system analysis, architectural planning, cloud design, and sustainability evaluation.

## Course Information

**Course:** D798 – Emerging Computing Systems
**Focus:** Evaluation and design of modern computing systems emphasizing scalability, reliability, security, and sustainability.

### Competencies

**Technological Evolution**
The graduate analyzes how modern computing systems have evolved from earlier technologies.

**System Architecture and Design**
The graduate designs scalable, secure, and maintainable computing systems.

**Cost and Performance Analysis**
The graduate compares infrastructure models for financial, operational, and performance efficiency.

**Security and Sustainability**
The graduate identifies risks, proposes mitigation strategies, and ensures sustainable computing practices.

## Project Overview

### Precursor Technology

The precursor to the VLE was the **Learning Management System (LMS)**, such as early versions of **Blackboard** and **Moodle**, which offered limited functionality and required on-premise servers.
LMS platforms were primarily focused on hosting assignments and lectures with minimal interactivity and lacked real-time collaboration or analytics capabilities.

### System Improvements

The **VLE** modernizes this model through:

* **Cloud-based deployment**, improving scalability and reducing hardware costs.
* **Integrated communication tools** including video conferencing, chat, and mobile access.
* **Automated updates and backups** handled by the cloud service provider.
* **Analytics dashboards** for instructors to track engagement and student performance.

### Cost Comparison

| System Type | Annualized Cost (Mid-Sized Institution) | Infrastructure Model | Staffing Needs          |
| ----------- | --------------------------------------- | -------------------- | ----------------------- |
| Legacy LMS  | $250K–$400K+                            | On-premise servers   | 1–2 full-time IT admins |
| Modern VLE  | $200K–$350K                             | Cloud-based (SaaS)   | 0.5–1 full-time admin   |

Cloud adoption reduces total costs by **20–40%** while improving scalability, reliability, and user accessibility.

### System Architecture

* **Frontend:** Web and mobile clients for students, instructors, and admins.
* **Load Balancer:** Distributes incoming traffic evenly across app servers.
* **Application Servers:** Host course delivery, authentication, and content logic.
* **Database Server:** Stores structured data (user profiles, grades, enrollments).
* **Content Storage:** Cloud object storage for videos, documents, and media.
* **Analytics Service:** Monitors usage, engagement, and performance metrics.
* **Backup Server:** Replicates databases to maintain continuity during failures.

### Operating System and Infrastructure

* **Backend:** Linux (Ubuntu LTS) for stability, security, and cost efficiency.
* **Cloud Provider:** AWS, Azure, or Google Cloud for elasticity and distributed redundancy.
* **Frontend Access:** Browser-based interface compatible with all major operating systems.

### Scalability and Performance

* Horizontal scaling with **auto-scaling groups or Kubernetes containers**.
* Caching layers (Redis, CDN) to reduce latency and offload static content.
* Load balancing and database replication for fault tolerance.
* Proven capability to support up to **1 million concurrent users** through distributed architecture and global load balancing.

### Security and Sustainability

* **Security Measures:** Multi-factor authentication, encryption in transit and at rest, intrusion detection, and log monitoring.
* **Attack Prevention:** MFA enforcement and account activity monitoring prevent credential-based attacks.
* **Attack Response:** Intrusion detection and account lockdown minimize impact during breaches.
* **Sustainability:** Hosted on carbon-neutral data centers; uses autoscaling to minimize idle compute consumption.

## Learning Summary

This course developed advanced understanding of **system design, scalability, and performance optimization** in emerging computing systems.
Through the VLE architecture, I gained hands-on experience in balancing **cost efficiency, reliability, and sustainability** while integrating **secure, cloud-native educational technology**.

## Contact

**Silver Alcid**
[Website](https://silveralcid.com) • [Outlook](mailto:silveralcid@outlook.com)

