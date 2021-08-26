---
layout: default
title: Times
nav_order: 3
---

# Times overview
{: .no_toc }

The main view of LibreWorkingTimes is the Times overview where Entries can be created, deleted and edited.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

The times view is the main view of LibreWorkingTimes and enables to create, edit and delete entries. \
It consists mostly of a list of months and their days. \

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
