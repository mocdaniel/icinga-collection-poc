# Icinga2 Ansible collection POC

This is a small poc of the Icinga2 ansible collection. It does the following:

- Install Icinga2 on 2 HA masters, 3 satellites in 2 zones and an agent
- Generates the zones, endpoints, host objects, 3 service groups and basic checks
- Enables the API feature needed for the setup to communicate
- Enables the ido-mysql feature and applies the schema to a preinstalled database

