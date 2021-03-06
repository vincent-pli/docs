The following examples will help you understand how to use Parallel to describe
various flows.

## Prerequisites

All examples require:

- A Kubernetes cluster with
  - Knative Eventing v0.9+
  - Knative Service v0.8+

All examples are using the
[default channel template](../../channels/default-channels.md).

## Examples

For each of these examples below, we'll use
[`CronJobSource`](../cronjob-source/README.md) as the source of events.

We also use simple
[functions](https://github.com/lionelvillard/knative-functions) to perform
trivial filtering, transformation and routing of the incoming events.

The examples are:

- [Parallel with multiple branches and global reply](./multiple-branches/README.md)
- [Parallel with mutually exclusive cases](./mutual-exclusivity/README.md)
