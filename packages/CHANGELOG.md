# Changelog

## Unreleased

- Rename sensor id `temp` → `temperature` across packages and displays.
  - Updated: `sensor_bme680.yaml`, `display_sh1106_multi_page.yaml`, `display_sh1106_single_page.yaml`, `display_ssd1306.yaml`, `sensor_pms5003t*.yaml`, and related templates.
  - Rationale: use a clearer, non-ambiguous id to avoid collisions and improve readability.
  - Note: `temp_raw`, `temp_2`, and other similarly named raw/secondary sensors were left unchanged.

Please update any external automations/dashboards that reference the old `temp` id to `temperature`.
