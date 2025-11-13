# rpissh

This is a BASH script for enabling SSH on my Rasperry Pi cluster. 

It edits the SSH daemon's configuration file, /etc/ssh/sshd_config, by setting "PermitRootLogin yes" - then saving the file, and restarting the sshd service to apply the changes.
