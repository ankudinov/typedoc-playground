---
title: groups
---

## Key

Key Name | Type | Required
---------|------|---------
`groups` | list | true

## Description

none

## Path

> NOTE: We are using the [same format as jq](https://jqlang.org/) to specify the path to the key.

`.aaa_settings.tacacs.servers.groups`

## Example

```yaml
aaa_settings:
    tacacs:
        servers:
            - groups: [ TACACS_GROUP ]
```

## Child Keys

none

## Parent Key

- [`servers`](../../servers.md)
