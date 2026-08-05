# HPC Ansible

Minimal production-ready HPC cluster automation.

## Environment

* Rocky Linux 9

* Bright Cluster Manager

* Slurm

* LDAP / SSSD

* Munge

* Lustre Client

* GPFS Client

* NVIDIA GPU Nodes

---

## Install collections

```bash
ansible-galaxy collection install -r requirements.yml
```

---

## Bootstrap

```bash
ansible-playbook bootstrap.yml
```

---

## Configure Cluster

```bash
ansible-playbook site.yml
```

---

## Inventory

Located in

```
inventories/production/
```
