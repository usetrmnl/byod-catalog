# BYOD Catalog

The enclosed `byod_catalog.yml` file powers the client-side wizard at [https://trmnl.com/byod](https://trmnl.com/byod) (WIP) and [https://trmnl.com/welcome](https://trmnl.com/welcome) (requires login with a BYOD license).

### How it works

- `families` contains child `keyname` blocks which represent a device or brand category (wizard Step 1)
- `options` block may contain zero or more interstitial steps (wizard Step 2)
- `steps` block produces an ordered list of linkable instructions

### Contributing

Clarifying step additions and new device families are welcome. We'll take care of the `icon` parameter.
