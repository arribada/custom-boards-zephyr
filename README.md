# Arribada Custom Board Directory

This repo contains the custom board files for Arribada Initiative.

To add any of the boards to your Zephyr project, add the following to your `west.yml` manifest file:

```yaml
    - name: arribada-custom-boards
      path: deps/arribada-custom-boards
      revision: v3.5.0 # see note below
      url: https://github.com/arribada/custom-boards-zephyr
```

> Note: After `v3.5.0`, the board directory structure has changed and the boards will need to be updated to the new structure. Checkout the `v3.5.0` branch for the last version that supports the old directory structure. Backwards compatibility may or may not be maintained in the future.

## Supported Boards

- [Adafruit Feather HUZZAH32 - ESP32](https://www.adafruit.com/product/3405)