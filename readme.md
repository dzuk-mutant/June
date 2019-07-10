![](preview.png)

## June

June is a high-resolution bitmap font with some playful curves and distinctive letterforms, inspired by portable game fonts of the 00's like Telegrama and GBA Pokémon games.

I made it to use in my own game concepts for the [Panic Playdate](https://play.date), as I didn't really find fonts that suited the size needs of the display or the kind of aesthetic I wanted. 

It's also probably applicable to other situations involving high-density, low colour depth displays.

It's currently in a prototype stage and is just a sprite sheet with some alignment guides right now. I want to get it encoded into a common format or two very soon.


### Aspects

- Full European Latin support, Japanese Kana support.
- 14px/~1.8mm baseline to ascender height for Latin, 14px/~1.8mm square height/width for CJK characters. (Essentially the same size as body text on iPhones)
- Borrows visual cues from  monospaced fonts to more clearly distinguish certain similar Latin characters (ie. I/i/1/l).


### Character areas supported:

- Unicode Basic Latin / ASCII (full)
- Unicode Latin-1 Supplement (most)
- Unicode Latin Extended-A (full)
- Unicode Hiragana (full)
- Unicode Katakana (full)
- Japanese Punctuation
- Full-Width Latin (most)
- Full-Width Latin Punctuation (some)
- Playdate input icons in two sizes (one to fit Latin characters better, the other to fit CJK characters, I'll probably revise this in the future)


### Todo:

- Get the font encoded into a common format or two (BMFont is something I'd definitely like to do if possible)
- Finish Japanese punctuation and Full-Width Latin
- Give all the characters a thorough testing
- Do some other symbols (smileys, hearts, etc.)
- Consider supporting a segment of the most used Kanji.


### License

This font is licensed under the [zlib license](license.txt) (it's basically like MIT).



### Special thanks

- kiilas for checking over the Central European accented characters for me.
- Someone on Mastodon for figuring out [what display the Playdate uses](https://www.sharpsma.com/products?sharpCategory=Memory%2520LCD&p_p_parallel=0&sharpProductRecordId=1504552), which helped me definitively figure out how big the font would be on a real Playdate.