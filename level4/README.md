# Intro

Now that we've exposed the tree, we want to expose the historical search volume of any category. Remember that the metric is only associated with leaf categories. For non-leaf categories, the metric is the aggregation of the metrics of its descendants.

# Level 4 - Expose the historical search volume

Implement a new endpoint that displays the average monthly search volume over the last 24 months of a single category, at any level of the tree, that satisfies the following schema:

```json
{
  "category": {
    "id": 274714,
    "name": "Chocolate candy and praline"
  },
  "averageMonthlyVolume": 799705
}
```

# Bonus

Surprise us! Add a feature that you think would work well here.
