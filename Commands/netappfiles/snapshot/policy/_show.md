# [Command] _netappfiles snapshot policy show_

Get a snapshot Policy

## Versions

### [2023-05-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXRhcHAvbmV0YXBwYWNjb3VudHMve30vc25hcHNob3Rwb2xpY2llcy97fQ==/2023-05-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.netapp/netappaccounts/{}/snapshotpolicies/{} 2023-05-01 -->

#### examples

- Get an ANF snapshot policy
    ```bash
        netappfiles snapshot policy show -g mygroup --account-name myaccname --snapshot-policy-name mysnapshotpolicyname
    ```