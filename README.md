# midi2wav
A simple Ruby script to convert MIDI file(s) to WAV file(s) using TiMidity++ as the backend.

## Usage
The usage is `midi2wav [FILE(S)]`.

## Notice
Your original file(s) won't be replaced. If you convert MIDI file(s) with `.mid` extension, you will get the WAV file(s) with `.wav` replacing the `.mid` of the original file(s) extension or else you will get WAV file(s) with `.wav` added to the end of its original filename. If you convert something that is not MIDI you will get an empty file with `.wav` extension with the name of your original filename added with `.wav` extension.

## No Liability
I'm not responsible of any damage the script may cause. You need to use this script at your own risk.
