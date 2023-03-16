OIS-01 - Playlists
--------------------

Specification of playlist object

## Fields


| Key   |      Value      |  Description | Required | Example |
|----------|:-------------:|------------:|---------:|---------:
| ois_id   | 1             | OIS kind for playlists | true | 1|
| name | text   |   Name for playlist | false  | Awesome Jazz |
| description | text | Description of playlist | false | My awesome playlist |
| songs | array | Array of songs | true | [] See below |


### Song format

| Key   |      Value      |  Description | Required | Example |
|----------|:-------------:|-------------:|--------:|---------|
| author   | text             | Author of song | false | Julian Lage |
| song | text   | Name of song | true  | I'll be seeing you |
| description | text | Description of song | false | Live in LA |


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
    }
  ]
}
```
