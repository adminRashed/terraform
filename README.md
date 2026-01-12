terraform --version
brew tap hashicorp/tap
brew install hashicorp/tap/terraform
vim rashed.tf
cat rashed.tf 
resource local_file my_file {
	filename = "terra.txt"
	content = "This is 1st terra file"
}

terraform iit
terraform validate
terraform plan
tarraform apply
