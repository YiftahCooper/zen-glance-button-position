# Glance Button Position

A CSS-only [Sine](https://github.com/CosmoCreeper/Sine) mod for Zen Browser. Choose which side the Glance buttons appear on and position them anywhere vertically using a percentage.

## Install

1. With Sine installed, open **Settings → Sine Mods** and find the option to install from a GitHub repository.
2. Paste this repository's URL and click **Install**:

   ```text
   https://github.com/YiftahCooper/zen-glance-button-position
   ```

3. Disable **Left Side Glance Buttons** or any other mod that moves these buttons, to avoid conflicting styles.
4. Restart Zen once after installation, then open this mod's configuration in Sine.

After initial activation, side and percentage changes apply without restarting.

## Settings

| Setting | Choices | Default |
| --- | --- | --- |
| Button Side | Left or Right, independently of Zen's sidebar position | Left |
| Vertical Position (%) | Any number from 0 to 100, including decimals | 0 |

Enter a number **without the `%` sign**, such as `37.5`. Press **Tab** or click outside the field to apply it.

- `0` places the button group at the top.
- `50` centres the group vertically.
- `100` places the group at the bottom.

These are examples, not presets: `12`, `63.25`, and other values work too. Position follows the **Glance panel's height**, with a 15px margin at each end. The calculation accounts for the group's own height, keeping all three buttons within those edges.

Values outside 0–100 are clamped to the nearest endpoint. Empty or invalid text falls back to the top; the text field retains what was entered.

The mod uses Sine's standard settings controls and contains no JavaScript.

## Compatibility

Verified with **Zen 1.22.2b** and **Sine 2.3.4.1c** on Windows, including side and percentage changes during normal use. Other versions and platforms have not been verified.

If settings appear to do nothing immediately after installation, restart Zen once. Conflicting appearance mods and panels too short to fit the button group may affect positioning. Disabling this mod restores Zen's native layout.

## Credits

Inspired by psu's [Left Side Glance Buttons](https://github.com/psu/zen-mods). This standalone mod adds configurable side and percentage-based vertical positioning.

## License

[MIT](LICENSE).
