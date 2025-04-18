# 🌐 DevOps & Cloud Infrastructure Project

This repository demonstrates the use of modern DevOps tools including **Docker**, **Kubernetes**, **AWS Lambda**, and **Terraform** for containerization, orchestration, cloud deployment, and infrastructure automation.

---

## 🧱 Docker

Docker is used to containerize applications for consistent deployment across environments.

### 🔧 What I Did:
- Completed Docker training and explored official documentation.
- Understood Docker images, containers, and the build lifecycle.
- Built images using the `docker build` command.
- Managed containers using `docker run`, `docker ps`, and other essential commands.

---

## ☸️ Kubernetes

Kubernetes is used for orchestrating containers and managing their deployment, scaling, and operations.

### 🔧 What I Did:
- Learned the fundamentals of Kubernetes: containers, pods, services, deployments, and orchestration.
- Reviewed Kubernetes documentation to understand real-world use cases.
- Practiced Kubernetes CLI tools like `kubectl` and `minikube`.
- Deployed and managed containerized applications on a local Kubernetes cluster.

---

## ☁️ AWS Lambda

AWS Lambda enables serverless computing by running code in response to events without provisioning servers.

### 🔧 Steps Followed:
1. Opened AWS Lambda Console and selected **"Create Function" > "Author from scratch"**.
2. Set the function name, selected runtime (e.g., Python), and configured IAM roles/permissions.
3. Added code using the inline editor or uploaded as a `.zip` package.
4. (Optional) Added triggers like **API Gateway** for HTTP access.
5. Clicked **"Deploy"**, tested the function, and verified the output.

---

## 🛠️ Terraform

Terraform is used to define and provision cloud infrastructure using declarative configuration files.

### 🔧 Prerequisites:
- Terraform installed
- Cloud provider CLI configured (e.g., AWS CLI)

### 🚀 Commands Used:
```bash
terraform init        # Initialize the project
terraform fmt         # Format the code
terraform validate    # Validate configuration
terraform plan        # Preview changes
terraform apply       # Apply changes
terraform destroy     # Tear down infrastructure
