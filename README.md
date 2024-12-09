# ansible-runonceat
run once a Job with ansible
## this install and start the service at on a linux and run once a job at a time
this need 3 variables:
- myhosts from the environment 
- job like "reboot" or so what ever
- starttime like "04:25"(for the next night) or "024:25 012125"(if you want to start a job on the 21.Oct 2025 at night)
tested only with suse15.4 and debian bookworm
