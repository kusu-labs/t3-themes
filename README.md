# T3 Code themes

Themes for [T3 Code](https://github.com/pingdotgg/t3code) that restyle the whole app, not just its colours: frames, labels, type and small working signals, each built from one reference image.

## Recon

Near-black space, dim olive hairlines and one acid yellow-green accent. While the agent works, a 2 px line sweeps along the composer's top edge.

![Recon in T3 Code](recon/screenshots/thread.png)

More screenshots and details: [recon/](recon/README.md).

## Install

Checked on T3 Code 0.1.12, desktop app on macOS. Themes restyle the web and desktop apps, not mobile.

**Full install, with the film-grain texture.** Copy two files into T3's themes folder and switch to the theme:

```sh
git clone https://github.com/kusu-labs/t3-themes.git
mkdir -p ~/.t3/userdata/themes
cp t3-themes/recon/theme.json ~/.t3/userdata/themes/recon.json
cp t3-themes/recon/background.png ~/.t3/userdata/themes/recon.png
~/.t3/bin/t3 theme set recon
```

If you set a different T3 data folder (`T3CODE_HOME` or `--base-dir`), use its `userdata/themes` instead.

**Quick install, without the texture.** In T3 Code, open Settings, Appearance, Add theme, and choose `recon/theme.json` (or paste its contents). Everything works except the grain.

**Undo.** Pick another theme in Settings, Appearance, or run `~/.t3/bin/t3 theme set t3-code`.

## Credits

- Font: Michroma, by The Michroma Project Authors, under the SIL Open Font License 1.1 ([OFL.txt](recon/OFL.txt)). The theme embeds a subset.

## Licence

The theme files are MIT ([LICENSE](LICENSE)). The embedded Michroma font stays under the OFL.
