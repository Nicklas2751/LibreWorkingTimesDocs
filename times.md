---
layout: default
title: Times
nav_order: 3
---

# Times overview
{: .no_toc }

The main view of LibreWorkingTimes is the times overview where entries can be created, deleted and edited.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

The times view is the main view of LibreWorkingTimes and enables to create, edit and delete entries. \
It consists mostly of a list of months and their days.

This view consits of four parts.

{% include lightbox.html src="assets/screenshots/screenshot_mobile_light_parts.png" data="parts-overview" title="Overview of the parts of the times view" style="width:300px" %}

1. A overview of the complete overtime, the work time and the overtime of today.
2. The month and year the currently shown days belong to.
3. The days and their entries
4. The quick actions menu

## Days and entries

{% include lightbox.html src="assets/screenshots/screenshot_mobile_light_entries.png" data="days-and-entries-overview" title="Screenshot of the overview of days and their entries in light mode" style="width:300px" %}
{% include lightbox.html src="assets/screenshots/screenshot_mobile_dark_entries.png" data="days-and-entries-overview" title="Screenshot of the overview of days and their entries in dark mode" style="width:300px" %}

The two screenshots are showing some different entries. In the same order this are:

1. A currently running work time entry.
2. A completed work time entry.
3. Overtime reduce
4. Vacation
5. Illness

## The quick actions menu

{% include lightbox.html src="assets/screenshots/screenshot_mobile_light_quick_actions.png" data="quick-actions" title="Screenshot of quick actions menu" style="width:300px" %}

In the quick actions menu are three entries:

1. Start / Stop work
  - Starts or stops the current work. Which means, that for the current day a entry with an open end is created. When the work will be stopped the end is set to the current time. A currently running entrys work time and overtime is getting updated every minute.
2. New entry
   - Opens the new entry dialog
3. Cancel
   - Closes the quick actions menu

{% include lightbox.html src="assets/gifs/start_stop_work.gif" data="start_stop_work_gif" title="A gif of starting and stopping current work" style="width:300px" %}

## Create / Edit entry

The dialog for creating and editing entries are the same.\
\
The top bar of the dialog consits of three parts:

1. The `Abort` button which discards changes and closes the dialog
2. The dialog title which starts with `Edit` when a existing entry is being changed or `Add` when a new entry is being created. After these keywords follows the date of the entry.
3. The `Save` button which saves the canges or creates the new entry and closes the dialog.

The first field in the dialog is always the `Type` field. Based on its selection the fileds for a work time, overtime, vacation or illness entry are shown.

{% include lightbox.html src="assets/screenshots/screenshot_mobile_light_dialog_worktime_edit.png" data="dialog-worktime" title="Screenshot of the work time entry edit dialog" style="width:300px" %}

### Work time

{% include lightbox.html src="assets/screenshots/screenshot_mobile_light_dialog_worktime_new.png" data="dialog-worktime" title="Screenshot of the work time entry create dialog" style="width:300px" %}

The work time dialog has two own fields:

1. The `start time field` which sets the start date and time for the work time entry.
2. The `end time field` which sets the end date and time for the work time entry. If nothing is set it gets calculated from the start time field based on the `daily work time` and `typical break duration` set in the [settings](/settings).

### Overtime

{% include lightbox.html src="assets/screenshots/screenshot_mobile_light_dialog_overtime_new.png" data="dialog-overtime" title="Screenshot of the overtime entry create dialog" style="width:300px" %}

The overtime dialog has four own fields:

1. The `day` field which sets for which day the overtime entry is.
2. The `overtime amount` which sets how many overtime hours and minutes should be added or removed. Its only visible if the `full day` switch isn't activated.
3. The `full day` switch decides if a specific amount of overtime should be adderd or removed or if the `daily work time` form the [settings](/settings) should be used.
4. The `add or remove` switch which decides if the overtime amount should be added or removed.

### Vacation & Illness

{% include lightbox.html src="assets/screenshots/screenshot_mobile_light_dialog_vacation_new.png" data="dialog-vacation-illness" title="Screenshot of the vacation entry create dialog" style="width:300px" %}
{% include lightbox.html src="assets/screenshots/screenshot_mobile_light_dialog_illness_new.png" data="dialog-vacation-illness" title="Screenshot of the illness entry create dialog" style="width:300px" %}

The vacation and the illness dialog are the same but the type is different. It has two own fields:

1. The `start date` field which sets the first day, it self including.
2. The `end date` which sets the last day, it self including.

If the entry duration is set for multiple days a new entry is generated for each day on save so every day has its own entry. Days which aren't set as `workday` in the [settings](/settings) are skipped.
