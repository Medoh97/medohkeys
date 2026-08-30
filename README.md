# MedohKeys

A piano and guitar practice app for Android.

## Install

Download the APK from [`dist/`](dist/) and open it on your phone or tablet.
Android will ask you to allow installing from this source; that is expected for
an app that does not come from the Play Store.

Once it is installed it keeps itself up to date: **Settings -> Check for
updates** pulls the newest build from this repository.

## What is in it

- Sheet music and falling-note views, with adjustable tempo and a metronome
- A fingering worked out for scores that do not print one, shown on the staff
- Hands that play along, on the keyboard and on the guitar neck
- Listens to a MIDI keyboard over USB or Bluetooth
- Can send the song out to a MIDI piano, so the piano plays it rather than the phone
- Guitar side: tab, fretboard, chord library and tuner

## The music

Sixty-six scores are included, all of works in the public domain -- Bach,
Beethoven, Brahms, Chopin, Debussy, Liszt, Mozart, Pachelbel, Satie, Schubert,
Joplin, Tchaikovsky and others.

The *compositions* are long out of copyright. The transcriptions were made by
other people and are included on that basis; if you are the author of one and
would rather it were not here, open an issue and it will be removed.

You can import your own MusicXML (`.musicxml`, `.xml`, `.mxl`), MIDI (`.mid`)
and PDF sheet music.

A MIDI file records what was played, not how it was written down, so anything
imported from one is worked out rather than read: which hand plays what comes
from the file's tracks where it separates them and from pitch where it does
not, sharps and flats are chosen by the key signature, and note values are
rounded to the nearest written one. MusicXML carries all of that properly and
is the better import where you have the choice.

## Feedback

Open an issue. Say what you were doing, what happened, and what you expected --
and which device, since the app is mostly tested on a Galaxy Tab S8+.
