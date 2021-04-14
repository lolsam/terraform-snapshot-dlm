# terraform-snapshot-dlm
Creates a snapshot policy in AWS using Terraform

Snapshot policy performs daily backups of AWS instances tagged with 'Backup:True'. 
Retains backups of 10 days 

Useful for hosts that are static and hard to rebuild. 
