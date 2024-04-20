# Twitch Now(Personal update + Features Fork)

## Requirements

* Node.js
* Gulp

## Current new features

- Fixed settings menu that properly saves text fields
- A new field that allows blocking specific Games/Categories (Even followed streamers do not appear in the list if they stream a blacklisted category)
- A more verbose notification text, now shows the category alongside the streamers name.

## How to build

Before all, you need to install dependencies:
```
$ npm install
```

To build Chrome version:
```
$ gulp chrome
```

To build Firefox version:
```
$ gulp firefox
```

To run Firefox version:
```
$ run firefox, goto about:debugging, then load build/firefox/manifest.json
```

To build Opera version:
_Not tested but should work as it uses the same build mechanism as everything else._
```
$ gulp opera
```