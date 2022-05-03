# Справка по оформлению

Немного **текста**!

$$
e = mc^2
$$ (eqn:best)

This is the best equation {eq}`eqn:best`

```{admonition} Внимание
:class: warning

Текст вставки
```
текст

```{epigraph}
Here's my quote, it's pretty neat.
I wonder how many lines I can create with
a single stream-of-consciousness quote.
I could try to add a list of ideas to talk about.
I suppose I could just keep going on forever,
but I'll stop here.

-- Jo the Jovyan, *[the jupyter book docs](https://jupyterbook.org)*
```

текст

```javascript
var borders = ee.FeatureCollection("projects/buryatia-changedetection/assets/BURborders");
var mgrs = ee.FeatureCollection("projects/buryatia-changedetection/assets/BURMGRS");
// var fcover = ee.Image("users/avvaler/PKraiForestMask");
var fmask = ee.ImageCollection("NASA/MEASURES/GFCC/TC/v3")
  .filterMetadata('year','equals',2015)
  .filterBounds(borders)
  .select('tree_canopy_cover')
  .max()
```

текст

текст

текст

```{margin} Look, some margin content!
On wider screens, this content will pop out to the side!
```

текст

текст

текст

текст