# Orrery updates

`latest.json` is read by the Orrery plugin (at most every 6 hours). Fields:

- `version`: the newest public version, e.g. `1.0.1`. The plugin shows the bar only when this is higher than the installed version.
- `url`: where "Download" goes. Must be https and on renger.com, renger.shop or github.com.
- `note`: one short line (max 160 characters).

Right now: version 2.13.0 (the current build, so no update bar). To test the update bar, temporarily set a higher version such as 9.0.0, then set it back.
