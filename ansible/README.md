Generally for all the playbooks it is being assumed that passwordless SSH login has been already set on the managed hosts.
If not done then follow the steps to setup passwordless SSH login:
  1. Use the following command to generate a new key:
      cmd# ssh-keygen
  2. Now copy this key to your managed hosts:
      cmd# ssh-copy-id [remote_username]@[server_ip_address]
