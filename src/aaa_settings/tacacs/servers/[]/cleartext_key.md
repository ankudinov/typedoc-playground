---
title: cleartext_key
---

## Key

Key Name | Type | Required
---------|------|---------
`cleartext_key` | str | false

## Description

Plaintext password that will be encrypted to Type 7 by AVD.
To protect the password at rest it is strongly recommended to make use of a vault or similar.
Either `key` or `cleartext_key` must be set to render the configuration;
otherwise, an error will be raised.

## Path

> NOTE: We are using the [same format as jq](https://jqlang.org/) to specify the path to the key.

`.aaa_settings.tacacs.servers[].cleartext_key`

## Example

```yaml
aaa_settings:
    tacacs:
        servers:
            - cleartext_key: not-a-secret
```

## Child Keys

none

## Parent Key

- [`servers`](../../servers.md)
