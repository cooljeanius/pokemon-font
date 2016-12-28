# pokemon-font 1.5.0
#### Original GAME BOY Pokemon font, unicode extended.

## What is it
This font is an extended clone of the original font shipped with Pokemon Red, Green, Blue and Yellow in the 90's. It was made into a proper font because it was needed for [Pokemon-Mini](https://github.com/Superpencil/Pokemon-Mini).

## Live Preview
Preview of webfonts available here:  [http://pascalpixel.com/pokemon-font/](http://pascalpixel.com/pokemon-font/).
This Readme file contains images of the glyphs to substitute for not having webfonts on Github.

## Features
### Latin
The latin character set has been extended to support the first three Unicode blocks, Basic Latin, Latin-1 Supplement and Latin Extended-A. This covers most West European languages. Some of the original glyphs have been changed for harmony with the added new glyphs.

###### Ligatures
There is a ligature to get the original <sup>P</sup><sub>K</sub><sup>M</sup><sub>N</sub> glyph, plainly write this string: `PKMN` in capitals without spaces and it will be replaced.

There are also the original games' ligatures for `'d`, `'l`, `'m`, `'r`, `'s`, `'v` and `'t`. Sadly, `'a`, `'c`, `'p` and `'n` don't have ligatures, so y'all, o'clock, s'pose or cap'n will look dull. Don't write those words.

###### Added Glyphs
A ton, to support the aforementioned Unicode blocks.

![Alt text](/img/Latin.png?raw=true "pokemon-font Latin Glyphs")

### Punctuation & Mathmatical
For all my nerdy trainers out there, these characters are extended as well to support common programming languages. So go ahead and load this up in your favorite editor.

###### MissingNo
If the font doesn't support a certain character, � is displayed, in this font that is a MissingNo ![Alt text](/img/MissingNo.png?raw=true "pokemon-font Font MissingNo Glyph"), because a tiny MissingNo is sugoi kawaii.

###### Added Glyphs
$, @, \\ and weird stuff like ~ \` ^.

![Alt text](/img/Punctuation.png?raw=true "pokemon-font Font Punctuation Glyphs") ![Alt text](/img/Mathmatical.png?raw=true "pokemon-font Font Mathmatical Glyphs")

### Unown
To type Unown, you must use one of the formats that supports ligatures. These little living glyphs might attack though. So be ready.

![Alt text](/img/Unown.png?raw=true "pokemon-font Font Unown Glyphs")

###### Ligatures
To write in Unown, prepend each basic alphabet character with an @.
> @y@o@u @c@a@u@g@h@t @a@l@l @t@h@e @u@n@o@w@n @v@a@r@i@a@t@i@o@n@s? @t@h@a@t @i@s @a @g@r@e@a@t @a@c@h@i@e@v@e@m@e@n@t!

### Japanese
I extended support to cover the full Unicode blocks for Hiragana and Katakana, which holds a few obscure characters that aren't used anymore, but gotta catch 'em all right?

![Alt text](/img/Japanese.png?raw=true "pokemon-font Font Japanese Glyphs")

## What I learned
While making this font I learned how to create SVG shapes with raw code, how modern fonts are encoded, how to convert between font formats, how to deal with size, kerning, ligatures, etc. This is also the first time I'm publishing a package to `npm` and `bower`.

Contact me on Twitter or Github: [@PascalPixel](http://twitter.com/pascalpixel). I'm very happy to have contributions/PR's to this repository!

I used [Glyphs App](https://glyphsapp.com) in the end to manage the `.ufo` master 'file'/folder.

## Supported Characters
Here's the full table of characters that are supported in the font right now.

###### C0 Controls and Basic Latin
 |0|1|2|3|4|5|6|7|8|9|A|B|C|D|E|F
-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-
U+002x| |!|"|#|$|%|&|'|(|)|*|+|,|-|.|/
U+003x|0|1|2|3|4|5|6|7|8|9|:|;|<|=|>|?
U+004x|@|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O
U+005x|P|Q|R|S|T|U|V|W|X|Y|Z|[|\|]|^|_
U+006x|`|a|b|c|d|e|f|g|h|i|j|k|l|m|n|o
U+007x|p|q|r|s|t|u|v|w|x|y|z|{|&#124;|}|~|

###### C1 Controls and Latin-1 Supplement
 |0|1|2|3|4|5|6|7|8|9|A|B|C|D|E|F
-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-
U+00Ax| |¡|¢|£|¤|¥|¦|§|¨|©|ª|«|¬| |®|¯
U+00Bx|°|±|²|³|´|µ|¶|·|¸|¹|º|»|¼|½|¾|¿
U+00Cx|À|Á|Â|Ã|Ä|Å|Æ|Ç|È|É|Ê|Ë|Ì|Í|Î|Ï
U+00Dx|Ð|Ñ|Ò|Ó|Ô|Õ|Ö|×|Ø|Ù|Ú|Û|Ü|Ý|Þ|ß
U+00Ex|à|á|â|ã|ä|å|æ|ç|è|é|ê|ë|ì|í|î|ï
U+00Fx|ð|ñ|ò|ó|ô|õ|ö|÷|ø|ù|ú|û|ü|ý|þ|ÿ

###### Latin Extended-A
 |0|1|2|3|4|5|6|7|8|9|A|B|C|D|E|F
-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-
U+010x|Ā|ā|Ă|ă|Ą|ą|Ć|ć|Ĉ|ĉ|Ċ|ċ|Č|č|Ď|ď
U+011x|Đ|đ|Ē|ē|Ĕ|ĕ|Ė|ė|Ę|ę|Ě|ě|Ĝ|ĝ|Ğ|ğ
U+012x|Ġ|ġ|Ģ|ģ|Ĥ|ĥ|Ħ|ħ|Ĩ|ĩ|Ī|ī|Ĭ|ĭ|Į|į
U+013x|İ|ı|Ĳ|ĳ|Ĵ|ĵ|Ķ|ķ|ĸ|Ĺ|ĺ|Ļ|ļ|Ľ|ľ|Ŀ
U+014x|ŀ|Ł|ł|Ń|ń|Ņ|ņ|Ň|ň|ŉ|Ŋ|ŋ|Ō|ō|Ŏ|ŏ
U+015x|Ő|ő|Œ|œ|Ŕ|ŕ|Ŗ|ŗ|Ř|ř|Ś|ś|Ŝ|ŝ|Ş|ş
U+016x|Š|š|Ţ|ţ|Ť|ť|Ŧ|ŧ|Ũ|ũ|Ū|ū|Ŭ|ŭ|Ů|ů
U+017x|Ű|ű|Ų|ų|Ŵ|ŵ|Ŷ|ŷ|Ÿ|Ź|ź|Ż|ż|Ž|ž|ſ

###### Hiragana
 |0|1|2|3|4|5|6|7|8|9|10|11|12|13|14|15
-|-|-|-|-|-|-|-|-|-|-|--|--|--|--|--|--
U+304x|　|ぁ|あ|ぃ|い|ぅ|う|ぇ|え|ぉ|お|か|が|き|ぎ|く
U+305x|ぐ|け|げ|こ|ご|さ|ざ|し|じ|す|ず|せ|ぜ|そ|ぞ|た
U+306x|だ|ち|ぢ|っ|つ|づ|て|で|と|ど|な|に|ぬ|ね|の|は
U+307x|ば|ぱ|ひ|び|ぴ|ふ|ぶ|ぷ|へ|べ|ぺ|ほ|ぼ|ぽ|ま|み
U+308x|む|め|も|ゃ|や|ゅ|ゆ|ょ|よ|ら|り|る|れ|ろ|ゎ|わ
U+309x|ゐ|ゑ|を|ん|ゔ|ゕ|ゖ|　|　|゙　|゚　|゛|゜|ゝ|ゞ|ゟ

###### Katakana
 |0|1|2|3|4|5|6|7|8|9|10|11|12|13|14|15
-|-|-|-|-|-|-|-|-|-|-|--|--|--|--|--|--
U+30Ax|゠|ァ|ア|ィ|イ|ゥ|ウ|ェ|エ|ォ|オ|カ|ガ|キ|ギ|ク
U+30Bx|グ|ケ|ゲ|コ|ゴ|サ|ザ|シ|ジ|ス|ズ|セ|ゼ|ソ|ゾ|タ
U+30Cx|ダ|チ|ヂ|ッ|ツ|ヅ|テ|デ|ト|ド|ナ|ニ|ヌ|ネ|ノ|ハ
U+30Dx|バ|パ|ヒ|ビ|ピ|フ|ブ|プ|ヘ|ベ|ペ|ホ|ボ|ポ|マ|ミ
U+30Ex|ム|メ|モ|ャ|ヤ|ュ|ユ|ョ|ヨ|ラ|リ|ル|レ|ロ|ヮ|ワ
U+30Fx|ヰ|ヱ|ヲ|ン|ヴ|ヵ|ヶ|ヷ|ヸ|ヹ|ヺ|・|ー|ヽ|ヾ|ヿ
