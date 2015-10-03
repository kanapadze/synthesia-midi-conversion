Synthesia MIDI Conversion
=========================

Music, software and documents about conversion of various file formats into Synthesia MIDI files.


Download MIDI
-------------

* [Eric Thiman - Flood Time.mid](midi/Eric Thiman - Flood Time.mid?raw=true)
* [Unknown Author - Murka.mid](midi/Unknown Author - Murka.mid?raw=true)

Documentation
-------------

#### Finale 2014

Probably the best MIDI editor on the planet, Includes **very** high quality sheet music OCR software.

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

