___
[project info](readme.md) | [current-db-fields](current-db-fields.md)  |   [formats](formats.md) | [subjects](subjects.md)
___

#example.md

[github link](https://github.com/karlstolley/isr/tree/project-2)

[relational db to Mongo db tutorial](http://code.tutsplus.com/articles/mapping-relational-databases-and-sql-to-mongodb--net-35650)

### carol-s.json


```
{"relationship": "Mom",
    "name": "Carol S.",
    "uri": "carol-s.json",
    "spouse": "lynn-s.json",
    "hobbies": ["crocheting", "cooking", "iPad games"]
}
```

### index.json

```
[
   {"relationship": "Mom",
    "name": "Carol S.",
    "uri": "carol-s.json",
    "spouse": "lynn-s.json"},
   {"relationship": "Dad",
    "name": "Lynn S.",
    "uri": "lynn-s.json",
    "spouse": "carol-s.json"}
]
```