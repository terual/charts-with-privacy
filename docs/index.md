# Charts with privacy

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "data": {"url": "data.json"},
  "mark": "bar",
  "encoding": {
    "y": {"field": "Language", "type": "nominal", "sort": "-x"},
    "x": {"field": "Coverage", "type": "quantitative"}
  }
}
```
