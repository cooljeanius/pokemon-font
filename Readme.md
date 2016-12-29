# pokemon-font v1.7.0
Github: [https://github.com/PascalPixel/pokemon-font](https://github.com/PascalPixel/pokemon-font)

## What is it
This font is an extended clone of the original font shipped with Pokemon Red, Green, Blue and Yellow for the _GAME BOY_ in the 90's. It was made into a proper font because it was needed for [Pokemon-Mini](https://github.com/Superpencil/Pokemon-Mini).

## Live Preview
Preview of webfonts available here:  [http://pascalpixel.com/pokemon-font/](http://pascalpixel.com/pokemon-font/).
This Readme file contains images of the glyphs to substitute for not having webfonts on Github.

## Features
### Latin
The latin character set has been extended to support the first three Unicode blocks, Basic Latin, Latin-1 Supplement and Latin Extended-A. This covers most West European languages. Some of the original glyphs have been changed for harmony with the added new glyphs.

#### Ligatures
##### PKMN
There is a ligature to get the original <sup>P</sup><sub>K</sub><sup>M</sup><sub>N</sub> glyph, plainly write this string: `PKMN` in capitals without spaces and it will be replaced with PKMN.

##### 'd 'l 'm 'r 's 'v 't
There are also the original games' ligatures for `'d`, `'l`, `'m`, `'r`, `'s`, `'v` and `'t`. Sadly, `'n` isn't supported cap'n.

#### Added Glyphs
A ton, to support the aforementioned Unicode blocks.

![Alt text](/img/Latin.png?raw=true "pokemon-font Latin Glyphs")

### Punctuation & Mathematical
For all my nerdy trainers out there, these characters are extended as well to support common programming languages. So go ahead and load this up in your favorite editor.

#### MissingNo
If the font doesn't support a certain character, � is displayed, in this font that is a MissingNo ![Alt text](/img/MissingNo.png?raw=true "pokemon-font Font MissingNo Glyph"), because a tiny MissingNo is sugoi kawaii.

#### Added Glyphs
$, @, \\ and weird stuff like ~ \` ^.

![Alt text](/img/Punctuation.png?raw=true "pokemon-font Font Punctuation Glyphs") ![Alt text](/img/Mathematical.png?raw=true "pokemon-font Font Mathematical Glyphs")

### Unown
To type Unown, you must use one of the formats that supports ligatures. These little living glyphs might attack though. So be ready.

![Alt text](/img/Unown.png?raw=true "pokemon-font Font Unown Glyphs")

#### Ligatures
To write in Unown, prepend each basic A-z alphabet character with the word `unown`.
If you write `unowna` and `unownz` the `a` and `z` Unown will be shown.
> unownyunownounownu unowncunownaunownuunowngunownhunownt unownaunownlunownl unowntunownhunowne unownuunownnunownounownwunownn unownvunownaunownrunowniunownaunowntunowniunownounownnunowns?
> unowntunownhunownaunownt unowniunowns unowna unowngunownrunowneunownaunownt unownaunowncunownhunowniunowneunownvunowneunownmunowneunownnunownt!

### Japanese
I extended support to cover the full Unicode blocks for Hiragana and Katakana, which holds a few obscure characters that aren't used anymore, but gotta catch 'em all right?

![Alt text](/img/Japanese.png?raw=true "pokemon-font Font Japanese Glyphs")

## What I learned
While making this font I learned how to create SVG shapes with raw code, how modern fonts are encoded, how to convert between font formats, how to deal with size, kerning, ligatures, etc. This is also the first time I'm publishing a package to `npm` and `bower`.

Contact me on Twitter or Github: [@PascalPixel](http://twitter.com/pascalpixel). I'm very happy to have contributions/PR's to this repository!

I used [Glyphs App](https://glyphsapp.com) in the end to manage the `.ufo` master 'file'/folder.

## Supported Characters
Here's the full table of characters that are supported in the font right now.

### Basic Latin
U+|0|1|2|3|4|5|6|7|8|9|A|B|C|D|E|F
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
002x| |!|"|#|$|%|&|'|(|)|*|+|,|-|.|/
003x|0|1|2|3|4|5|6|7|8|9|:|;|<|=|>|?
004x|@|A|B|C|D|E|F|G|H|I|J|K|L|M|N|O
005x|P|Q|R|S|T|U|V|W|X|Y|Z|[|\|]|^|_
006x|`|a|b|c|d|e|f|g|h|i|j|k|l|m|n|o
007x|p|q|r|s|t|u|v|w|x|y|z|{|&#124;|}|~|

### Latin-1 Supplement
U+|0|1|2|3|4|5|6|7|8|9|A|B|C|D|E|F
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
00Ax| |¡|¢|£|¤|¥|¦|§|¨|©|ª|«|¬| |®|¯
00Bx|°|±|²|³|´|µ|¶|·|¸|¹|º|»|¼|½|¾|¿
00Cx|À|Á|Â|Ã|Ä|Å|Æ|Ç|È|É|Ê|Ë|Ì|Í|Î|Ï
00Dx|Ð|Ñ|Ò|Ó|Ô|Õ|Ö|×|Ø|Ù|Ú|Û|Ü|Ý|Þ|ß
00Ex|à|á|â|ã|ä|å|æ|ç|è|é|ê|ë|ì|í|î|ï
00Fx|ð|ñ|ò|ó|ô|õ|ö|÷|ø|ù|ú|û|ü|ý|þ|ÿ

### Latin Extended-A
U+|0|1|2|3|4|5|6|7|8|9|A|B|C|D|E|F
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
010x|Ā|ā|Ă|ă|Ą|ą|Ć|ć|Ĉ|ĉ|Ċ|ċ|Č|č|Ď|ď
011x|Đ|đ|Ē|ē|Ĕ|ĕ|Ė|ė|Ę|ę|Ě|ě|Ĝ|ĝ|Ğ|ğ
012x|Ġ|ġ|Ģ|ģ|Ĥ|ĥ|Ħ|ħ|Ĩ|ĩ|Ī|ī|Ĭ|ĭ|Į|į
013x|İ|ı|Ĳ|ĳ|Ĵ|ĵ|Ķ|ķ|ĸ|Ĺ|ĺ|Ļ|ļ|Ľ|ľ|Ŀ
014x|ŀ|Ł|ł|Ń|ń|Ņ|ņ|Ň|ň|ŉ|Ŋ|ŋ|Ō|ō|Ŏ|ŏ
015x|Ő|ő|Œ|œ|Ŕ|ŕ|Ŗ|ŗ|Ř|ř|Ś|ś|Ŝ|ŝ|Ş|ş
016x|Š|š|Ţ|ţ|Ť|ť|Ŧ|ŧ|Ũ|ũ|Ū|ū|Ŭ|ŭ|Ů|ů
017x|Ű|ű|Ų|ų|Ŵ|ŵ|Ŷ|ŷ|Ÿ|Ź|ź|Ż|ż|Ž|ž|ſ

### Hiragana
U+|0|1|2|3|4|5|6|7|8|9|A|B|C|D|E|F
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
304x|　|ぁ|あ|ぃ|い|ぅ|う|ぇ|え|ぉ|お|か|が|き|ぎ|く
305x|ぐ|け|げ|こ|ご|さ|ざ|し|じ|す|ず|せ|ぜ|そ|ぞ|た
306x|だ|ち|ぢ|っ|つ|づ|て|で|と|ど|な|に|ぬ|ね|の|は
307x|ば|ぱ|ひ|び|ぴ|ふ|ぶ|ぷ|へ|べ|ぺ|ほ|ぼ|ぽ|ま|み
308x|む|め|も|ゃ|や|ゅ|ゆ|ょ|よ|ら|り|る|れ|ろ|ゎ|わ
309x|ゐ|ゑ|を|ん|ゔ|ゕ|ゖ|　|　|゙　|゚　|゛|゜|ゝ|ゞ|ゟ

### Katakana
U+|0|1|2|3|4|5|6|7|8|9|A|B|C|D|E|F
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
30Ax|゠|ァ|ア|ィ|イ|ゥ|ウ|ェ|エ|ォ|オ|カ|ガ|キ|ギ|ク
30Bx|グ|ケ|ゲ|コ|ゴ|サ|ザ|シ|ジ|ス|ズ|セ|ゼ|ソ|ゾ|タ
30Cx|ダ|チ|ヂ|ッ|ツ|ヅ|テ|デ|ト|ド|ナ|ニ|ヌ|ネ|ノ|ハ
30Dx|バ|パ|ヒ|ビ|ピ|フ|ブ|プ|ヘ|ベ|ペ|ホ|ボ|ポ|マ|ミ
30Ex|ム|メ|モ|ャ|ヤ|ュ|ユ|ョ|ヨ|ラ|リ|ル|レ|ロ|ヮ|ワ
30Fx|ヰ|ヱ|ヲ|ン|ヴ|ヵ|ヶ|ヷ|ヸ|ヹ|ヺ|・|ー|ヽ|ヾ|ヿ

### Unown
The following are ligatures that work like so:
- `unowna` > unowna
- `unownb` > unownb
- `unownc` > unownc

U+|0|1|2|3|4|5|6|7|8|9|A|B|C|D|E|F
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
006x| |unowna|unownb|unownc|unownd|unowne|unownf|unowng|unownh|unowni|unownj|unownk|unownl|unownm|unownn|unowno
007x|unownp|unownq|unownr|unowns|unownt|unownu|unownv|unownw|unownx|unowny|unownz| | | | |

### Extras
- `PKMN` > PKMN
- `'d` > 'd
- `'l` > 'l
- `'m` > 'm
- `'r` > 'r
- `'s` > 's
- `'v` > 'v
- `'t` > 't
