# Hola, soy Diego Feversani 👋
### Cloud & DevOps Engineer | AWS Solutions Architect Professional

[![LinkedIn](https://img.shields.io/badge/LinkedIn-diegofeversani-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/diegofeversani)
[![Email](https://img.shields.io/badge/Email-diego.feversani%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:diego.feversani@gmail.com)
[![Lab Organization](https://img.shields.io/badge/GitHub_Labs-feversani--labs-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/feversani-labs)

---

## Sobre mí

Ingeniero **Cloud & DevOps** con sólida experiencia diseñando, automatizando y operando infraestructura crítica en **AWS** y **Google Cloud Platform (GCP)**. Especializado en **Infrastructure as Code (Terraform)**, orquestación de contenedores con **Amazon EKS / Kubernetes**, flujos de despliegue **GitOps / CI/CD** e ingeniería de plataformas (**IDP / Nullplatform**).

Mi enfoque de ingeniería combina tres pilares en cada arquitectura:
- **Security by Design (SecOps):** Implementación de *IAM Least Privilege*, arquitecturas de red privadas, *Compute Hardening* sin exposición de puertos administrativos (SSH-less) y remediación continua de vulnerabilidades.
- **Eficiencia Operativa y Automatización (IaC & GitOps):** Aprovisionamiento 100% declarativo, reproducible y versionado mediante **Terraform**, integrado en pipelines de **CI/CD** y **ArgoCD**.
- **Optimización de Costos (FinOps):** Diseño de arquitecturas costo-eficientes, migraciones *Cloud-to-Cloud* (GCP a AWS) y entornos efímeros con ciclo de vida controlado (*TTL*).

---

## Certificaciones Oficiales

![AWS SAP](https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Professional-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![AWS DVA](https://img.shields.io/badge/AWS_Certified-Developer_Associate-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![AWS SAA](https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Associate-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)
![AWS CLF](https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white)

---

## Tech Stack & Herramientas

**Cloud Providers & Core Infrastructure**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

**Containers, Orchestration & Platform Engineering**  
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Amazon EKS](https://img.shields.io/badge/Amazon_EKS-FF9900?style=for-the-badge&logo=amazoneks&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nullplatform](https://img.shields.io/badge/IDP-Nullplatform-000000?style=for-the-badge)

**CI/CD, GitOps & Prácticas**  
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![FinOps](https://img.shields.io/badge/FinOps-Cost_Optimization-2E8B57?style=for-the-badge)
![SecOps](https://img.shields.io/badge/SecOps-Cloud_Security-C70039?style=for-the-badge)

---

## Featured Projects — [`feversani-labs`](https://github.com/feversani-labs)

Mis laboratorios de referencia y arquitecturas en **AWS + Terraform** están centralizados en la organización [**`feversani-labs`**](https://github.com/feversani-labs), diseñados bajo principios de producción, seguridad y **FinOps**.

| Proyecto | Patrón de Arquitectura | Stack Principal | Descripción Técnica |
| :--- | :--- | :--- | :--- |
| [**`ephemeral-aws-sandbox`**](https://github.com/feversani-labs/ephemeral-aws-sandbox) | `Base Infrastructure` / `FinOps` | `AWS` `Terraform` `S3` `SSM` | Aprovisionamiento de backend remoto nativo en S3 y *SSM Parameter Store* diseñado para sesiones de laboratorio efímeras (**2h TTL**) y control estricto de costos. |
| [**`my-ec2-aws`**](https://github.com/feversani-labs/my-ec2-aws) | `Compute Hardening` / `SecOps` | `AWS` `EC2` `SSM` `Docker` `IAM` | Instancia EC2 *standalone* endurecida: acceso **SSH-less** vía *SSM Session Manager*, *bootstrap* automatizado de Docker con `user_data` y perfiles **IAM Least Privilege**. |
| [**`aws-high-availability-asg`**](https://github.com/feversani-labs/aws-high-availability-asg) | `High Availability` / `Networking` | `AWS` `VPC` `ALB` `ASG` `Terraform` | Arquitectura *enterprise* **Multi-AZ** resiliente con *Application Load Balancer (ALB)*, *Auto Scaling Group (ASG)* y aislamiento de cargas en subredes privadas. |

<!-- =========================================================================
PLANTILLA PARA AGREGAR NUEVOS REPOSITORIOS A LA TABLA:
Copia la siguiente línea y pégala al final de la tabla superior:

| [**`nombre-del-repo`**](https://github.com/feversani-labs/nombre-del-repo) | `Categoría / Patrón` | `AWS` `Terraform` `Tech` | Descripción concisa del problema que resuelve y patrones aplicados. |
========================================================================= -->

> 💡 **Explora el catálogo completo:** Visita [**@feversani-labs**](https://github.com/feversani-labs) para ver la documentación detallada, diagramas de arquitectura y guías de despliegue de cada laboratorio.

---

## Contacto

- **LinkedIn:** [linkedin.com/in/diegofeversani](https://www.linkedin.com/in/diegofeversani)
- **Email:** [diego.feversani@gmail.com](mailto:diego.feversani@gmail.com)
