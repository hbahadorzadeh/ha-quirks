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
