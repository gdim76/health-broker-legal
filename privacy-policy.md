---
layout: default
title: Health Broker Privacy Policy
---

# Health Broker Privacy Policy

**Effective date: 26 November 2026**

Health Broker is a personal Android proof of concept. This policy explains how
the app handles data when used on your device.

## Data the app handles

The app may process the following data on the device:

- Bluetooth Low Energy measurements from a Xiaomi Mi Body Composition Scale 2,
  including weight and, where the scale exposes it, raw impedance;
- an optional local profile: height, date of birth, biological sex, and an
  expected weight range;
- user-confirmed measurement ownership status;
- optional local calibration points: weight, raw impedance, and a body-fat
  percentage manually entered from Zepp.

## Purpose and local storage

The app uses this data solely to display measurements, support user ownership
decisions, and evaluate a local body-fat calibration proof of concept. The app
has no Health Broker account system, backend, analytics service, advertising,
or sale of personal data.

Local profile settings and calibration or ownership records are stored in the
app's private storage on the device. They are excluded from Android cloud
backup and device-transfer backup. Raw BLE diagnostic payloads are held only in
memory during a manually started diagnostic session and are not stored in the
local calibration database.

## Huawei Health

The current proof of concept does not transmit data to Huawei Health. A future
write to Huawei Health will occur only after all of the following:

1. Huawei grants the required Health Service Kit scope;
2. the user completes Huawei authorization in the app; and
3. the user has explicitly confirmed that the measurement belongs to them.

If enabled in a future version, a confirmed weight record will be sent directly
from the device to Huawei Health through Huawei's official SDK. Huawei's own
privacy terms apply to data handled by Huawei Health.

## Your choices and deletion

You may leave all optional profile fields empty. You can delete the local
profile and calibration points in the app. To delete all locally stored Health
Broker data, use Android Settings to clear the app's storage or uninstall the
app. You may revoke Huawei Health authorization through Huawei's controls when
that integration is enabled.

## Changes and contact

If this policy changes materially, the effective date above will be updated.
For privacy questions or deletion assistance, contact
[gdim76@gmail.com](mailto:gdim76@gmail.com).
