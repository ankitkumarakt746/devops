To enable a non-privileged user to become root without a password is to install a file with following directives:

## Password-less sudo for non privileged users
someuser ALL=(ALL) NOPASSWD:ALL

into the directory /etc/sudoers.d
