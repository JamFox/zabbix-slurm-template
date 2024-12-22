# Zabbix Slurm template

Simple Zabbix template for checking Slurm node status.

## Usage

1. The template has to be applied to each host individually
   - This means there is no automatic discovery and you can not apply this template to only the Slurm headnode to gather info about each Slurm node.
2. UserParameters need to be added to each monitored host's zabbix-agent configuration: add contents of the file `userparameters_slurm.conf` linux to your `zabbix_agentd.conf` file.
