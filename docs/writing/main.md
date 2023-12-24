# Adèkora Writing System

Adèkora's main writing system (called TODO_WRITING_SYSTEM) is an **alphabet-based** system, in which each phoneme has its own [character](#table-of-characters) (called TODO_WRITING_SYSTEM_CHARACTER).

This system expresses **left-to-right and top-to-bottom directionality**, just like English. There are **35 characters**, divided as **21 letters** (14 consonants and 7 vocals), **8 digits**, and **6 localizators**. 

## Letters

Each letter represents exactly one [phoneme](../phonology/main.md#adèkora-phonology), so there is only one pronounciation for each one. Like many other alphabets, Adèkora's letters are strung to form syllables. The bottom line that appears in many characters is called TODO_WRITING_SYSTEM_LINE, and it physically connects the letters to create the syllables. Therefore, all consonants start and end such that they can be indefinetly concatenated using the TODO_WRITING_SYSTEM_LINE (since all consonants can potentially have more letters before or after them). Only some vowels follow this principle, whereas the so-called *determinate vowels* do not continue the TODO_WRITING_SYSTEM_LINE, indicating that the syllable must end there.

## [Digits](numbering.md)

Adèkora uses base 8 numeral system. This means that instead of having the digits from 0 to 9 like in many languages, only the digits corresponding from 0 to 7 are present. Whereas number *eight* would be < **8** > in English, Adèkora represents this as the digit for *one* followed by the digit for *zero* (literally, <wm>10</wm>).

The digits for *zero* to *three* are unique. After those, the remaining four digits modify the previous ones by adding a horizontal stroke which represents an addition of four units (e.g. *two* is <wm>2</wm>; adding the stroke *six* is obtained, <wm>6</wm> ).

Negative integers can be represented by suffixing the digits with the syllable TODO_WRITING_SYSTEM_NEGATIVE (literally *negative*). Therefore, *negative fifteen* (< **-15** >) would be represented as <wm>17'nex</wm> .

## Localizers

In Adèkora, a few spatial concepts are given their own glyph:

- *TODO_CLOSE* < <wl>!</wl> >, a distance close to the speaker.
- *TODO_FAR_VISIBLE* < <wl>"</wl> >, an area far from the speaker such that vision is still mantained.
- *TODO_FAR_NOT_VISIBLE*, < <wl>#</wl> >, an area far from the speaker such that there is no vision of the place.
- *TODO_LIFE* < <wl>$</wl> >, Life (commonly to convey that something/someone is alive).
- *TODO_DEATH* < <wl>%</wl> >, Death (commonly to convey that something/someone is dead).
- *TODO_UNKNOWN* < <wl>&</wl> >, the Unknown (commonly to convey that something/someone is missing).

All localizers are syntactically treated as places. As an example, to convey that someone is alive, the usage of *TODO_LIFE* would more acurrately be translated as to *"be in the Life"*.

## Punctuation Marks

Aside from standard characters, Adèkora has punctuation marks for the following purposes:

- *TODO_SYLLABLE_CLOSE*, to separate syllables (from the same word), with < <wl>'</wl> >.
- *TODO_WORD_CLOSE*, to separate words, with < <wl>&hairsp; &hairsp;</wl> >.
- *TODO_SENTENCE_CLOSE*, to end sentences, with < <wl>.</wl> >.

Some punctuation marks common in other languages (such as commas, exclamation/quotation marks, parenthesis) are not present. Instead, sentences indicate interrogative and other clauses by other means, and sentence structure is simplified to avoid using commas.

## Table of Characters

<table class="writing-all-characters-table">
	<tr>
		<th><wxl>p</wxl></th>
		<th><wxl>b</wxl></th>
		<th><wxl>d</wxl></th>
		<th><wxl>ch</wxl></th>
		<th><wxl>k</wxl></th>
		<th><wxl>m</wxl></th>
		<th><wxl>n</wxl></th>
	</tr>
	<tr>
		<th><x>p</x></th>
		<th><x>b</x></th>
		<th><x>d</x></th>
		<th><x>ch</x></th>
		<th><x>k</x></th>
		<th><x>m</x></th>
		<th><x>n</x></th>
	</tr>
	<tr>
		<th><wxl>ñ</wxl></th>
		<th><wxl>rr</wxl></th>
		<th><wxl>r</wxl></th>
		<th><wxl>z</wxl></th>
		<th><wxl>zh</wxl></th>
		<th><wxl>x</wxl></th>
		<th><wxl>l</wxl></th>
	</tr>
	<tr>
		<th><x>ñ</x></th>
		<th><x>ŕ</x></th>
		<th><x>r</x></th>
		<th><x>z</x></th>
		<th><x>zh</x></th>
		<th><x>x</x></th>
		<th><x>l</x></th>
	</tr>
	<tr>
		<th><wxl>a</wxl></th>
		<th><wxl>e</wxl></th>
		<th><wxl>i</wxl></th>
		<th><wxl>o</wxl></th>
		<th><wxl>u</wxl></th>
		<th><wxl>à</wxl></th>
		<th><wxl>è</wxl></th>
	</tr>
	<tr>
		<th><x>a</x></th>
		<th><x>e</x></th>
		<th><x>i</x></th>
		<th><x>o</x></th>
		<th><x>u</x></th>
		<th><x>à</x></th>
		<th><x>è</x></th>
	</tr>
	<tr>
		<th><wxl>0</wxl></th>
		<th><wxl>1</wxl></th>
		<th><wxl>2</wxl></th>
		<th><wxl>3</wxl></th>
		<th><wxl>!</wxl></th>
		<th><wxl>"</wxl></th>
		<th><wxl>#</wxl></th>
	</tr>
	<tr>
		<th><x>0</x></th>
		<th><x>1</x></th>
		<th><x>2</x></th>
		<th><x>3</x></th>
		<th><x>LOC</x></th>
		<th><x>LOC</x></th>
		<th><x>LOC</x></th>
	</tr>
	<tr>
		<th><wxl>4</wxl></th>
		<th><wxl>5</wxl></th>
		<th><wxl>6</wxl></th>
		<th><wxl>7</wxl></th>
		<th><wxl>$</wxl></th>
		<th><wxl>%</wxl></th>
		<th><wxl>&</wxl></th>
	</tr>
	<tr>
		<th><x>4</x></th>
		<th><x>5</x></th>
		<th><x>6</x></th>
		<th><x>7</x></th>
		<th><x>LOC</x></th>
		<th><x>LOC</x></th>
		<th><x>LOC</x></th>
	</tr>
</table>



<!--The characters are combined into syllables according to [the phonotactical rules](../phonology/main.md#phonotactics). All the characters in a syllable are connected by the TODO_WRITING_LINE, a continuous line at the bottom of the characters. The syllables of a word are strung together using a special mark called TODO_WRITING_SEPARATOR (pictured as < <ws>'</ws> >).-->

### [Characters](./alphabet.md)



### [Vowels](./vowels.md)
