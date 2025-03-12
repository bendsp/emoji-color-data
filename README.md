# Emoji Color Data

This repository contains a [structured JSON dataset of emojis](./emojis.json)

It was compiled while working on [typeArt](https://typeart.desprets.net/) upon realizing no such dataset was easily accesible.

## 📂 Dataset Structure

Each emoji entry in the emojis.json file includes the following fields:
- `emoji`: The actual emoji character.
- `name`: A descriptive name for the emoji.
- `unicode`: The Unicode representation.
- `hex`: The average hex color of the emoji.
- `rgb`: The corresponding RGB color values.
- `area`: A numerical ratio representing the relative area coverage of the dominant color, from 0 to 1.

## 📝 Sample

```json
{
    "emoji": "☁️",
    "name": "cloud",
    "unicode": "U+2601 U+FE0F",
    "hex": "#E3E7EB",
    "rgb": [227, 231, 235],
    "area": 0.4783782958984375
  },
  {
    "emoji": "☂️",
    "name": "umbrella",
    "unicode": "U+2602 U+FE0F",
    "hex": "#884ECF",
    "rgb": [136, 78, 207],
    "area": 0.3159027099609375
  },
  {
    "emoji": "☃️",
    "name": "snowman",
    "unicode": "U+2603 U+FE0F",
    "hex": "#A4AEB5",
    "rgb": [164, 174, 181],
    "area": 0.631317138671875
  }
```

## 📜 License

This dataset is provided under the MIT License. Feel free to use and modify it for your projects.
