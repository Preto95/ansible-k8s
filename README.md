This is just my ansible stuff which I created to deploy Kubernetes on my local machines.

## Requirements
OS: Currently only supports Red Hat (further support will be provided in the future)

**inventory**
```
[master]
master01   ansible_user=root   ansible_host=<IP address>

[worker]
worker01   ansible_user=root   ansible_host=<IP address>
worker02   ansible_user=root   ansible_host=<IP address>
```
