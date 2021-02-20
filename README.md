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

## Defining Texts

```
"extensions": {
    "EXT_text": {
        "texts": [
            {
                "text": "Hello glTF!",
                "fonts": ["Arial", "Times New Roman"],
                "size": 1.0,
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

| Property | Description | Requires |
|:------|:------|:------|
|`text`| | Yes |
|`fonts`| | No |
|`size`| | No |
