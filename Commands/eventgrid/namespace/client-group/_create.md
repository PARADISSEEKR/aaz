# [Command] _eventgrid namespace client-group create_

Create a client group.

## Versions

### [2023-06-01-preview](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5ldmVudGdyaWQvbmFtZXNwYWNlcy97fS9jbGllbnRncm91cHMve30=/2023-06-01-preview.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.eventgrid/namespaces/{}/clientgroups/{} 2023-06-01-preview -->

#### examples

- Create client group
    ```bash
        eventgrid namespace client-group create -g rg --namespace-name name -n client-group --group-query "attributes.floor=6"
    ```