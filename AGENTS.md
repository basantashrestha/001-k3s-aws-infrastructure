k3s-aws-infrastructure/
├── AGENTS.md
├── terraform/
│   ├── modules/
│   │   ├── networking/
│   │   └── ec2/
│   ├── environments/
│   │   └── dev/
│   │       ├── main.tf
│   │       ├── variables.tf
│   │       ├── outputs.tf
│   │       └── terraform.tfvars.example
│   └── providers.tf
├── ansible/
│   ├── inventory/
│   ├── playbooks/
│   │   ├── install-k3s.yml
│   │   └── install-argocd.yml
│   └── roles/
├── scripts/
├── docs/
└── README.md

