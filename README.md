# ribbon-light

A fork of [ribbon](https://github.com/robonuggets/ribbon) by Jay E that also works in light mode.

It's the same band above the prompt: how much of the 5-hour and 7-day usage is left, when each resets, and whether the prompt cache is warm or cold.

What changed compared with ribbon:

- The band's text uses theme colours, so it follows the light and dark themes.
- The band and the cache card have no hardcoded dark background.
- The SVG drawings swap to a light palette under `prefers-color-scheme: light`.

Turn off the original ribbon if you have it, so you don't get two bands.

## Install

At the prompt of a terminal session:

```
/plugin install ribbon-light --marketplace fureya/ribbon-light
```

Answer `y` to add the marketplace, then pick a scope.

From a shell:

```bash
claude plugin install ribbon-light --marketplace fureya/ribbon-light
```

In the desktop app, where `/plugin` doesn't run: click + next to the prompt box, then Plugins, Add marketplace with `fureya/ribbon-light`, then Add plugin.

## License

MIT, like the original. See [LICENSE](LICENSE).
