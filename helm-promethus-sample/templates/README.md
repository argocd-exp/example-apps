# Prometheus QuickStart
By using these manifests, you can quickly deploy a simple prometheus that use a `ServiceMonitor` to select pods labeled `app:rpc-app`.


Note: You need to set the `namespace` in the `RoleBinding.yaml` before using the below command.

```
cd Prometheus/quickstart
oc create -f ./
```
