# glockenspieler
Coding for Glockenspiel-playing LEGO robot - provided as-is without a lot of explanation or documentation, just as "it works for me".

The coding is written in NXC - [Not eXactly C](https://bricxcc.sourceforge.net/nbc/nxcdoc/nxcapi/intro.html) - inside of the old [Bricx Command Center IDE](https://bricxcc.sourceforge.net/).

More information can be found in my [German blog post](https://www.brickup.de/2023/glockenspieler) or my [English talk on the Wintergatan meetup](https://www.youtube.com/watch?v=1wKk3kyaDLg&t=16255s)

- chimes_main.nxc: Program running on the first NXT brick
- chimes_sub.nxc: Program running on the second NXT brick
- chimes_song_xxx.nxc: Programm to create the .dat file for a song on the first NXT brick (that gets read/played by the main program)
- chimes_note_writer.nxc: Repeated coding that gets included into the song programs
- chimes_note_constants.nxc: Repeated constants that get included into the main and the song programs

# Muse-Score-XML to NXC converter
The song-arrays can be generated using this handy [muse-xml-converter](https://github.com/brickup-de/glockenspieler-muse-converter) written by [@aerdev](https://github.com/EAR-Development)
