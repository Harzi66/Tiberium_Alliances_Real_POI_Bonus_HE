# Tiberium Alliances Real POI Bonus HE

An extensively enhanced version of the original **Tiberium Alliances Real POI Bonus** userscript by **petui**, continued and expanded by **Harzi**.

The script adds a local POI event archive, automatic background synchronization, rank forecasts, coordinate search and map navigation, configurable forecast levels, and a multilingual interface.

## Features

### POI Bonus Overview

- Displays information about the selected Point of Interest (POI).
- Shows the alliance bonus and alliance rank information.
- Estimates the POI points required for the next rank increase or decrease.
- Provides both **realistic** and **optimistic** estimates for gains and losses.
- Shows the POI level used for each estimate.

### POI Archive

- Stores POI gained/lost events locally.
- Performs an initial historical backfill and then uses incremental synchronization on later game starts.
- Continues collecting events in the background; opening the archive is not required for collection.
- Keeps the archive separate from the game's notification list.
- Offers separate tabs for all seven POI categories:
  - Tiberium
  - Crystal
  - Energy
  - Infantry
  - Vehicles (Uranium)
  - Air Force
  - Resonance

### Search and Map Navigation

- Search archived events by coordinates.
- Click an archived event to close the archive and center the world map on the event's coordinates.

### Configuration

- Choose the archive retention period: 3 months, 6 months, 1 year, 2 years, or unlimited.
- Set the maximum POI level used for forecasts (default: **46**).
- The optimistic forecast considers up to two POI levels above the selected POI's level, subject to the configured maximum.
- Select the interface language: **German, English, French, or Spanish**.
- Filter the archive to show gained events, lost events, or both.

## Screenshots

The screenshots below are included in this repository.

### POI Bonus Overview

<!-- Insert screenshot of the POI bonus overview here -->

### POI Archive

<!-- Insert screenshot of the POI archive here -->

### Archive Options and Settings

<!-- Insert screenshot of the archive options and settings here -->

## Installation

1. Install a userscript manager such as [Tampermonkey](https://www.tampermonkey.net/).
2. Open the userscript file in this repository: [Tiberium_Alliances_Real_POI_Bonus_HE.user.js](Tiberium_Alliances_Real_POI_Bonus_HE.user.js).
3. Click **Raw** on GitHub. Tampermonkey should offer to install the script.
4. Confirm the installation.

## Updates

The script header contains the `@downloadURL` and `@updateURL` entries pointing to this repository's `main` branch. A userscript manager can use these URLs to check for updates.

## Compatibility

Designed for the browser-based **Command & Conquer: Tiberium Alliances** game and userscript managers that support the script metadata used here.

## Credits and License

- **Original author:** petui – original script and foundation.
- **Further development:** Harzi – extensive feature development and maintenance of the HE edition.

This project is distributed under the **GNU General Public License v3.0 or later (GPL-3.0-or-later)**.

See the [GNU GPL v3.0 license](https://www.gnu.org/licenses/gpl-3.0.html).

The original author's contribution is acknowledged. The HE edition builds on that original work and adds substantial new functionality.
