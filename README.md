# anbf
Like Ansible but faster, written in Go supporting [most] existing playbooks.

Supports:
- Terraform inventory
- Fucking reconciliation 
- Most of the Ansible core modules [file, apt, copy, shell, sysctl, template]
- Single file to deploy(forget about python dependecy)
- Fast gRPC CnC

Why:

For simple cases where you need something quickly deplyoed without too much mmeory consumption and tons of dependecies.
