---
title: host
---

## Key

Key Name | Type | Required
---------|------|---------
`host` | str | true

## Description

Host IP address or name.
Combination of `host` and `vrf` should be unique.

## Path

> NOTE: We are using the [same format as jq](https://jqlang.org/) to specify the path to the key.

`.aaa_settings.tacacs.servers[].host`

## Example

```yaml
aaa_settings:
    tacacs:
        servers:
            - host: 10.54.76.8
```

## Child Keys

none

## Parent Key

- [`servers`](../../servers.md)
