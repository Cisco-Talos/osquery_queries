# Cisco Talos Osquery queries

These queries are distributed in the hope that they will be useful, but **WITHOUT ANY WARRANTY**.

**NOTE:** This repository is still under construction.

### About this Repository

This repository contains Osquery packs used to query for malware and threat related IoCs.

This project's goal is to provide Osquery packs that reflect the current threat landscape.

### Repository Layout

All packs will reside under the <i>packs</i> directory. Each pack will be an appropriately named .conf file indicating its platform and type of queries contained.

**Current packs available:**
  - win_malware.conf

### Using This Repository

It is recommended to run these queries/configurations in an isolated or lab environment before deploying.

Each query defaults to being run every 24 hours (86400). This value can be modified by changing the "interval" value under each query.
