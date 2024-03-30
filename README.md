# Bible-kjv-1611

- This repository contains the original KJV 1611 Bible in JSON format.
- There are 80 books. Each book is a separate JSON file.
- Included is a JSON array of all 80 book names.
- Also included is a JSON array of book and chapter count pairs.

## Example JSON verse
As an example, this is Psalms 23 verse 1 in JSON format.

```
{
   "book": "Psalms",
   "chapter-count": "150",
   "chapters": [
      {
        .......
         "chapter": 23,
         "verses": [
            {
               "verse": 1,
               "text": "The Lord is my shepheard, I shall not want."
            },
            .....
         ]
      }
   ]
}
```

## Books.json

`Books.json` is a JSON array containing all the 80 books of the KJV 1611 Bible.

This is a sample of `Books.json`.

```
["Genesis", "Exodus", "Leviticus", "Numbers", ..., "Prayer of Manasseh", "1 Maccabees", "2 Maccabees"]
```

## Books_chapter_count.json

`Books_chapter_count.json` is a JSON 2D array containing an array of (book, chapter-count) pairs of all the 80 books of the KJV 1611 Bible.

This is a sample of `Books_chapter_count.json`.

```
[["Genesis", 50], ["Exodus", 40], ["Leviticus", 27], ["Numbers", 36], ..., ["1 Maccabees", 16], ["2 Maccabees", 15]]
```

