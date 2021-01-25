# sjyko

This tutorial will cover the phonology, morphogy, and grammar of the constructed language sjyko.

## Phonology

sjyko has 7 consonants and 3 vowels, listed below: p, consonant - `p` in `put`
* c, consonant - `s` in `snake`
* s, consonant - `sh` in `shape`
* k, consonant - `k` in `king`
* d, consonant - `d` in `dog`
* j, consonant - `y` in `young`
* r, consonant - `j` in `bonjour` or `r` in `red`, speaker`s choice
* v, consonant - `v` in `view`
* a, vowel     - `a` in `father`
* y, vowel     - `ee` in `meet`
- o, vowel     - `oa` in `goat`

(The pronunciation of the consonant `r` is up to the speaker, and can change throughout a single word - `ror` could be pronounced
 like the English word `roar`, like the French word `rouge`, or any combiantion of the soft j and hard r.)

Multiple letters of the same class can be joined together, unlike some other languages. When this occurs, the speaker should simply
pause after the first letter. For example, `dco` would be spoken as `d`so`.

In addition to consonants and vowels, sjyko has several seperator letters. These are used to designate the ends of tags, objects, and other grammatical things (see below for more details). There are three:

* The high seperator. It is written as either a `ʰ` or a `'`. It is pronounced similar to the English `h`, but with air moving along
  the roof of the mouth as if to roll and `r`. Similar to the `h` in Mandarin `hei`.
* The low seperator. It is written as either a `ₕ` or a `,`. It is pronounced like the `ch` in the German word `bach`. If unsure, just  pronounce it like `k` but with some air moving out of your mouth as you make the sound.
* The middle seperator. It is written as an `h` or `;`. It is pronounced the same way as the English `h`.

All seperators are optional unless the grammar of a sentence would be changed by their absence.

## Grammar

All sentences in sjyko are simply written as objects, which themselves are described as a collections of attributes. This is in
contrast to many other languages, in which objects are described using specific words. The sjyko approach is much more general and
allows for more objects to be describd with fewer words. Attributes of an object are described using combinations of tags. A tag is
just a way to write an attribute. 

### Points

Tags are composed of three main types of words: points, attributes, and particles. A point
describes a certain quality of an object, ranging from something concrete, like color, to more abstract things, like conciousness. Points
are each 3 letters long, and they can be chained to produce new points: if points `abc` and `def` are valid, then point `abcdef` (and `defabc`) is also valid. The meanings of chained points are interpreted left to right: if I combine two points meaning `sound` and `musical` together,
the meaning would be `musical sound`, ie. `song`. Points may refer to something called the 'built object'. This simply means the object
described so far by any other tags applied and all points interpreted so far. When points are being interpreted left to right, each point
changes the built object sequentially, so what exactly this is may change as one reads a word. Let's look at an example: suppose I had a point
meaning `the parent of the built object` and one meaning `the name of the built object`. Imagine our sentence had this tag, and another tag
expressing that the object was red. This tag would then be interpreted as `the name of the parent of this red object`. The built object starts
out as simply a combination of all other tags in a sentence, so when interpreting `the parent of the built object`, the built object is just
something with the tag of red. Then we apply the next point in the word, and get `the name of the built object.`  Now the built object refers
to the parent of the full described object, so `the name of the built object` is interpreted in this context, leading to the given translation.

### Particles

Points aren't useful on their own; they must be chained into tags using particles. Each tag in a sentence is composed of a point, one or more
'sub-points', a particle, and a value. The first point tells us what trait is being described, for example in the above the name of the
red object's parent. The sub-points describe any additional values needed for this particular tag. The particle defines the tag's type, and the
value what the vlaue of that particular trait is. A tag type just describes *how* a tag describes an attribute. There are three types of tag:

* Spectrum tags. These tags have two sub-points, describing two points of a spectrum for the given attribute. The value must be one of a few
  position words, describing the position on the spectrum of the described trait, with 'left' representing the first attribute and 'right' the
  second. The words are:
  
  - Far left:       `pa`
  - Mid left:       `ca`
  - Slightly left:  `sa`
  - Center:         `ka`
  - Slightly right: `da`
  - Mid right:      `ja`
  - Far right:      `ra`
  - No position, or outside of the spectrum: `va`
  (Notice that the first letters of each word are the consonants in order.)

  Spectrums are written using the main point, an optional low seperator, the first sub-point, another low seperator, the second sub point, and
  a third low seperator, followed by the spectrum particle `py`. Then there is another optional low seperator and the value.
* Boolean tags. These simply describe whether a trait is true or false, exists or doesn't exist. They have no sub-points, and are written as
  a point, followed by an optional low seperator, followed by the boolean particle `cy`, followed by yet another low seperator, followed by
  a boolean value. The words for booleans are `yypo` for `true` and `yyco` for `false`.
* Object tags. These are used for the most broad points, and simply say that the value of a trait is a given object. They take no sub-points.
  An object tag is written as a point, followed by a low seperator, followed by the object particle `sy`, another optional low seperator, and
  then an object or a point. The object should be terminated with a middle seperator so that you can have tags applied to the parent object
  after the object tag.
* Enumerated tags. These are like object tags, but instead of allowing any object, they specify a choice between several objects. This may not
  seem useful at first, but when you get into asking questions (see below), its purpose becomes evident. An enumerated tag is written as a
  point, followed by an optional low seperator, and then any number (at least 1) of points seperated by low seperators. Then, there should be
  a low seperator, the enumeration particle ky, another optional low seperator, and the value. The value can be any of the given sub-points.

