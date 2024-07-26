# Orbit B-Hyve Card

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)

This is a card for the [bhyve-home-assistant](https://github.com/sebr/bhyve-home-assistant) integration.

## Install

1. Navigate to the HACS add-on. Go to "Frontend", if HACS has separate pages for Integrations and Frontend.

2. Via the "..." menu at the top right, select "Custom repositories" and add https://github.com/davidn/bhyve-card as type "Lovelace" (or "Plugin", if you are on older HACS versions).

3. If there is a "Explore & download respositories" button, click on it and find "Orbit B-Hyve Card". If you directly see a list of cards, find "Orbit B-Hyve Card" (you may need to clear filters to see integrations that haven't been downloaded). Click on it and then click "Download".

4. When you are prompted to reload the frontend, do so.

## Usage

Select "Custom: Orbit B-Hyve Card" when adding a card to the dashboard. Configure it with the switch and history sensor entities created by the Orbit B-Hyve integration:

```
   type: custom:bhyve-card
   switch: switch.some_zone
   history: sensor.some_zone_history
```
