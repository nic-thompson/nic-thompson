<!-- HEADER BANNER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0052CC&height=200&section=header&text=Nicolas%20Thompson&fontSize=42&fontColor=ffffff&desc=Backend%20Engineer%20%7C%20AWS-Native%20Data%20Infrastructure&descSize=18&descAlignY=75" width="100%" alt="Header Banner" />
</p>

<!-- QUOTE & INTRO -->
<p align="center">
  <i>"I like systems that fail loudly and code that explains itself."</i>
</p>

<p align="center">
  <a href="https://nicolas-thompson.com"><img src="https://img.shields.io/badge/Website-nicolas--thompson.com-0052CC?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://linkedin.com/in/nicolas-giles-thompson"><img src="https://img.shields.io/badge/LinkedIn-nicolas--giles--thompson-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:hello@nicolas-thompson.com"><img src="https://img.shields.io/badge/Email-hello%40nicolas--thompson.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

### **Architecture Focus**

```mermaid
flowchart LR
    A[Raw Stream Telemetry] --> B[Schema-Versioned Contracts]
    B --> C[Async Processing Pipeline]
    C --> D[(DynamoDB Feature Store)]
    C --> E[(S3 / Parquet Export)]
