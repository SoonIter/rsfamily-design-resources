# Rstack logo variants

SVG logo variants for Rspack, Rsbuild, Rslib, Rspress, Rsdoctor, Rstest,
Rslint, Rslim, and Rspeedy, exported from Figma on September 17, 2026.

| Directory | Variant | Source sizes | Filename |
| --- | --- | --- | --- |
| [`avatar`](./avatar) | Circular avatars with backgrounds | 32×32 | `<product>.svg` |
| [`website`](./website) | Website icons with backgrounds | 16×16, 32×32 | `<product>-16x16.svg`, `<product>.svg` |
| [`simplified`](./simplified) | System icons with transparent backgrounds | 16×16, 32×32 | `<product>-16x16.svg`, `<product>.svg` |

The three directories contain 45 icons. Each SVG retains its original
`viewBox` and omits fixed root dimensions so consumers can set the display size.
The 16×16 files preserve the separately exported small-size artwork.
Functional IDs have unique variant, product, and size prefixes so the icons
can be inlined together. Path precision, filters, gradients, masks, and clipping
are preserved.

The existing [`vscode`](./vscode) assets are separate and were not changed by
this Figma refresh.

![Preview of all 45 icons](../assets/rstack-logo-variants-preview.svg)

After deployment, each file is available from `https://assets.rspack.rs/` using
its repository path. For example:

```text
https://assets.rspack.rs/rstack/logos/avatar/rspack.svg
https://assets.rspack.rs/rstack/logos/website/rspack.svg
https://assets.rspack.rs/rstack/logos/website/rspack-16x16.svg
```
