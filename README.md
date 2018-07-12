# Collection of Simple Cloudify Blueprints

## Overview

This contains cloudify blueprints

## OpenStack

* To check a working manager
```
cfy install https://github.com/rajalokan/cloudify-blueprints/archive/master.zip --blueprint-filename simplest_blueprint.yaml --blueprint-id simplest_blueprint
```

* To install a very simple VM
```
cfy install https://github.com/rajalokan/cloudify-blueprints/archive/master.zip --blueprint-filename openstack-vm-blueprint.yaml --blueprint-id simple_openstack_vm -i private_network_name=<my_network>
```
