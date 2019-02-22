external-ip-\*.yaml files are related, as it's an external service you need to define the endpoints yourself.

If more than one IP address for redundancy can report them in the addresses array. The load balancer will redirect traffic
from kubernetes service to the IP address endpoint(s).

External services don't do any health checking

# Running a mysql singleton

Uses nfs for portability but k8s supports many different persistent volume drive types

nfs-volume.yaml, nfs-volume-claim.yaml
