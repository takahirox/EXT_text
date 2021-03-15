# EXT\_text

## Contributors

* Diego F. Goberna, Embark Studios, [@feiss](https://github.com/feiss)
* Takahiro Aoyagi, Mozilla, [@takahirox](https://github.com/takahirox)

## Status

Draft

## Dependencies

Written against the glTF 2.0 spec.

## Overview

T.B.D.

## Example screenshot

<img src="./screenshot.png" alt="Example screenshot" width="320">

## Defining Texts

```
"extensions": {
    "EXT_text": {
        "texts": [
            {
                "text": "Hello glTF!",
                "fonts": ["Arial", "Times New Roman"],
                "size": 1.0,
                "color": [1.0, 1.0, 1.0, 1.0]
            }
        ]
    }
}
```

## Adding Text instances to Nodes

```
"nodes": [
    {
        "extensions": {
            "EXT_text": {
                "text": 0
            }
        }
    }
]
```

## Text Types

| Property | Type | Description | Requires |
|:------|:------|:------|:------|
| `text` | `string` | Text content | :white_check_mark: Yes |
| `fonts` | `string` `[1-*]` | | No |
| `color` | `number` `[4]`| Text's RGBA font color | No, default: `[0,0,0,1]` |
| `size` | number| | No, default: `1.0` |
