![](preview_regular.png)

![](preview_condensed.png)

## June

June is a multilingual, high-resolution bitmap font with some playful curves and distinctive letterforms, inspired by portable game fonts of the 00's.

It's intended to be highly legible and readable - ideal for contexts like dialogue.

I made it to use in my own game concepts for the [Panic Playdate](https://play.date), as I didn't really find fonts that suited the size needs of the display or the kind of aesthetic I wanted. 

It's also probably applicable to other situations involving high-density, low colour depth displays.

It's currently in a prototype stage, I'd like to get it encoded in a format or two very soon.

---


### Aspects, Features + Limitations

- Two versions - regular and condensed.
- On a Playdate screen, it's estimated to be about 14px/~1.8mm baseline to ascender height for Latin, 14px/~1.8mm square height/width for CJK characters. (Essentially the same size as body text on iPhones)
- Borrows visual cues from  monospaced fonts to more clearly distinguish certain similar Latin characters (ie. I/i/1/l).
- Currently, Japanese characters have only been designed/framed to be written in horizontal writing orientation so they can be typed alongside the rest of June's characters in a seamless way.

----

### Supported Unicode character areas

#### Regular

- Basic Latin / ASCII (full)
- Latin-1 Supplement (full)
- Latin Extended-A (full)
	- (excluding the depreciated U+0149 character)
- Cyrillic (Russian and some others)
- Hiragana (full)
- Katakana (full)
- Fullwidth and Halfwidth Letterforms (some)
	- All Fullwidth ASCII characters + Japanese punctuation
- CJK Symbols and Punctuation (some)


#### Condensed

- Basic Latin / ASCII (full)
- Latin-1 Supplement (full)
- Latin Extended-A (not yet)

If you wanted, you could mix and match June Condensed Latin with June Regular CJK characters.


#### Other WIP (src/regular/june_wip.ase)
- Playdate input icons

---

### Todo:

- Get the font encoded into a format or two
- Declare kerning pairs
- Add € and some other useful signs not covered by the blocks I've done so far
- Keep testing
- Do some other symbols (smileys, hearts, etc.)
- Consider supporting a segment of the most used and least complex Kanji

---

### License

This font is licensed under the [zlib license](license.txt) (it's basically like MIT).

---

### Special thanks

- kiilas for checking over the Central European accented and Cyrillic characters for me.
- Someone on Mastodon for figuring out [what display the Playdate uses](https://www.sharpsma.com/products?sharpCategory=Memory%2520LCD&p_p_parallel=0&sharpProductRecordId=1504552), which helped me definitively figure out how big the font would be on a real Playdate.