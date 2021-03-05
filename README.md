# To use these scripts
Create Automation Account in Azure
Create a RunAs account
Add modules (browse gallery, import) Az.Accounts, Az.Sql

# Create a secondary database
Create a Runbook to create the replica
Select edit and paste in the contents of createsecondarydb.psl

# Delete a secondary database
Create a Runbook to destroy the replica
Select edit and paste in the contents of destroysecondarydb.psl

# Schedule the runbooks
You can do this in Azure once the books have been created
e.g. Destroy the replica on Friday evening and create on Monday morning