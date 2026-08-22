---
layout: default
title: Atlas Rhythm Guide
---

# Atlas Rhythm

[中文说明](atlas-rhythm-zh.html) · [All watch faces](./)

Atlas Rhythm is a personal-pattern watch face for Garmin devices. It compares your current rhythm with your own historical baseline instead of producing a generic health score.

## Supported devices

- Forerunner 165, 265, 265S, 570 (42 mm/47 mm), 965 and 970
- Venu 3, Venu 3S and Venu 4 (41 mm/45 mm)
- vívoactive 6
- epix (Gen 2)
- epix Pro (42 mm, 47 mm and 51 mm)
- fēnix 8 (43 mm, 47 mm and 51 mm), and fēnix E

The watch face supports English and Simplified Chinese. It requires a compatible Garmin device that provides the relevant Body Battery, stress and resting-heart-rate data.

## Four personal metrics

### Energy

Shows how the recent Body Battery trend compares with your usual trend at the same time of day. The evidence line shows the configured window's current average change per hour and your usual value. A positive deviation means a more favorable energy trend than usual — less depletion or more recovery.

### Stress

Shows today's time-weighted Garmin stress average compared with your usual value at the same point in the day. The evidence line shows `today|usual·coverage`; coverage helps identify incomplete sensor data. A positive deviation means today's stress is lower than your usual level.

### Recovery

Uses a fixed daily snapshot from the configured night window. It compares your overnight recovery trend with your own usual overnight trend. A positive deviation means recovery was faster than usual; a negative deviation means it was slower. Sleep-plan timing only defines this statistical window; it does not change the watch-face design.

### RHR

Shows the difference between Garmin's 7-day resting-heart-rate average and your personal baseline. A positive value means the 7-day average is higher than usual.

## How the baseline works

Atlas Rhythm stores compact local snapshots while it is the active watch face. For each metric, it compares the current value with values from the same time period across your recent personal history (up to 28 days; a 14-day minimum is used where applicable).

The baseline uses a median, rather than a simple average, so an unusually hard day has less influence. Median absolute deviation (MAD) is used to distinguish ordinary variation from a meaningful personal deviation.

The four cards are not medical measurements and should not be used for diagnosis or treatment decisions.

## ATLAS RHYTHM

The central **ATLAS RHYTHM** indicator is an unweighted summary of the four cards, not a 0–100 score. It reports how many usable indicators are currently in their ordinary range and highlights an available limiting factor when one needs attention. If enough baseline or sensor coverage is unavailable, it shows that data is insufficient.

## Reading the cards

- The large value is the deviation from your usual pattern.
- The short state is the interpretation of that deviation.
- The bottom line is the evidence used for the calculation.
- `C` on the Stress card is today's usable coverage.

The signs follow each metric's meaning. For Energy, Stress and Recovery, a positive deviation is more favorable than usual: for Stress, it means today's stress is lower; for Recovery, it means overnight recovery was faster. For RHR, a positive deviation means resting heart rate is higher than usual.

## First use and “data insufficient”

Atlas Rhythm needs both Garmin source data and enough of your own history before it can make a personal comparison. It is normal to see **data insufficient** when:

- you have just installed the watch face;
- the relevant Garmin field is unavailable or has incomplete coverage;
- you have recently returned from another watch face and there is a local snapshot gap; or
- the required historical baseline has not yet accumulated.

Keep Atlas Rhythm active and wear the watch normally. Cards become available independently as each metric obtains enough usable data; they do not all appear at once.

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

## Privacy

Atlas Rhythm calculates its personal comparisons from data available on your watch and stores its compact history locally on the watch. It does not require you to create an Atlas account.

## Frequently asked questions

### Is ATLAS RHYTHM a medical or readiness score?

No. It is an unweighted view of four personal deviations. It is intended to make patterns easier to notice, not to diagnose a condition, predict performance, or replace professional advice.

### Why can two cards be available while another is not?

Each card has different source-data and baseline requirements. For example, RHR relies on Garmin's 7-day average, while Recovery uses a nightly snapshot.

### Does changing the sleep schedule redesign the watch face?

No. The night setting only defines the Recovery statistical window.

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
