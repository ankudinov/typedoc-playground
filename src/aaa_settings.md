---
title: aaa_settings
children:
    - aaa_settings/enable_password.md
    - aaa_settings/tacacs.md
---

`aaa_settings`

`aaa_settings` is an eos_designs key used to configure AAA.

## Example

```yaml
aaa_settings:
    enable_password:
        password: <SHA512 hashed password>
  tacacs:
    servers:
      - host: 1.2.3.4
```

## Keys

- [`enable_password`](aaa_settings/enable_password.md)
- [`tacacs`](aaa_settings/tacacs.md)
