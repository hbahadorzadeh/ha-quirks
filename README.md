# ha-quirks
HomeAssistant ZHA quirks


To install add this section to your `configuration.yaml` file:

```yaml
zha:
  enable_quirks: true
  quirks_path: /config/zha_quirks
```

Then clone this repository to `/config/zha_quirks`:

```bash
mkdir /config/zha_quirks
git clone https://github.com/hbahadorzadeh/ha-quirks.git .
```
Supported devices:
- [Tuya TS0601_thermostat](https://nl.aliexpress.com/item/1005005145690732.html?spm=a2g0o.order_list.order_list_main.44.5bf679d2M10QUN&gatewayAdapt=glo2nld)
