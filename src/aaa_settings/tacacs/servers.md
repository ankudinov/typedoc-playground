---
title: servers
children:
    - servers/[].md
---

## Key

Key Name | Type | Required
---------|------|---------
`servers` | list | false

## Description

none

## Path

> NOTE: We are using the [same format as jq](https://jqlang.org/) to specify the path to the key.

`.aaa_settings.tacacs.servers`

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

- [`host`](servers/[]/host.md)
- [`groups`](servers/[]/groups.md)
- [`vrf`](servers/[]/vrf.md)
- [`key`](servers/[]/key.md)
- [`cleartext_key`](servers/[]/cleartext_key.md)

## Parent Key

- [`tacacs`](../tacacs.md)
