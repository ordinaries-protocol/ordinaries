OIS-01 - Playlists
--------------------

Specification of playlist object

## Fields


| Key   |      Value      |  Description | Required | Example |
|----------|-------------|------------|---------|---------|
| ois_id   | 1             | OIS kind for playlists | true | 1|
| name | text   |   Name for playlist | false  | Awesome Jazz |
| description | text | Description of playlist | false | My awesome playlist |
| songs | array | Array of songs | true | [] See below |


### Song format

| Key   |      Value      |  Description | Required | Example |
|----------|-------------|-------------|--------|---------|
| author   | text             | Author of song | false | Julian Lage |
| song | text   | Name of song | true  | I'll be seeing you |
| description | text | Description of song | false | Live in LA |
| cover | ordinal id | An ordinal id referring to an image | false | 58030e24...d92fd3i0 |
| audio | ordinal id | An ordinal id referring to an audio file | false | 58030e24...d92fd3i0 |


## Create a playlist
```
{
  "ois_id": 1,
  "name": "Awesome Jazz",
  "description": "Listen to my favourite songs",
  "songs": [
    {
      "author": "Julian Lage",
      "song": "I'll Be Seeing You",
      "description": "Live in LA"
      "cover": "58030e24935cb01b7c3ab1cc68ac9d086c40b5398a4db2a702a3165af6d92fd3i0"
      "audio": "58030e24935cb01b7c3ab1cc68ac9d086c40b5398a4db2a702a3165af6d92fd3i0"
    }
  ]
}
```
