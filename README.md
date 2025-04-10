
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
