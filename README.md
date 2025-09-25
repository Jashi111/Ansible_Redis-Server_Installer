# 📦 Redis Cluster Setup Using Ansible

This Ansible playbook automates the installation, configuration, and clustering of Redis on multiple nodes. Designed for scalable and production-ready deployments, it supports optional cleanup of existing Redis installations, and sets up a Redis Cluster with proper configuration and user privileges.

---

## 📌 Author

**jashi111**

---

## 📦 Features

- Idempotent setup: Safe to run multiple times without breaking the system
- Clean-up tasks: Optionally removes previous Redis installations, configs, and logs
- Installs Redis from the official APT repositories
- Configures Redis Cluster settings in /etc/redis/
- Cluster-aware configuration (e.g. cluster-enabled, cluster-config-file)
- Optional custom user and authentication setup
---

