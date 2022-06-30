### Added

- New playbook `playbooks/kubeconfig.yml` to manage kubeconfigs. It can either move the cluster admin kubeconfig that kubespray produces or create an OIDC kubeconfig. This comes with several new group vars.
- New playbook `playbooks/cluster_admin_rbac.yml` to add cluster admin RBAC for OIDC users. This comes with several new group vars.

### Changed

- Apply command uses the new ansible playbooks to manage kubeconfigs and OIDC clusteradmin RBAC.
