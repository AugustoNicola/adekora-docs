# Adèkora Morphology

This section provides a basic description of the Morphology of Adèkora, the section of Grammar focused on **morphemes and their combinations that form words**. The topics are ordered with the intention of putting the simpler and more neccesary concepts first, and then going into finer details. More examples and exceptions are listed in the respective sub-pages. Examples are written using the [romanization system](../phonology/main.md#romanization).


## Agglutinativity

As a highly [**agglutinative language**](https://en.wikipedia.org/wiki/Agglutinative_language), Adèkora uses many **[affixes](https://en.wikipedia.org/wiki/Affix)**, mainly for two purposes: to **mark for aspects of grammar**, and to **generate words**. 

Many word classes such as nouns, verbs and adjectives use affixes to mark for aspects like person, number, gender, tense, aspect, etc. This affix rules are explored in their respective word class sections. Since Adèkora is agglutinative, it is common for each affix to have **one precise simple meaning**, and this entails the concatenation of many affixes to express all required aspects of grammar in words.

On the other hand, affixes can be combined to create **long sequences of affix transformations** in order to create **words with precise meaning**, as explained in the [Word Derivation Section](#word-derivation).

## [Nouns](nouns.md)

The formation of nouns in Adèkora requires the expression of the noun's aspects (such as **person** and **number**) via **morphological declension** and with the use of a **mandatory article**. All nouns fall into one of five possible **genders**, which partition the noun space in a defined manner. A **case system** is also used, based on the **Ergative-Absolutive** alignment with some other extra cases. **Definiteness** (i.e. *the* vs. *a/an*) is also marked morphologically. Finally, there is some extra marking for expressing the **proximity** of the noun to the speaker/listener. The structure of noun declension and pronouns is illustrated below.

<div class="center showcase">
	<span> {PROXIMAL}-{GENDER}-{CASE} NOUN-{DEFINITENESS}-{PLURALITY} </span>
</div>

<div class="center showcase">
	<span> {PROXIMAL}-ROOT-{PLURALITY}-{CASE} </span>
</div>

## [Verbs](verbs.md)

Adèkora's verbs mark **TMA (Tense-Mood-Aspect)** using **affixes** in the verb's conjugation, with optional morphological marking for **source of evidence**. There are three tenses, four aspects, and four moods. **Verbs agree with their subjects in gender** via tense marking. Some **valency-changing particles** are also present. The structure of verb conjugation is shown below.

<div class="center showcase">
	<span> {MOOD}-{VERB}-{TENSE}-{ASPECT}-{EVIDENTIALITY} </span>
</div>



## Adjectives

### Location and Agreement

Adèkora's adjectives are placed **after the noun phrases** they describe, and display agreement with them in [Gender](nouns.md#gender) when the noun phrase is [plural](nouns.md#countability), according to the following table.


<table class="common-table">
	<tr>
		<td class="header" colspan="6">Adjective-Noun Agreement Suffixes</td>
	</tr>
	<tr>
		<td class="header"></td>
		<td class="header">Animate</td>
		<td class="header">Natural</td>
		<td class="header">Artificial</td>
		<td class="header">Abstract</td>
		<td class="header">Geographical</td>
	</tr>
	<tr>
		<td class="header">Singular</td>
		<td>∅</td>
		<td>∅</td>
		<td>∅</td>
		<td>∅</td>
		<td>∅</td>
	</tr>
	<tr>
		<td class="header">Plural</td>
		<td><em>-zhei</em></td>
		<td><em>-xem</em></td>
		<td><em>-ñem</em></td>
		<td><em>-zham</em></td>
		<td><em>-mei</em></td>
	</tr>
</table>

TODO add example.

### General Order

When many adjectives are applied to the same noun phrase, they are placed from left to right according to this ordering.

<div class="center showcase">
	<span> NOUN PHRASE > Origin > Opinion > Color > Shape > Size > Other </span>
</div>

TODO add example.

### Comparatives and Superlatives

The [comparative and superlative](https://en.wikipedia.org/wiki/Comparison_(grammar)) versions of adjectives are formed by adding a prefix. The **comparative prefix *bax-*** works very similarly to the -er suffix of English, while the **superlative prefix *ŕax-*** is similar to the -est English suffix.

TODO add example.

Adjectives in the comparative or superlative form can also be transformed into nouns using the noun-converter prefix chi-, in order to express concepts such as *I am the biggest* (TODO add example.)

## Adverbs

Adverbs in Adèkora are placed **after the structure they modify**, be it a verb, adjective, or something else; they do not morphologically agree with any other type of word, unlike adjectives. In case multiple adverbs are affecting the same clause or affecting one another, the principle of [head-directionality](../syntax/main.md#head-directionality) is followed, and therefore the adverbs are applied from right to left.

TODO add examples.

## Pronouns

Aside for the Personal Pronouns specified in the [Nouns section](nouns.md#pronouns), Adèkora manages the other types of pronouns in particular ways.

### Via Case

Some types are managed by [case marking](nouns.md#case): the **Possesive pronouns** (*hers, yours, mine*) are covered by the [Genitive case](nouns.md#genitive-case); the **Reflexive pronouns** (like in *I did it for myself*) use the [Absolutive case](nouns.md#ergativity); the **Reciprocal pronouns** (as in *They liked each other*) are deduced from context using the Absolutive case.

### Demonstrative

The **Demonstrative pronouns** (*that* in *Look at that pencil!*) are expressed using the [Personal pronouns](nouns.md#pronouns) with [proximal marking](nouns.md#proximals) before the noun phrase (if there is one). In case there is a noun phrase, the Personal pronoun's gender must agree with that of the noun phrase; if there is not, the gender must be Abstract.

TODO add examples "She looks at this pencil" => "She look 3S-G_AR-close pencil"
                  "I look at that leaf (which I can see)" => "I look 3S-G_NA-nearfar leaf"
                  "He looks at that (which He can not see)" => "He look 3S-G_AB-remfar"

### Interrogative

The **Interrogative pronouns** (*what*, *how*, *who*, *why*, etc.) are used when [asking questions](../syntax/main.md#questions), and have their own words. 

TODO add words.

### Relative

The **Relative pronouns** are used to mark [relative clauses](https://en.wikipedia.org/wiki/Relative_clause) which are related to an [interrogative pronoun](#interrogative). Instead of being the same word as their interrogative counterpart - like in English - the **suffix *-kep* to transform any Interrogative pronoun into a Relative one**. TODO add example.

### Indefinite

The role of **Indefinite pronouns** (like *somebody*, *anything*, *no one*) is covered in Adèkora by dedicated words exhibiting a regular affix pattern.

TODO add words.

## Word Derivation

Since Adèkora heavily relies on affixes to morphologically mark many aspects across all word types, an extensive system of prefixes and suffixes is present that greatly helps obtain new words by concatenating affixes. Although there are many root words, with original morphology and many examples of other derivational strategies (such as [compounding](https://en.wikipedia.org/wiki/Compound_(linguistics))), this is the most common process.

Adèkora uses this affix system to create both inflections and derivations; that is, some affixes transform a word from one class into another word from the same class, whereas other affixes create words from a different grammatical class than the original (moreover, there exist affixes that have the precise intention of adapting a concept into a particular word class, such as the noun-generator prefix *chi-*).

The many affixes of Adèkora are documented in the [Vocabulary Section](../vocabulary/main.md), with information on the type of affix, particular considerations, etc.