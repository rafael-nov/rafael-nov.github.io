# Archived infrastructure

Terraform and the ephemeral AWS deploy workflow lived here when the site was experimenting with S3 static hosting.

Production hosting is **GitHub Pages** (`rafaelnovais.dev`).

- `terraform/` — bootstrap + deploy modules (S3 website, remote state)
- `workflows/deploy_destroy_aws.yml` — manual GitHub Action that applied Terraform, synced `_site`, then destroyed

Kept for reference only. Not used by CI.
