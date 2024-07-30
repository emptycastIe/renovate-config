# renovate-config

To host the renovate config.

- `config.js` holds the self-hosted Renovate configuration so that Renovate knows what and how it should process.
- `renovate.json` in this repository ensures to receive Renovate updates.
- `default.json` holds the basic config for all repositories. It extends the presets by the renovate project defined in `renovate-schema.json`.
- Each repository can extend/alter this config by adding a `renovate.json` file to the root of the repository.