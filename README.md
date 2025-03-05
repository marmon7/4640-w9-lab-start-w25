# 4640-w9-lab-start-w25

To create packer image from project root following the list of commands in sequence:
Packer and Terraform and Ansible must be installed on your machine.

1. ./scripts/import_lab_key "your ssh public key"
2. cd packer
3. packer init .
4. packer build .
5. cd ../terraform
6. terraform init
7. terraform apply
8. (optional) ../scripts/delete_lab_key
