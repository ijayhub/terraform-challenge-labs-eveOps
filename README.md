<img width="400" height="400" alt="Screenshot 2026-03-17 061020" src="https://github.com/user-attachments/assets/2b203ac5-f784-4456-a7ac-2e05552308fd" />

I set up my Terraform and AWS environment on my system. I installed Terraform and confirmed it is working properly.
I also configured AWS CLI and used the command aws sts get-caller-identity to check if my credentials were set correctly. This command returned my AWS account details, which confirmed that my setup was successful.


I ran into an issue when pushing my code because I included the .terraform folder, which had large files. I fixed it by removing it and adding it to my gitignore file so it will not happen again.
