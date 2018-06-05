# Bolt analytics collection

Bolt automatically collects data about how you use it.

## What data does Bolt collect?

* Version of Bolt
* The Bolt command executed (eg. `bolt task run`, `bolt plan show`), excluding arguments
* User locale

This data is associated with a random, non-identifiable user UUID.

You can see the data Bolt is sending by running with `--debug`.

## Why does Bolt collect data?

Bolt collects data to help us understand how it's being used and make decisions about how to improve it.

## Opt-out

You can disable the collection of analytics data by adding the following line to `~/.puppetlabs/bolt/analytics.yaml`:

```
disabled: true
```