# Christmas Decorations Theme

Bring the Christmas spirit to your Home Assistant interface. This lightweight theme adds festive decorations to the UI and pairs nicely with Home Assistant's new Snowflakes feature (2025.12) for a seasonal, cheerful look. More decorations will be added over time.

## Screenshots

### Overview

![Theme - Overview - Dark](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-overview-dark.png)
![Theme - Overview - Light](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-overview-light.png)

### Map

![Theme - Map - Dark](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-map-dark.png)
![Theme - Map - Light](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-map-light.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

Install `card-mod` per the instructions on its [GitHub page](https://github.com/thomasloven/lovelace-card-mod "card-mod"). Card-mod is necessary for this theme to work.

### HACS

1. Go to the Community Store.
2. Search for `Christmas Decorations`.
3. Navigate to `Christmas Decorations` theme.
4. Press `Install`.
5. Go to services and trigger the `frontend.reload_themes` service.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/Thibov16/ha-christmas-decorations-theme.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/Thibov16/ha-christmas-decorations-theme.git
```

## Automation

You can automatically apply this theme around the Christmas season with an automation action:

```yaml
action: frontend.set_theme
data:
  name: Christmas Decorations
```

## Contributing

Have an idea or want to contribute? Great — feel free to open an issue or create a pull request.

- **Report ideas or bugs:** Open an issue describing the problem or idea. Include screenshots and steps to reproduce when applicable.
- **Submit changes:** Fork the repository, create a branch for your change, and open a pull request with a clear description of what you changed and why.