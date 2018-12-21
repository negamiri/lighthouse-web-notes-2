# Day 3 notes

## Morning: Objects in JS

```js
[] // array object
() // string object
{} // empty object
```

Objects = key value pairs

* primatives
  - Booleans
  - Number
  - String
  - Undefined
  - Null
  - Symbols (es 6)

truthy = something that javascript recognizes as true
falsy = 0, undefined, null, empty string, false, null, NaN

* valid identifiers
  - Site to check
  - invalid: numbers, start with exclamation
  (invalid identifiers can be used as objects)

* objects
  - key/property can be used interchangeably

Method = function of an object

var stuff = 'thing'
vs.
stuff = 'thing'
--> 2nd creates a global variable that can be accessed from any file anywhere

## Compass work

``` javascript

  const { name, artist, album } = libTracks[trackid];

  is the same as
  var trackName = libTracks[trackid].name
  var trackArtist = libTracks[trackid].artist
  var trackAlbum = libTracks[trackid].album

