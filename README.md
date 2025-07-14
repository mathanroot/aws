## Usage


# 1. Clone repo
git clone https://github.com/mathanroot/aws.git
cd <repo>

# 2. Initialize Terraform
terraform init

# 3. Review execution plan
terraform plan -out=tfplan

# 4. Apply (create resources)
terraform apply tfplan
