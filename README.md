Synthesia MIDI Conversion
=========================

Music, software and documents about conversion of various file formats into Synthesia MIDI files.


Download MIDI
-------------

* [Eric Thiman - Flood Time.mid](midi/Eric Thiman - Flood Time.mid?raw=true)
* [Unknown Author - Murka.mid](midi/Unknown Author - Murka.mid?raw=true)
* [Mikael Tariverdiev - Two in a Cafe](midi/Mikael Tariverdiev - Two in a Cafe.mid) (in progress)

Documentation
-------------

#### Finale 2014

Probably the best optical recognition software on the planet. Bad and very outdated user interface.

* Switch to Microsoft GS Wavetable Synth for clarity in `MIDI/Audio > Device setup > MIDI Setup`.

* `Space+Left Click` - play from the mouse position (most useful shortcut in Finale).

* Use `File > Import > TIFF File`, `Add files to list`. The rest will be done almost automatically.

* Midi for Synthesia (with left and right hand support) can be exported without any additional hustle.
Open `Window > Score Manager` switch to `Instrument List`, edit `Ch.` column (set 1 for left hand or 2 for right hand)
for each track, then just use `File > Export > MIDI File`, `Format 0` (without markers).

* Finale 2014 supports both TIF and BMP files (both greyscale and B/W bitmaps). I personally use single-page
LZW-compressed B/W TIFs at 150 DPI, because they are pretty small (use Levels tool from Photoshop to adjust brightness).

* Use `Measures` button and `Insert Measure Stack` in the context menu to insert missing bars.
Make sure all time signatures are correct. If bar slows down in the end, its duration may be wrong.
Reset bar to a proper timing (4/4, 2/4, etc.) using context menu of the `Time Signature Tool`.
To join bars use `Plug-ins > Measures > Merge measures`.

* Scary "red" notes after scanning is actually layer 2 (red is the default screen display colour for Layer 2 notes).
You may switch layers using `View > Select Layer` or `Shift+Alt+1`, `Shift+Alt+2`.

##### Finale 2014 Speedy Entry Shortcuts

Of course, it's absolutely necessary to use speedy entry to modify notes, it's much, much faster than "Simple Entry Tool".
Check out the help page on the Finale site: [speedy entry cheat sheet](http://www.finalemusic.com/usermanuals/finale2012mac/Content/Finale/Speedy_Entry.htm).

First of all, uncheck "Use MIDI device for input" in `Speedy > Speedy Options` to use keyboard.

* `T` - tie (draws arc from the current note to the next note)
* `1`...`8` - enter notes (`4` - eight note, `5` - quarter note, `6` - half note, etc.)
* `.` - dot (adds dot to the note)

#### MuseScore (FREE)

Free and very promising. Fixing scores seems easier. Uses terrible free audiveris OCR library (in the browser).
Modern editing, good buttons and shortcuts (Finale 2014 looks bad in comparison).

