# Athenaeum releases

Builds of Athenaeum, an app for the Mac and the iPhone that keeps your books from Kindle,
Goodreads, Pagebound and Fable in one library. The source code is private; this repository only
holds the releases.

## iPhone, through AltStore Classic or SideStore

[AltStore Classic](https://altstore.io) and [SideStore](https://sidestore.io) install apps from
outside the App Store by signing them with your own Apple ID. (AltStore PAL can't: it only installs
apps notarised by Apple for distribution in the EU.) Add this source, then install Athenaeum from it:

```
https://github.com/hugodelahousse/athenaeum-releases/releases/latest/download/altstore-source.json
```

With a free Apple ID, AltStore renews the app every week.

## Mac

Download `Athenaeum-<version>-mac.zip` from the [latest release](https://github.com/hugodelahousse/athenaeum-releases/releases/latest),
unzip it and move Athenaeum to Applications. Builds that aren't notarised yet have to be opened the
first time with Control-click → Open.

## Early days

Each device keeps a library of its own; they aren't shared yet. Sign in to each service inside the
app and it imports your books from there.
