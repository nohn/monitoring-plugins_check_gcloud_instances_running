# monitoring-plugins_check_gcloud_instances_running
Nagios / Icinga check if expected Google Compute Engine instances are running

Example:

    check_gcloud_instances_running "web[0-9]*:1:10;mysql[0-9]*:1:2;temp-[a-z0-9]*:0:0"


