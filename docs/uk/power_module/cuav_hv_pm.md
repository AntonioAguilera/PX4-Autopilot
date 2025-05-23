# CUAV HV PM (High-Voltage модуль живлення)

The CUAV<sup>&reg;</sup> _HV_PM_ power module is a "high voltage" power module independently developed by CUAV.

:::tip
The _HV_PM_ is included in the CUAV V5+/V5 nano kit, but is also be sold separately.
Існують різні кабелі в залежності від контролера польоту (Pixhack v3, V5+/V5 nano, Pixhawk).
Це може бути використано з іншими контролерами польоту, але вам може знадобитися змінити контактний пін.
:::

## Характеристики

- **Higher voltage input:** 10V-60V (3s~14s battery)
- **Accurate battery monitor:**
  - **Voltage detection accuracy:** +-0.1v;
  - **Current detection accuracy:** +-0.2A
- **BEC (5v) max current:** 5A
- **Max (detection) current:** 60A
- **Max output current (ESC/MOTOR PORT):** 60A

## Де купити

[CUAV aliexpress store](https://www.aliexpress.com/item/32841805115.html?spm=2114.12010615.8148356.1.64165998hPvTKQ)

## Схема розташування виводів

![HV PM](../../assets/hardware/power_module/cuav_hv/hv_pm.jpg)

## Увімкнути HV PM

[Battery Estimation Tuning](../config/battery.md) describes how to configure the battery and power module.

The key configuration settings for `HV_PM` are:

- **Voltage divider:** 18
- **Amps per volt:** 24 A/V
