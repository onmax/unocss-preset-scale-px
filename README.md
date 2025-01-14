# UnoCSS Preset Scale PX

A UnoCSS preset that maps utility numbers directly to pixel values (e.g., `p-4` → `0.25rem(4px)`).

## Features

- 📏 1:1 Scaling – Utility numbers map directly to px values (p-4 → 4px).
- ⚡ Consistent Sizing – Simplifies spacing and sizing with predictable values.
- 🔧 Easy Integration – Plug-and-play with any UnoCSS project.

## Usage
```shell
pnpm i -D unocss-preset-scale-px
```

```ts
// uno.config.ts
import { defineConfig } from 'unocss'
import { presetScalePx } from 'unocss-preset-scale-px'

export default defineConfig({
  presets: [
    // ...
    presetScalePx(),
  ],
})
```

## Playground

You can open the [Unocss Playground](https://unocss.dev/play/#html=DwEwlgbgBAxgNgQwM5ILwCIAOBaALOgPgChgB6cCAoA&config=JYWwDg9gTgLgBAbwFBzgEwKYDNgDsMDCEuOA5gDQpxhQYDOGMAqrhJapjvgAq0MyUAvnCxQIIOAHIArqwDGdOpKRI5xOvFogASgFE4AXjgB6ABQBaAPwBtAHQAdNAF0A1AEotx0irW4N1PkYAZTkAQwAbDG4AD0N0bDwowJhTUwB9CDAYYHU4hEE3QwA%2BRCpaGGkoXFLUVFxQkAwALilZCAU6cxp6RnM6MMiu6Ml2WsgNGnb6OhbTaWzwwoMS5Fra3zoISNtwiFJTBHngcIKqNeAsOFMAQiPw2wxcGChgejgAH3e4GABPMAwIJc7g8ni96LYsNBdKE5AALODXAxGSRYWRybLESRuM5rODlSq4FS4uDAx7PV50SwQqEw2GpYBLFY4tYbeAANwi0gwcWA1gAjE5mbULldfv9AXAOeEuYYkVINC9cKRJHAAGSqvEYHS6WwwegpKVctzY4nnflOOKGjC2WhgcIwjCmLR6chXNKusB8xlwAAGABIEJ6THAACyCLQ%2Bk2405rQSjQRIU5IDDRSCweJYULScLwTiJIgkYD7VYBHowGZwazdfgsCCmNwe5IhCJRaL1wUFIA&css=PQKgBA6gTglgLgUzAYwK4Gc4HsC2YDCAyoWABYJQIA0YAhgHYAmYcUD6AZllDhWOqgAOg7nAB0YAGLcwCAB60cggDYIAXGBDAAUKDBi0mXGADe2sGC704AWgDuCGAHNScDQFYADJ4Dc5sAACtMLKAJ5gggCMLPK2ABR2pPBIcsoAlH4WAEa0yADWTlBYqEw2yFjK3Bpw5LxxAOTllVDoYpSMYgAs3vUZ2gC%2BmsBAA&options=N4IgLgTghgdgzgMwPYQLYAkyoDYgFwJTZwCmAvkA&version=65.4.0)

## License

[MIT](./LICENSE) License © 2023 [zyyv](https://github.com/zyyv)

## Credits

- [unocss](https://github.com/unocss/unocss)
- [preset-starter](https://github.com/unocss-community/unocss-preset-starter)
