# Still

A dark and light color theme for Zed, with cohesive UI surfaces and syntax colors based on JetBrains Themes.

| Theme | Background | Appearance |
| --- | --- | --- |
| Still Dark | `#010101` | Near-black surfaces with a distinct active tab |
| Still Light | `#F7F8FA` | Soft-white surfaces with a distinct active tab |

Both themes use opaque backgrounds. Each variant retains the corresponding JetBrains syntax highlighting and terminal ANSI palette.

## Local installation

To test the complete extension, open the Extensions page in Zed, click **Install Dev Extension**, and select this repository's root directory. Then select **Still Dark** or **Still Light** in the theme selector.

To load only the theme JSON on macOS or Linux:

```sh
mkdir -p ~/.config/zed/themes
cp themes/still.json ~/.config/zed/themes/
```

If the themes do not appear immediately, restart Zed.

## Automatic appearance switching

Add this to your Zed settings:

```json
{
  "theme": {
    "mode": "system",
    "light": "Still Light",
    "dark": "Still Dark"
  }
}
```

## License and credits

Apache-2.0. See [LICENSE.txt](LICENSE.txt) and [NOTICE.txt](NOTICE.txt).

Based on [JetBrains Themes for Zed](https://github.com/artemevsevev/zed-theme-jetbrains) by Artem Evsevev. Still customizes the UI palettes and interaction states.
