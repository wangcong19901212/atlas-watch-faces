---
layout: default
title: Atlas Rhythm Guide
---

# Atlas Rhythm

[中文说明](atlas-rhythm-zh.html) · [All watch faces](./)

Atlas Rhythm is a personal-pattern watch face for Garmin devices. It compares your current rhythm with your own historical baseline instead of producing a generic health score.

## Four personal metrics

### Energy

Shows how the recent Body Battery trend compares with your usual trend at the same time of day. The evidence line shows the configured window's current average change per hour and your usual value.

### Stress

Shows today's time-weighted Garmin stress average compared with your usual value at the same point in the day. The evidence line shows `today|usual·coverage`; coverage helps identify incomplete sensor data.

### Recovery

Uses a fixed daily snapshot from the configured night window. It compares your overnight recovery trend with your own usual overnight trend. Sleep-plan timing only defines this statistical window; it does not change the watch-face design.

### RHR

Shows the difference between Garmin's 7-day resting-heart-rate average and your personal baseline. A positive value means the 7-day average is higher than usual.

## How the baseline works

Atlas Rhythm stores compact local snapshots while it is the active watch face. For each metric, it compares the current value with values from the same time period across your recent personal history (up to 28 days; a 14-day minimum is used where applicable).

The baseline uses a median, rather than a simple average, so an unusually hard day has less influence. Median absolute deviation (MAD) is used to distinguish ordinary variation from a meaningful personal deviation.

The four cards are not medical measurements and should not be used for diagnosis or treatment decisions.

## Overall status

The center indicator is an unweighted summary of the four cards, not a 0–100 score. It reports how many usable indicators are currently in their ordinary range and highlights an available limiting factor when one needs attention. If enough baseline or sensor coverage is unavailable, it shows that data is insufficient.

## Reading the cards

- The large value is the deviation from your usual pattern.
- The short state is the interpretation of that deviation.
- The bottom line is the evidence used for the calculation.
- `C` on the Stress card is today's usable coverage.

The signs follow each metric's meaning. For Energy, a positive deviation is a more favorable trend than usual. For Stress, a positive deviation means stress is higher than usual. For RHR, a positive deviation means resting heart rate is higher than usual.

## Settings

Atlas Rhythm settings are available in Garmin Connect on your phone. The settings page follows Garmin Connect's language; the watch face itself can be switched between English and Simplified Chinese.

Available options include:

- Watch-face language
- Energy comparison window and sensitivity
- Night recovery window
- Display preferences supported by the installed device

## Data, updates and gaps

Historical snapshots and settings are stored locally on the watch. Installing a normal update of the same Atlas Rhythm app preserves them. Uninstalling the app removes its local data.

When another watch face is active, Atlas Rhythm does not continue writing its own periodic snapshots. On return, it uses retained local history and can refill recent Garmin history when appropriate; a gap may still require more wear time before every personal baseline is available again.

## Requirements and limitations

Results depend on Garmin data availability, wear time and sensor coverage. Body Battery, stress, sleep and resting-heart-rate fields can be unavailable on some devices or during incomplete recording periods.

Garmin and Connect IQ are trademarks of Garmin Ltd. or its subsidiaries. Atlas Rhythm is an independent watch face and is not a medical device.

---

## Support development

### China

#### WeChat Pay

<img src="assets/wechat.png" alt="WeChat Pay QR code" width="220">

#### Alipay

<img src="assets/alipay.png" alt="Alipay QR code" width="220">

### International

[Support Atlas Watch Faces on Ko-fi](https://ko-fi.com/atlaswatch)
