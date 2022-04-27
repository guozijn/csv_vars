# csv_vars

Ansible plugin for parsing data in csv into host vars.

# usage

- Place csv(name: <GROUP_OR_HOST_NAME>.csv) in the csv_vars directory under inventory or playbook.
- Ensure that the hostname in the inventory is the same as the hostname in csv.
- All items in csv will be converted to host variables.
