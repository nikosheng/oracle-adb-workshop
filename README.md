# ADB Workshop In A Day

> In this **FREE half-day workshop**, participants will delve into the world of **Oracle Autonomous Database (ADB)**. Leveraging machine learning and AI, the Autonomous Database delivers a self-driving, self-securing, and self-repairing database service that can instantly scale to meet the demands of mission-critical applications.
> 
> 
> During the workshop, you’ll explore the following key areas:
> 
> 1. **Comprehensive Understanding**: Gain insights into the Oracle Autonomous Database, spanning from **L100** (introductory) to **L300** (advanced) levels. Understand its ecosystem and discover multiple deployment options tailored to your enterprise needs in both public and hybrid cloud scenarios.
> 2. **Migration Strategies**: Learn how to seamlessly migrate your Oracle databases from other cloud vendors or on-premise environments to the Autonomous Database.
> 3. **Management and Security**: Acquire essential skills in managing the Autonomous Database. Explore the enterprise-graded security features natively supported within the Autonomous Database environment.
> 
> Whether you’re a beginner or an experienced professional, this workshop promises an enriching experience. Get ready to unlock the potential of Oracle Autonomous Database!
> 

### Audience 🧑‍🎓

---

- Database Administrator
- System Administrator
- Software Engineer
- Security Specialist

### Workshop Agenda 🧑🏼‍🏫

---

1️⃣ **Part 1 (1.5 Hours)**

- ADB Overview
    - Intro to ATP/ADW/AJD and Value proposition
    - ADB Deployment Options - Serverless , Dedicated and C@C
    - Innovation path of ADB
        - Automation capabilities in Oracle database
            - Automatic Indexing
            - Automatic Partitioning
            - Optimizer Statistics
        - Lakehouse Integration
            - OML
            - OCI Data Lake

2️⃣ **Part 2 (1 Hours)**

- Migration Strategies
    - Assessment
        - CPAT (Cloud Premigration Assessment Tool)
        - Choose the Right Migration Strategy
            - [Cloud Migration Advisor](https://www.oracle.com/webfolder/s/assets/webtool/cloud-migration-advisor/index.html)
    - Oracle Database Migration
        - Offline Migration
            - Datapump
            - mv2adb
            - DBMS_CLOUD APIs
            - External Table Loading
        - Online Migration - minimal downtime
            - Zero Down Time Migration Tool (ZDM)
            - OCI DMS
            - GoldenGate
    - Non-Oracle Database Migration (Optional)
        - SQL Developer
            - MySQL/PostgreSQL
            - Amazon Redshift
            - MSSQL

3️⃣ **Part 3 (2 Hours)**

- Management & Security
    - Resource Management
        - Auto Scaling
        - Concurrency and Priorities on ADB
            - Service Concurrency
            - Manage CPU/IO Shares on ADB
            - Oracle Scheduler
            - Runway SQL Statements
        - Event and Alarm Notification
        - Performance Hub
    - High Availability and Disaster Recovery
        - HADR Strategy
            - RTO & RPO Options
        - Autonomous Data Guard
            - Local Region AuDG
            - Cross Region AuDG
                - Snapshot Standby
            - Failover & Switchover
        - Refreshable Clone
        - Backup & Restore
            - Automatic Backup
            - Long Term Backup
            - Point-in-time Restore
    - Database Actions
        - Data Load
        - Data Transformation
        - Data Share
        - Oracle Machine Learning
    - Data Security
        - Data Encryption
            - Encryption of Data at Rest
                - Transparent Data Encryption
            - Encryption of Data in Transit
                - TCPS database connection - TLS & mTLS
        - Access Control
            - Network Access Control
                - Private Endpoint and Network Security Group
                - Public Endpoint and Access Control List
            - Database User Access Control
        - Data Safe
            - Security Assessment
            - Sensitive Data Discovery
            - Data Masking
            - Activity Auditing
        - Database Vault

### Autonomous Database Hands-on Preparation 💻

---

- [Always Free ADB](https://docs.oracle.com/en/cloud/paas/autonomous-database/serverless/adbsb/autonomous-always-free.html#GUID-03F9F3E8-8A98-4792-AB9C-F0BACF02DC3E)
- [Autonomous Database Free Container Image](https://github.com/oracle/adb-free)

### Livelabs 🙌

---

🔗 [Autonomous Database 15 Minute Quick Start](https://apexapps.oracle.com/pls/apex/r/dbpm/livelabs/view-workshop?wid=928&clear=RR,180&session=114199137894150)

🔗 [Manage and Monitor Autonomous Database](https://apexapps.oracle.com/pls/apex/r/dbpm/livelabs/view-workshop?wid=553&clear=RR,180&session=114199137894150)

🔗 [Data Studio - Self service tools for everyone using Oracle Autonomous Database](https://apexapps.oracle.com/pls/apex/r/dbpm/livelabs/view-workshop?wid=789&clear=RR,180&session=114199137894150)

### Reference Architecture 📁

---

🔗 **[Configure a DR Solution with an Oracle Autonomous Database](https://docs.oracle.com/en/solutions/adb-refreshable-clones-dr/index.html#GUID-D31D13F9-F2C3-4BAB-B652-DAB5F5C25A4B)**

🔗 [Fast-Ingest with high-frequency inserts in IoT](https://docs.oracle.com/en/database/oracle/oracle-database/21/tgdba/tuning-system-global-area.html#GUID-CFADC9EA-2E2F-4EBB-BA2C-3663291DCC25)
