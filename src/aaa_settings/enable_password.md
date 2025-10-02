---
title: enable_password
children:
    - enable_password/password.md
---
---

## Key

`enable_password`

## Type

dict

## Description

none

## Path

> NOTE: We are using the [same format as jq](https://jqlang.org/) to specify the path to the key.

`.aaa_settings.enable_password`

## Example

```yaml
aaa_settings:
    enable_password:
        password: <SHA512 hashed password>
```

## Child Keys

- [`password`](enable_password/password.md)

## Parent Key

- [`aaa_settings`](../aaa_settings.md)
