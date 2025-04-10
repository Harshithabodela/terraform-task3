
# Terraform + Docker + Custom Nginx Page

## What This Does
- Pulls `nginx:latest` image
- Serves a custom HTML page using a mounted volume
- Exposes the container on http://localhost:8080

## How to Use

```bash
terraform init
terraform apply
# Open http://localhost:8080
terraform destroy
```
<img width="1440" alt="Screenshot 2025-04-10 at 3 26 54 PM" src="https://github.com/user-attachments/assets/6541c614-d00e-4899-9600-9f1709d25264" />
