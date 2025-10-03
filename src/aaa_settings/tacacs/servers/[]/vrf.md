---
title: vrf
---

## Key

Key Name | Type | Required
---------|------|---------
`vrf` | str | false

## Description

VRF name.
The value will be interpreted according to these rules:
- `use_mgmt_interface_vrf` will configure the TACACS host under the VRF set with `mgmt_interface_vrf`.
    An error will be raised if `mgmt_ip` or `ipv6_mgmt_ip` are not configured for the device.
- `use_inband_mgmt_vrf` will configure the TACACS host under the VRF set with `inband_mgmt_vrf`.
    An error will be raised if inband management is not configured for the device.
- `use_default_mgmt_method_vrf` will configure the VRF and source-interface for one of the two options above depending on the value of `default_mgmt_method`.
- Any other string will be used directly as the VRF name.

## Path

> NOTE: We are using the [same format as jq](https://jqlang.org/) to specify the path to the key.

`.aaa_settings.tacacs.servers[].vrf`

## Example

```yaml
aaa_settings:
    tacacs:
        servers:
            - vrf: RED
```

## Child Keys

none

## Parent Key

- [`servers`](../../servers.md)
