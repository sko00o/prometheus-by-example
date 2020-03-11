# Prometheus by Example

This repo contains a collection of prometheus example projects that can be used for reference when adding monitoring
to your existing applications.

## Examples

[Job Processor](./job-processor) - Demonstrates how to add basic monitoring when working with a worker based service

## Issues

Change grafana directory owner to fix permision issue.

```sh
sudo chown 472:472 ./job-processor/.docker/grafana -R
```
 