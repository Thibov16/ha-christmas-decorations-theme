# Christmas Decorations Theme

## Screenshots

### Overview

![Theme - Overview](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-overview.png)

### Map

![Theme - Map](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-map.png)

### Logbook

![Theme - Logbook](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-logbook.png)

### History

![Theme - History](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-history.png)

### Developer Tools

![Theme - Developer Tools](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-developer-tools.png)

### Configuration

![Theme - Configuration](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-configuration.png)

### Profile

![Theme - Profile](https://raw.githubusercontent.com/Thibov16/ha-christmas-decorations-theme/master/docs/theme-profile.png)

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
