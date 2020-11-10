How to learn and use this repo.
------------
Install Terraform on Linux:

- Run the below commands.

		sudo yum install -y yum-utils
		sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo
		sudo yum -y install terraform
		terraform -help

- Now that you have terraform installed create a directory to work out of "Do not name it 'terraform'".
		
		
		mkdir yourdirectoryname
		

- Next make sure you have git installed and check the version:
		
		
		sudo yum install git
		git --version
		touch .gitignorefile 
		
-Add any files or logs you do not want to commit to the repo in the git ignore

### Cloning an existing repository.

- Determine your SSH clone url. On Github it's probably something like ***git@github.com:USERNAME/PROJECT.git***. Should be on the project's page somewhere.

		git clone {{the link you just copied}} Project

###Working with terraform basic commands

		terraform  init
		terraform plan
		terraform apply 
		terraform destroy
