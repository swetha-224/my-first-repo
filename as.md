```vega-lite
{
  "description": "A simple pie chart.",
  "data": {
    "values": [
      {"category": "A", "value": 40},
      {"category": "B", "value": 30},
      {"category": "C", "value": 20},
      {"category": "D", "value": 10}
    ]
  },
  "mark": "arc",
  "encoding": {
    "theta": {"field": "value", "type": "quantitative"},
    "color": {"field": "category", "type": "nominal"}
  },
  "view": {"stroke": null}
}
```