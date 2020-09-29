# Helm Add Repository

Runs helm repo add command.

## Inputs

| Name | Description | Required | Default |
| --- | --- | --- | --- |
| name | The repository name. | true |  |
| url | The repository URL. | true |  |
| flags | The flags to be passed to the Helm command. One flag per line is accepted.  | false |  |
| update | Whether to run helm repo update or not. |  | `false` |

## Outputs

This action has no outputs.
