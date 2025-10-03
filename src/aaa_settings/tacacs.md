---
title: tacacs
children:
    - tacacs/servers.md
---

## Key

Key Name | Type | Required
---------|------|---------
`tacacs` | dict | false

## Description

none

## Path

> NOTE: We are using the [same format as jq](https://jqlang.org/) to specify the path to the key.

`.aaa_settings.tacacs`

## Example

```yaml
aaa_settings:
    tacacs:
        servers:
            - host: 10.54.76.8
              groups: [ TACACS_GROUP ]
              vrf: RED
```

## Child Keys

- [`servers`](tacacs/servers.md)

## Parent Key

- [`aaa_settings`](../aaa_settings.md)
