k8s_bramble


## Preparing the Raspberry Pi
Kubernetes will do a series of checks and gie a warning about "missing optional cgroups" and "If you know what you are doing..."
/boot/firmware/cmdline.txt
cgroup_enable=cpuset cgroup_memory=1 cgroup_enable=memory