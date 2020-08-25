# Terway CNI Network Plugin
CNI plugin for Alibaba Cloud VPC/ENI.

## Parameters
The following table lists the configurable parameters of the Terway chart and their default values.

| Parameter                                   | Description                                         | Default                                                           |
|---------------------------------------------|-----------------------------------------------------|-------------------------------------------------------------------|
| `nameOverride`                              | String to partially override terway.fullname template with a string (will prepend the release name) | `nil`             |
| `fullnameOverride`                          | String to fully override terway.fullname template with a string                                     | `nil`             |
| `mode`                                      | Terway running mode(vpc/eni).                       | `vpc`                                                             |
| `accessKey`                                 | Alibaba cloud accessKey.                            | `nil`                                                             |
| `accessSecret`                              | Alibaba cloud accessSecret.                         | `nil`                                                             |
| `securityGroup`                             | Alibaba security group.                             | `nil`                                                             |
| `vSwitches`                                 | Alibaba vSwitches(eni only).                        | `{}`                                                              |
| `rbac.create`                               | Create and use RBAC resources                       | `false`                                                           |
| `serviceAccount.create`                     | Specifies whether a ServiceAccount should be created | `false`                                                          |
| `serviceAccount.name`                       | The name of the ServiceAccount to create            | Generated using the terway.fullname template                      |
