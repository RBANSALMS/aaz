# [Command] _vmware workload-network port-mirroring create_

Create a port mirroring profile by id in a private cloud workload network.

## Versions

### [2022-05-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5hdnMvcHJpdmF0ZWNsb3Vkcy97fS93b3JrbG9hZG5ldHdvcmtzL2RlZmF1bHQvcG9ydG1pcnJvcmluZ3Byb2ZpbGVzL3t9/2022-05-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.avs/privateclouds/{}/workloadnetworks/default/portmirroringprofiles/{} 2022-05-01 -->

#### examples

- Create a port mirroring profile by ID in a workload network.
    ```bash
        vmware workload-network port-mirroring create --resource-group group1 --private-cloud cloud1 --port-mirroring portMirroring1 --display-name portMirroring1 --direction BIDIRECTIONAL --source vmGroup1 --destination vmGroup2 --revision 1
    ```
