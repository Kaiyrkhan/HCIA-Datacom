# Huawei External BGP (eBGP)

### 🖧 Network Topology

![Topology](images/Topology_eBGP.png)  
[Download Link for PNETLab Topology File](Topology/Topology_eBGP.topo)

**HQ-RT1**
```shell
[R1] display ip routing-table
[R1] ping 50.2.2.2
[R1] ping 172.16.112.1
```

**BR-RT1**
```shell
[R2] display ip routing-table
[R2] ping 50.1.1.1
[R2] ping 172.16.111.1
```
