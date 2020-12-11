# meloomoto

In 2001 I created a website which was offering monophonic ringtones for compatible Motorola phones (V2288 and many others). It was my first serious website (and maybe second or third in general) and I was maintaining it up to 2003.

In December 2020 in a sudden influx of nostalgia I checked how much of it was still accessible on Web Archive. While the website itself is too incomplete to recover it, most of its content remained intact, so I decided to save it for memories.

The *ringtones* directory contains all ringtones I composed throughout whole lifespan of the project.

## How did it work?

In the early 2000s many Motorola phones featured a ringtone editor and allowed for using custom ringtones received via a text message. To set up a customized ringtone you had to do one of the following:

* compose it yourself in the editor
* use a premade ringtone from a website like mine and type it carefully into the editor
* use an online SMS gateway to send the ringtone to your phone as a text message

## How did I compose my own ringtone?

Let's look at a sample line:

``4 A1 E3 R2 E-2 R5 E#+2``

First digit indicates tempo. 1 is the slowest and 4 is the fastest.

Letters from A to G are actual music notes.

Plus sign (`+`) and minus sign (`-`) raise or lower a note by a semitone.

Hash (`#`) raises a note by an octave.

`R` indicates a pause.

Digits at the end of each note indicate its length. 1 is the shortest and 8 is the longest.

Each ringtone could contain a maximum of 35 notes.

To send a ringtone in a text message the ringtone had to be converted to SMS-compatible code with software called Motorola Ringer Tone Maker. The software was free to download from Motorola website.

## Licence

[Oh come on](https://raw.githubusercontent.com/lwojcik/meloomoto/master/LICENSE).
