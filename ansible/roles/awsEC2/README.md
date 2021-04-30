Note: 
  1. Update the awsEC2deploy/vars/var.yml and awsEC2deploy/vars/main.yml with the required values.

  2. Make sure to encrypt the awsEC2deploy/vars/main.yml with ansible-vault as it contains critical data. Use following command in the directory awsEC2deploy/vars/ : 
     cmd# ansible-vault encrypt --vault-id user@prompt main.yml
     It'll prompt for setting new password. Provide a strong password and verify.
     
  3. While running the playbook deployEC2.yml use:
     cmd# ansible-playbook --vault-id user@prompt deployEC2.yml
     
