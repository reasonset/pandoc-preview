# pandoc-preview

Preview markdown file with Pandoc and webview.

# Dependencies

* Zsh
* Yad (If `webview_cmd` is not set.)
* `stdbuf` (If `webview_cmd` is not set.)

# Install

* Copy `pandoc-preview` on your `$PATH`
* Copy `pandoc-preview.desktop` on `~/.local/share/applications/`

# Configuration

write `${XDG_CONFIG_HOME:-$HOME/.config}/reasonset/pandoc-preview.rc` or `${XDG_CONFIG_HOME:-$HOME/.config}/reasonset/pandoc-preview/pandoc-preview.rc` as zsh.

|param|description|
|-------|-------------------------|
|`pandoc_cmd`|Pandoc command. default is `pandoc`.|
|`webview_cmd`|Webview command-line array. If not set, use `yad` for preview.|
|`css`|URL of CSS file.|
|`yad_width`|Width of Yad.|
|`yad_height`|Height of Yad.|