# SCC test manifest

`dev/test-scc.yaml` creates a privileged pod with host PID access and a mount of the host root filesystem. Use it only in an isolated test cluster, and delete the pod after the test. Do not apply it to a shared or production cluster.