Questions can be accomplished with the dy particle. It can be substituted for any value, and it asks the speaker to respond with an appropriate
answer. For spectrum tags, this means a position; for enumerated tags, one of the passed sub-points; etc.

### Attributes

The final type of word is attributes. These are really a subclass of point, but they are not valid as the leading point in a tag: only as sub-
points or as a value. They are similar to adjectives in other languages. They cannot be joined and must stand alone.

## Morphology

The morpology of sjyko is relatively simple: words can be any 'shape' (ie., ccv, cvc, etc.) as long as they are 3 letters long. There are a few
exceptions, as we have seen: particles are always a different amount of letters, to distinguish them from points. As well, when transliterating
a name, it should either be padded or truncated to that it is never 3 letters long. This can be done easily by simply adding a vowel or
similar to the end.

### Numbers

Numbers, like particles, must be distinguished from points. Numbers are written in base 8, using the consonants in order as digits, and ending
in the suffix `oay`. Thus, the numbers 0 through 7 can be written as follows:

* 0: `poay`
* 1: `coay`
* 2: `soay`
* 3: `koay`
* 4: `doay`
* 5: `joay`
* 6: `roay`
* 7: `voay`

To make numbers higher than seven, consonants should be chained to write digits. For example, the number 8, `10` in octal, would be written as
`cpoay`. If one desires, a vowel can be inserted after any digit except the last. Thus, the octal number `123` could be written as
`cskoay`, `cysykoay`, `cosykoay`, etc. However, no consonants can be used, as that would change the value of the number.

---

## Appendix: Useful Resources

The sjyko website can be found at [sjyko.github.io](https://sjyko.github.io). If you would like to talk in or abou sjyko with other people, the sjyko Discord
can be found [here](https://discord.gg/exYSY7wu7h).

## Appendix: Lexicon

The lexicon of sjyko is very much in development, and is being added to often. However, the (small) lexicon as it stands can be read below.
Note that while new words will appear often, the existing words will never change, so this is a source of truth for the definitions it holds.
A dictionary will be forthcoming using the current lexicon. Check the sjyko website for more information.

(Note about notation: p. means the listed word is a point, and a. an attribute.)

```
cyj: p. The amount of the built object.
vyc: p. The physical size of the built object.
kaj: p. The timespan of or temporal size of the built object.
kap: p. The start or first edge of the built object.
koj: p. The end or last edge of the built object.
kor: p. The center of the built object.
poj: p. Built object is yours.
sak: p. Built object is mine.
cav: p. The reason the built object is the way it is.
cok: p. Change built object to a group of the built object.
rad: p. The existence of the built object.
rop: p. The conciousness or mind of the built object.
dor: p. The life of the built object.
jav: p. The body or physical presence of the built object.
coj: p. The mood or emotion of the built object.
cor: p. The physical position of the built object.
pos: p. The temporal position of the built object.
sos: p. The physical appearance of the built object.
jar: p. The color of the built object.
rar: p. The sound of the built object.
pok: p. The built object is in the present, to the speaker.
dys: p. The built object is in the past, to the speaker.
pov: p. The built object is in the future, to the speaker.
kyk: p. The built object is to the west, to the speaker.
aca: p. The built object is to the east, to the speaker.
sac: p. The built object is to the north, to the speaker.
vaj: p. The built object is to the south, to the speaker.
vap: p. The built object is above, to the speaker.
ova: p. The built object is below, to the speaker.
acy: p. The x-rotation of the built object.
jac: p. The y-rotation of the built object.
ryc: p. The z-rotation of the built object.
dos: p. The name of the built object.
jop: a. Red.
avy: a. Green.
paj: a. Blue.
pop: a. Black.
rod: a. Positive, good.
ody: a. Negative, bad.
jaj: a. Large
ojy: a. Small
odo: p. The gender of the built object.
cas: p. The sex of the built object.
pod: p. The built object is different from the argument.
sor: p. The built object is the same as the argument.
ror: p. The place of origin of the built object.
aja: p. The time of origin of the built object.
oja: a. Round
yka: a. Rectangular
caj: a. Square
jyc: a. Triangular
ora: a. Quadrilateral
rap: a. Pentagonal
ryr: p. Built object belongs to the referenced object, should be followed by a name
  or a number. (Functions as a pronoun.)
dod: p. The built object can be referenced as the name or number following this word.
sod: p. The width of the built object.
por: p. The height of the built object.
ypo: p. The depth of the built object.
joc: p. The desires or wants of the built object.
vak: p. The possessions or property of the built object.
syc: p. The humanity or sentience of the built object.
kov: p. The opposite of the built object.
vyv: p. The motivation or reason for the built object.
pas: p. The parent of the built object.
koc: p. The spouse of the built object.
cad: p. The sibling of the built object.
vok: p. The child of the built object.
sys: p. The next version of the built object.
yvo: p. The previous version of the built object.
yro: p. A clone or copy of the built object which is distinct.
yco: p. The skill or ability of the built object.
opy: p. The food or sustenance of the built object.
daj: p. The drink of the built object.
ryk: p. The pattern or design of the built object.
ydy: a. Sexual
osa: a. Romantic
yvy: a. Platonic
sas: a. Artistic
cos: a. Entertaining
dyj: a. Male
pac: a. Female
ypy: a. Non binary
paa: a. Correct
oro: a. Just, fair
pap: a. Rational
kac: a. Normal, conventional
pak: p. The structure or organization of the built object.
oko: p. The tendency or structure of the built object.
```

---
