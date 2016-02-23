# splunk-vagrant-ansible-collections

This repository is a personal collection of configuration files and scripts that make an heavy use of Vagrant and Ansible to create on the fly full Splunk environments for testing and development purposes.

These repositories will use:

- Virtualbox as the virtualization layer (but you could use other provider), See:https://www.virtualbox.org
- Vagrant, an incredibly powerful tool, See: https://www.vagrantup.com

Currently, following configuration scenario are available:

## create_monosite_cluster

This scenario uses Vagrant and Ansible to create on a fly a mono-site Splunk cluster.
Instructions are available in the [README](https://github.com/guilhemmarchand/splunk-vagrant-ansible-collections/tree/master/create_monosite-cluster) of the repository

## deploy_nmon_cluster_monosite

This scenario will automatically deploy the Nmon Performance application (See https://splunkbase.splunk.com/app/1753 or https://github.com/guilhemmarchand/nmon-for-splunk) for the mono-site cluster configuration.
Instructions are available in the [README](https://github.com/guilhemmarchand/splunk-vagrant-ansible-collections/tree/master/deploy_nmon_cluster_monosite) of the repository

