Vagrant xenial VMware Box
========

```sh
vagrant up
```

log
```
$ vagrant up --provider=vmware_fusion
Bringing machine 'default' up with 'vmware_fusion' provider...
==> default: Box 'envimation/ubuntu-xenial' could not be found. Attempting to find and install...
    default: Box Provider: vmware_desktop, vmware_fusion, vmware_workstation
    default: Box Version: >= 0
==> default: Loading metadata for box 'envimation/ubuntu-xenial'
    default: URL: https://vagrantcloud.com/envimation/ubuntu-xenial
==> default: Adding box 'envimation/ubuntu-xenial' (v1.0.3-1501648475) for provider: vmware_desktop
    default: Downloading: https://vagrantcloud.com/envimation/boxes/ubuntu-xenial/versions/1.0.3-1501648475/providers/vmware_desktop.box
```

