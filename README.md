# Tibco EMS Community Edition on RHEL Development Environment

This repository is intended to provide a base Tibco EMS CE installation for a RHEL 7 instance, for use in development and testing.  The instance will come with the AppDynamics Machine agent and Network Visibility agent installed.

# Requirements

1. Rename `ansible/inventory.ini.dist` & `ansible/variables.json.dist` to drop the `.dist` suffix.
2. Have a RHEL 7 instance running, and update `ansible/inventory.ini` and `ansible/variables.json` with your desired configurations.
3. Download Tibco EMS locally, and update `tibco_ems_ce_local_source` in `ansible/variables.json` to point to the Tibco EMS CE zip.
