# French Irregular Verbs

A curated list of 60 French irregular verbs with present indicative conjugations in json.

## Example

Each entry in the json file follows this shape:

```json
{
  "infinitive": "Prendre",
  "english": "to take",
  "chinese": "拿",
  "present_indicative": {
    "je": "prends",
    "tu": "prends",
    "il": "prend",
    "nous": "prenons",
    "vous": "prenez",
    "ils": "prennent"
  },
  "importance": "essential"
}
```

## Curation notes

- Only present indicative forms are included
- Verbs are filtered for real-world frequency — archaic, literary, and overly niche verbs have been excluded
- Some verbs only have third-person forms (e.g. _Falloir_ → `il faut`, _Pleuvoir_ → `il pleut`)
- Around 2/3 are marked `essential` — these are the ones learners should prioritise. `medium` verbs are common enough to be useful but less urgent.

## License

MIT
