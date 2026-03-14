Non-terminated Pods:          (4 in total)
  Namespace                   Name                               CPU Requests  CPU Limits  Memory Requests  Memory Limits  Age
  ---------                   ----                               ------------  ----------  ---------------  -------------  ---
  default                     frontend-778ccbd84-rn7md           0 (0%)        0 (0%)      0 (0%)           0 (0%)         77s
  default                     redis-follower-6c5dfb8f9d-kf4qg    0 (0%)        0 (0%)      0 (0%)           0 (0%)         53s
  kube-system                 coredns-6b4688786f-js7d2           100m (10%)    0 (0%)      70Mi (3%)        170Mi (8%)     42m
  kube-system                 svclb-traefik-f6c3940d-gd82d       0 (0%)        0 (0%)      0 (0%)           0 (0%)         42m
Allocated resources:
  (Total limits may be over 100 percent, i.e., overcommitted.)
  Resource           Requests    Limits
  --------           --------    ------
  cpu                100m (10%)  0 (0%)
  memory             70Mi (3%)   170Mi (8%)
  ephemeral-storage  0 (0%)      0 (0%)
  hugepages-1Gi      0 (0%)      0 (0%)
  hugepages-2Mi      0 (0%)      0 (0%)

  Namespace                   Name                               CPU Requests  CPU Limits  Memory Requests  Memory Limits  Age
  ---------                   ----                               ------------  ----------  ---------------  -------------  ---
  default                     frontend-88dcd974c-7dhz2           100m (10%)    0 (0%)      100Mi (5%)       0 (0%)         33s
  default                     redis-follower-6958c9f49c-b7ptj    100m (10%)    0 (0%)      100Mi (5%)       0 (0%)         27s
  default                     redis-follower-6c5dfb8f9d-kf4qg    0 (0%)        0 (0%)      0 (0%)           0 (0%)         2m2s
  kube-system                 coredns-6b4688786f-js7d2           100m (10%)    0 (0%)      70Mi (3%)        170Mi (8%)     44m
  kube-system                 svclb-traefik-f6c3940d-gd82d       0 (0%)        0 (0%)      0 (0%)           0 (0%)         43m
Allocated resources:
  (Total limits may be over 100 percent, i.e., overcommitted.)
  Resource           Requests     Limits
  --------           --------     ------
  cpu                300m (30%)   0 (0%)
  memory             270Mi (13%)  170Mi (8%)
  ephemeral-storage  0 (0%)       0 (0%)
  hugepages-1Gi      0 (0%)       0 (0%)
  hugepages-2Mi      0 (0%)       0 (0%)
Events:
  Type    Reason                   Age   From                   Message
  ----    ------                   ----  ----                   -------
  Normal  CertificateExpirationOK  44m   k3s-cert-monitor       Node and Certificate Authority certificates managed by k3s are OK
  Normal  Synced                   44m   cloud-node-controller  Node synced successfully
  Normal  RegisteredNode           44m   node-controller        Node node-01 event: Registered Node node-01 in Controller

  =============================================================================================================

  Non-terminated Pods:          (6 in total)
  Namespace                   Name                                       CPU Requests  CPU Limits  Memory Requests  Memory Limits  Age
  ---------                   ----                                       ------------  ----------  ---------------  -------------  ---
  default                     frontend-88dcd974c-vgsvz                   100m (5%)     0 (0%)      100Mi (5%)       0 (0%)         5m31s
  default                     redis-follower-6958c9f49c-g26gh            100m (5%)     0 (0%)      100Mi (5%)       0 (0%)         5m25s
  default                     redis-leader-6465bf85d4-4p6n6              100m (5%)     0 (0%)      100Mi (5%)       0 (0%)         5m20s
  kube-system                 local-path-provisioner-6bc6568469-kbm89    0 (0%)        0 (0%)      0 (0%)           0 (0%)         48m
  kube-system                 metrics-server-77dbbf84b-t6jv6             100m (5%)     0 (0%)      70Mi (3%)        0 (0%)         48m
  kube-system                 svclb-traefik-f6c3940d-285wh               0 (0%)        0 (0%)      0 (0%)           0 (0%)         48m
Allocated resources:
  (Total limits may be over 100 percent, i.e., overcommitted.)
  Resource           Requests     Limits
  --------           --------     ------
  cpu                400m (20%)   0 (0%)
  memory             370Mi (18%)  0 (0%)
  ephemeral-storage  0 (0%)       0 (0%)
  hugepages-1Gi      0 (0%)       0 (0%)
  hugepages-2Mi      0 (0%)       0 (0%)

  ==================================================================================================================