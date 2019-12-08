# Eufy Security integration for Home Assistant

At this moment, this repo simply extracts [@bachya](https://github.com/bachya)'s [PR for Home Assistant](https://github.com/home-assistant/home-assistant/pull/28443) which uses [@FuzzyMistborn](https://github.com/FuzzyMistborn)'s package [`python-eufy-security`](https://github.com/FuzzyMistborn/python-eufy-security).

## Installation

### From HACS

1. Install HACS if you haven't already (see [installation guide](https://hacs.netlify.com/docs/installation/manual)).
2. Add custom repository `https://github.com/nonsleepr/ha-eufy-security` as "Integration" in the settings tab of HACS.
3. Find and install "Eufy Security" intergration in HACS's "Integrations" tab.
4. Restart your Home Assistant.
5. Add "Eufy Security" integration in Home Assistant's "Configuration -> Integrations" tab.

### Manual

1. Download and unzip the [repo archive](https://github.com/nonsleepr/ha-eufy-security/archive/master.zip). (You could also click "Download ZIP" after pressing the green button in the repo, alternatively, you could clone the repo from SSH add-on).
2. Copy contents of the archive/repo into your `/config` directory.
3. Restart your Home Assistant.
4. Add "Eufy Security" integration in Home Assistant's "Configuration -> Integrations" tab.

### Notes

The camera card might not show up in Lovelace interface automatically, in that case you can add it by editing the UI.
