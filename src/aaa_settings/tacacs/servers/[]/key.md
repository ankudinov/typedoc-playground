---
title: key
---

## Key

Key Name | Type | Required
---------|------|---------
`key` | str | false

## Description

Encrypted Type 7 key.
Takes precedence over `cleartext_key` if both are provided.
Either `key` or `cleartext_key` must be set to render the configuration;
otherwise, an error will be raised.

## Path

> NOTE: We are using the [same format as jq](https://jqlang.org/) to specify the path to the key.

`.aaa_settings.tacacs.servers[].key`

## Example

```yaml
aaa_settings:
    tacacs:
        servers:
            - key: <type-7 encrypted key>
```

## Child Keys

none

## Parent Key

- [`servers`](../../servers.md)
