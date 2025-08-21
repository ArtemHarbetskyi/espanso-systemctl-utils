# Systemctl Utilities

🇺🇦 Цей пакет додає зручні команди для espanso `systemctl`.

🇺🇸 This package adds convenience commands to espanso `systemctl`.

### Use:
- `:scstatus` → `systemctl status`
- `:scstart` → `systemctl start`
- `:scstop` → `systemctl stop`
- `:scforcestop` → `systemctl force-stop`
- `:screstart` → `systemctl restart`
- `:sclist` → `systemctl list-units --type=service`
- `:scenable` → `systemctl enable`
- `:scdisable` → `systemctl disable`
- `:scmask` → `systemctl mask`
- `:scunmask` → `systemctl unmask`
- `:screload` → `systemctl reload`
- `:scforcereload` → `systemctl force-reload`

### Install:
```bash
espanso install systemctl-utils --git https://github.com/ArtemHarbetskyi/espanso-systemctl-utils.git --external
```

or

```bash
espanso install systemctl-utils
```