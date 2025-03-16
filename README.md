# Sharded Addon Template
Template for Sharded Addons, built with the best practices.

Sharded Addons by default will be generated with `metadata.json` containing the information which (apart from `description`) would appear when
a user is attempting to download.

## Installation

How a user would download your addon would be,
```bash
sharded addon install HOST/ADDON_NAME
```

- `HOST` = By default Sharded Addons will format it to fit github links to pull the addons from. For example, `sharded addon install shardedinteractive/ADDON_NAME`

- `ADDON_NAME` = Should be self-explanatory and has to **ABSOLUTELY** link to what the repository is named, for example, `sharded addon install HOST/addon-example`