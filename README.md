### Notes

- Fix probe delay seconds to avoid error installing PostgreSQL by bitnami helm chart.

  https://github.com/bitnami/charts/issues/3925

- Add no_root_squash to avoid permission error of nfs storage.

  https://stackoverflow.com/questions/50854701/kubernetes-permission-denied-for-mounted-nfs-volume


### Reference

- [CSI Driver for NFS](https://github.com/kubernetes-csi/csi-driver-nfs/blob/master/docs/driver-parameters.md)

- [Ansible filter example](https://docs.ansible.com/ansible/latest/dev_guide/developing_plugins.html#developing-filter-plugins)

- [Gitea Actions](https://docs.gitea.com/next/usage/actions/quickstart)

- [MicroK8s Ingress](https://microk8s.io/docs/addon-ingress)


### TODO

- [ ] Create DNS server.

- [ ] Optimize NFS server.
    
    https://manpages.debian.org/unstable/manpages-ja/exports.5.ja.html

- [ ] Specify version.

- [ ] Use variables.
