### Build Log
- Build Time: 2025-11-20 20:00:43 UTC
- Source Commit: dcefaa659eaecb1a1bc78e25b5431b872879cba4
- Build Target: contents

### private-build-plans.toml
```toml
[buildPlans.IosevkaCustom]
family = "Iosevka Custom"
spacing = "fontconfig-mono"
serifs = "slab"
noCvSs = true
exportGlyphNames = false

  [buildPlans.IosevkaCustom.ligations]
  inherits = "dlig"

[buildPlans.IosevkaCustom.weights.Regular]
shape = 400
menu = 400
css = 400

[buildPlans.IosevkaCustom.weights.Light]
shape = 300
menu = 300
css = 300

[buildPlans.IosevkaCustom.widths.Normal]
shape = 456
menu = 5
css = "normal"

[buildPlans.IosevkaCustom.slopes.Upright]
angle = 0
shape = "upright"
menu = "upright"
css = "normal"

[buildPlans.IosevkaCustom.slopes.Italic]
angle = 9.4
shape = "italic"
menu = "italic"
css = "italic"
```
