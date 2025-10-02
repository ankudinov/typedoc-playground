---
title: password
---

## Key

Key Name | Type | Required
---------|------|---------
`password` | str | false

## Description

SHA512 hashed password.

## Path

> NOTE: We are using the [same format as jq](https://jqlang.org/) to specify the path to the key.

`.aaa_settings.enable_password.password`

## Example

```yaml
aaa_settings:
    enable_password:
        password: <SHA512 hashed password>
```

## Child Keys

none

## Parent Key

- [`enable_password`](../enable_password.md)
