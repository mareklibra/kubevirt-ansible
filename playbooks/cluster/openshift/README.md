# OpenShift Cluster Playbook

Create an OpenShift Cluster

### Variables
| Variable        | Default Value           | Description  |
|:------------- |:-------------|:----- |
| openshift_version | 3.7 | OpenShift cluster version. Either 3.7 or 3.9 |
| openshift_ansible_dir | openshift-ansible | Path to openshift-ansible directory |
| openshift_playbook_path | playbooks/byo/config.yml | Path to OpenShift deploy playbook (3.7 -> playbooks/byo/config.yml, 3.9 -> playbooks/deploy_cluster.yml |
