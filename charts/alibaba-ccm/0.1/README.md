# Alibaba Cloud Controller Manager
Alibaba cloud controller manager.

## Parameters
The following table lists the configurable parameters of the alibaba cloud-controller-manager chart.

| Parameter                                   | Description                                         | Default                                                           |
|---------------------------------------------|-----------------------------------------------------|-------------------------------------------------------------------|
| `nameOverride`                              | String to partially override alibaba-ccm.fullname template with a string (will prepend the release name) | `nil`        |
| `fullnameOverride`                          | String to fully override alibaba-ccm.fullname template with a string                                     | `nil`        |
| `accessKey`                                 | Alibaba cloud accessKey.                            | `nil`                                                             |
| `accessSecret`                              | Alibaba cloud accessSecret.                         | `nil`                                                             |
| `clusterCIDR`                               | Specifies cluster CIDR                              | `nil`                                                             |
| `rbac.create`                               | Create and use RBAC resources                       | `false`                                                           |
| `serviceAccount.create`                     | Specifies whether a ServiceAccount should be created | `false`                                                          |
| `region`                                    | Specifies alibaba region                             | `false`                                                          |
