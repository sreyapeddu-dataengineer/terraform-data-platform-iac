# Terraform Data Platform IaC — Infrastructure as Code for Cloud Data Platforms

Infrastructure as code for cloud data platforms with Terraform — provisioning Databricks, data lake and warehouse resources, and deploying pipelines through GitHub Actions, Jenkins and Azure DevOps CI/CD with Docker and Kubernetes. Resources are defined as reusable modules and promoted across dev, UAT and production with testing gates, reflecting production data platform delivery on AWS, Azure and GCP.

**Tech stack:** Terraform • Docker • Kubernetes • GitHub Actions • Jenkins • Azure DevOps • AWS • Azure • GCP

## Architecture Overview
Reusable Terraform modules (compute, storage, governance) → environment configs (dev / UAT / prod) → CI/CD pipelines deploy Databricks notebooks, Airflow DAGs and infrastructure changes with unit and pipeline testing gates.

## Project Structure
`modules/, environments/ (dev, uat, prod), .github/workflows/, examples/`

## How to Run
Pick an environment under environments/, run `terraform init` and `terraform plan` to preview the data platform resources, then review the example workflows under .github/workflows/.

## Skills Demonstrated
Terraform, Infrastructure as Code, Docker, Kubernetes, GitHub Actions, Jenkins, Azure DevOps, CI/CD, AWS (S3, EMR, Glue, Lambda, DMS, Lake Formation, IAM), Azure, GCP, Unit & Pipeline Testing

## Notes
Portfolio project built on **synthetic data only** — real production engineering patterns from healthcare and financial services data engineering, with no real patient, customer, or market data, and no employer-confidential code or data.

---
*By Sreya Peddu — Senior Data Engineer, Dallas–Fort Worth, TX • peddusreya02@gmail.com • [LinkedIn](https://www.linkedin.com/in/sreyapeddu)*
