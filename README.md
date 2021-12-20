<p align="center">
  <img src="https://user-images.githubusercontent.com/6678/142731484-c654c002-a4c6-4664-b44d-634c8bc5dbcf.png" />
</p>

---

Alpha Lyrae is a typeface that personalises the innovative mindset of VEGA. 

It shows the cutting-edge impact on the trading process and the arising freedom unlocked by the power of blockchain technology. Unlike the calm horizontal terminals of the well-known Helvetica, our first proposal visualises terminal cuts following the natural stroke of the letters. This allows a significant increase in the letter apertures for efficient legibility. Moreover, it hints at the inclusiveness and transparency of this novel invention to the community across the world. Another noteworthy feature is the emphasised edgy terminals. They stir the classic appearance of Helvetica associated with old-fashioned concepts of many financial institutions out there and challenge us to think beyond the status quo. It’s safe to say, this proposal takes the best out of both worlds — the trustful reliable shapes of Helvetica and the critical rebellious ideas of modern visionaries.


# TECHNOLOGY

![lorem-ipsum](https://user-images.githubusercontent.com/6678/142731503-121cce41-3aec-41c6-b422-8fd28e997c00.png)


Alpha Lyrae was created with the font editor Glyphs App and was exported directly from there. Not text editor was used to compile or build the files.

Alpha Lyrae contains one basic set of sans serif glyphs as a default option and four other stylistic sets (SS01—SS05) with pixelated letters, numerals and punctuations:
- SS01 — the first pixelated set of letters with unique structure.
- SS02 — the second pixelated set of letters with unique structure. 
- SS03 — the glitched version of SS01.
- SS04 — the glitched version of SS02.
- SS05 — another pixelated set with displaced pixels for a feeling of motion.

There are seven sans serif ligatures and their respective pixelated representation, as SS01.
The selected ligatures follow the most frequent digraphs seen in the English language.

The main underlying feature is the CALT feature (contextual alternates) that is active be default in the mainstream software and environments. 
The CALT makes each fourth glyph (including the spaces and punctuations) change to SS01, which is the first pixelated set. When the space is the fourth one in position, there won’t be seen any visible difference in this particular space. Whenever the fourth letter is a part of a ligature, it gets changed also into pixelated ligature.

If the user wants to access the pixelated ligatures at certain place they can be accessed also as discretionary ligatures (DLIG).


When a letter appears to be fourth (hence SS01) and if there is another SS01 version of it in the following 5 letters it will be changed into SS02. 
This counts for all the Extended Latin letters whose shape is similar to those in Basic Latin. So Æ Ǽ Ø Ǿ Œ Þ ẞ ð ø ǿ œ þ ß (AE AEacute Oslash Oslashacute OE Thorn Germandbls eth oslash oslashacute oe thorn germandbls germandbls.calt) won't be affected. 

The letters and OpenType classes are oderdered not as ABCD but as ETAO, following the frequency of most common letters appearing in the English language available here: http://pi.math.cornell.edu/~mec/2003-2004/cryptography/subs/frequencies.html

Otherwise, the stylistic sets are accessible via the options at the OpenType menu in Adobe CC softwares and also in web browsers.

When all letters are pixelated the lookup ”Scenario03” tries to bring variety. It converts each fourth pixelated glyph (if in SS01 or SS02) into a pixelated and displaced letter (SS05).


# Usage

## Web
Alpha Lyrae is avaialble in `.woff`, `.woff2` and `.eot` on the [release page](https://github.com/vegaprotocol/alpha-lyrae/releases).

## MacOS

### Using Font Book:
1. Download `AlphaLyrae-Medium.ttf` from the [release page](https://github.com/vegaprotocol/alpha-lyrae/releases).
2. Open the "Font Book" application.
3. In the main menu, select File, then Add Fonts...
4. Find the "Alpha Lyrae" font in your Downloads folder and press the Open button.

### Using Finder:
1. Download `AlphaLyrae-Medium.ttf` from the [release page](https://github.com/vegaprotocol/alpha-lyrae/releases).
3. Press `cmd-shift-G` in Finder and go to: `~/Library/Fonts`
4. Delete any existing "Alpha Lyrae" files
5. Paste the font file

## Windows
1. Download `AlphaLyrae-Medium.ttf` from the [release page](https://github.com/vegaprotocol/alpha-lyrae/releases).
2. Right-click on the font in your Download folder and choose "Install for all users".

If you have a previous installation of Alpha Lyrae, you should make sure
to remove those fonts files before installing new ones. You need to
install the font for all users, as some software requires fonts to be
global.

Once you have successfully installed the files you will need to enable it in whatever Windows application you're using.

### MS Word
1. Click on the popout button in the bottom right of the 'Font' section of the toolbar OR right click anywhere on the page and select 'Font'
2. Click on 'Advanced'
3. Tick the box labelled 'Use Contextual Alternates' - pixellated ligatures will now be used automatically

You can also manually switch between the sets using the Stylistic Sets menu.

### MS Powerpoint
TBC


## Linux
There are many different Linux distributions and some handle font management
differently. These instructions are for the most common Linux distributions:

1. Create a folder called ".fonts" in your home directory.
   Example: `mkdir -p ~/.fonts`
2. Copy `AlphaLyrae-Medium.otf` from the [release page](https://github.com/vegaprotocol/alpha-lyrae/releases) into your `.fonts` directory
   Example: `cp "AlphaLyrae-Medium.otf" ~/.fonts/`

You may have to restart apps and/or your window server session.

Again, these instructions are for the most common Linux distributions like
Ubuntu and might not apply to you. Refer to the documentation for your
distribution for more details on how to manage fonts in your OS.

**Q: I installed the fonts but they don't show up**

**A:** Try rebuilding the font database:
   `sudo fc-cache -f -v`
   Then restart your program(s).

**Q: Is there a way to tell if Alpha Lyrae was actually installed?**

**A:** Try running: `fc-list | grep "Alpha Lyrae"`

**Q: `~/.fonts` is an old thing. The new thing is `~/.local/share/fonts`**

**A:** Yes, that is true for recent distributions. These distros usually support
   `~/.fonts` as well making these instructions work for everyone. Yay.

--- 

![multi-lyrae](https://user-images.githubusercontent.com/6678/142732686-a662004e-5be6-4bff-b043-e01d89f2ca90.png)

--- 

Alpha Lyrae was designed by [fontfabric](https://www.fontfabric.com)

# Playground
You can try out the fonts online at [vegaprotocol.github.io/alpha-lyrae](https://vegaprotocol.github.io/alpha-lyrae).

# License
See [LICENSE.md](./LICENSE.md)


