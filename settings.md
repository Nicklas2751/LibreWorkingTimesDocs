---
layout: default
title: Settings
nav_order: 5
---

# Settings
{: .no_toc }

The settings view of LibreWorkingTimes is the place to set the personal application settings.
{: .fs-6 .fw-300 }

---

The settings view enables to set the personal application settings for the own needs. \
It consists mostly of a list of fileds. All settings are saved directly after editing them.

{% include lightbox.html src="assets/screenshots/screenshot_mobile_light_settings.png" data="settings" title="Screenshot of the application settings" style="width:300px" %}

The following settings are available:

1. `Designation` is shown as subtitle in the menu and should help the user to identify what time he is tracking in the application.
  - Default Value: `John Doe @ Example Corp`
2. `Daily working time` sets the amount of work time per day is needed. Its the calculation base for overtime and will be used when `full day` is activated for overtime entries.
  - Default Value: `08:00` (hh:mm)
3. `Typical break duration` sets the amount of break time per day. Its used to calculate the work time and overtime for a day.
  - Default Value: `00:30` (hh:mm)
4. `Working days` are the days a week on which the user works reguarrly. Its used when illness or vacation entries for multiple days are generated. Non working days are ignored for these generation.
  - Default Value: `Monday, Tuesday, Wednesday, Thursday, Friday`