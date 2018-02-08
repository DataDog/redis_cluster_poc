# redis cluster poc

1. copy files to their corresponding locations in /etc/dd-agent/checks.d and /etc/dd-agent/conf.d
2. edit /etc/dd-agent/checks.d/rdcls.py and update CLUSTER_HOST and CLUSTER_PORT global vars with your Redis cluster's info.
3. restart the datadog agent.
