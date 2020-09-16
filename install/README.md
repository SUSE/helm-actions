# Helm Install

Runs helm install command.

## Inputs

| Name | Description | Required | Default |
| --- | --- | --- | --- |
| name | The chart installation name. | true |  |
| chart | The chart to be installed. It must be a chart reference, a path to a packaged chart, a path to an unpacked chart directory or a URL.  | true |  |
| flags | The flags to be passed to the Helm command. One flag per line is accepted.  | false |  |

## Outputs

This action has no outputs.
