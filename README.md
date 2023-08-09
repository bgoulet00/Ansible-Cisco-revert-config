# Ansible-Cisco-revert-config

This Ansible play contains the commands required to archive the current configuration and roll back to that config after a predertimed amount of time.  configuration tasks should occur in the location of the debug task placeholder.  keep in mind the number of configuration tasks and the number of hosts you are executing against as the processing delay in the play could run down your revert timer
