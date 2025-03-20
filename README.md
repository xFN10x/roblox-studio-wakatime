# Roblox Studio WakaTime

This is a plugin for automatically tracking your time spent in Roblox Studio, with support for tracking:

-   Time spent in the code editor (with script names)
-   Time spent playtesting
-   Time spent editing in the viewport

## Installation

[Install on the Creator Hub](https://create.roblox.com/store/asset/76658431643665/WakaTime)

It is also possible to place the latest `rbxm` from the [Releases](https://github.com/tacheometry/roblox-studio-wakatime/releases) tab in your local plugins folder.

![Screenshot](./assets/plugin_screenshot.png)

## Building

> [!IMPORTANT]
> Please make sure to install the required [Dependencies](./wally.toml) via the following command:
>
> ```
> wally install
> ```

<br>

To generate a build for _testing_, run:

```
rojo build -p "RobloxStudioWakaTime.rbxm"
```

<sub>_This will automatically install it into your **Roblox Studio** Plugins folder._</sub>

<br>

To manually generate a **final** build, run:

```
rojo build -o "RobloxStudioWakaTime.rbxm"
```

<sub>_This will instead just generate the file directly in **this** directory._</sub>
