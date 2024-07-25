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

<div class="trans">
	<p class="literal">dei ka'lop oi'rrel xu'pi'zham'zhon</p>
	<p class="roman">dei-Ø             <emph>kalop-Ø-Ø        oiŕel-Ø</emph>        Ø-xupi-zham-zhon</p>
	<p class="gloss">G_AN-ABS  <emph>horse-DEF-SG  brown-SG</emph>  IND-fell-PST.G_AN-SP</p>
	<p class="meaning">The <emph>brown horse</emph> fell.</p>
</div>

<div class="trans">
	<p class="literal">dei ka'lo'pal oi'rrel'zhei xu'pi'zham'zhon</p>
	<p class="roman">dei-Ø             <emph>kalo-Ø-pal        oiŕel-zhei</emph>               Ø-xupi-zham-zhon</p>
	<p class="gloss">G_AN-ABS  <emph>horse-DEF-PL  brown-G_AN.PL</emph>  IND-fell-PST.G_AN-SP</p>
	<p class="meaning">The <emph>brown horses</emph> fell.</p>
</div>

TODO revisar consonant repetition! kalop => kalopal

### General Order

When many adjectives are applied to the same noun phrase, they are placed from left to right according to this ordering.

<div class="center showcase">
	<span> NOUN PHRASE > Origin > Opinion > Color > Shape > Size > Other </span>
</div>

<div class="trans">
	<p class="literal">dei u'kau'zhu a'me'ri'ka'ke'ku drei'kal'pli paz'di'mi'za</p>
	<p class="roman">dei-Ø             ukau-zhu-Ø       <emph>amerika-keku  dreikalpli   pazdimiza</emph> </p>
	<p class="gloss">G_AN-ABS  duck-INDF-SG  <emph>america-from  admirable  yellow</emph></p>
	<p class="meaning">An <emph>admirable american yellow</emph> duck.</p>
</div>

### Comparatives and Superlatives

The [comparative and superlative](https://en.wikipedia.org/wiki/Comparison_(grammar)) versions of adjectives are formed by adding a prefix. The **comparative prefix *bax-*** works very similarly to the -er suffix of English, while the **superlative prefix *ŕax-*** is similar to the -est English suffix.

<div class="trans">
	<p class="literal">zhà'ke'lo rroi bax'bu'xok du xà'ñi'pad'xol</p>
	<p class="roman">zhàke-Ø-lo             Ø-ŕoi-Ø-Ø                  <emph>bax-buxok</emph>      du-Ø              xàñipad-xol-Ø</p>
	<p class="gloss">G_AN.3-SG-ERG  IND-be-PRS-CONT  <emph>CMPR-scary</emph>  G_NA-ABS  tornado-INDF-SG</p>
	<p class="meaning">She's <emph>scarier</emph> than a tornado!</p>
</div>

<div class="trans">
	<p class="literal">zhi'zhà'ke'lo rroi dei dal rrax'bon'ban mi'chem kà'ñu</p>
	<p class="roman">zhi-zhàke-Ø-lo                     Ø-ŕoi-Ø-Ø                 dei-Ø              dal-Ø-Ø       <emph>ŕax-bonban</emph></p>
	<p class="gloss">N_FAR-G_AN.3-SG-ERG  IND-be-PRS-CONT  G_AN-ABS  cow-DF-SG  <emph>SUP-heavy</emph></p>
	<p class="roman">mi-chem        kàñu-Ø-Ø</p>
	<p class="gloss">G_GE-GEN  country-DF-SG</p>
	<p class="meaning">That's the <emph>heaviest</emph> cow of the country.</p>
</div>

Adjectives in the superlative form can also be transformed into nouns using the noun-converter prefix <em>chi</em>.

<div class="trans">
	<p class="literal">dar chi'rrax'bo'le'zer è'mer'zen'zhon</p>
	<p class="roman">dar-Ø            chi-ŕax-bolezer-Ø-Ø          Ø-èmer-zen-zhon</p>
	<p class="gloss">G_AB-ABS  <emph>NOUN-SUP-sad-DF-SG</emph>  IND-live-FUT.G_AB-SP</p>
	<p class="meaning">The <emph>saddest one</emph> will live.</p>
</div>

## Adverbs

Adverbs in Adèkora are placed **after the structure they modify**, be it a verb clause, adjective, or something else; they do not morphologically agree with any other type of word, unlike adjectives. In case multiple adverbs are affecting the same clause or affecting one another, the principle of [head-directionality](../syntax/main.md#head-directionality) is followed, and therefore the adverbs are applied from right to left.

<div class="trans">
	<p class="literal">dei'lo zhi'ko'ma'kem dei'ze'zham'zhon dar zi'ki'zhai'pal ko'li'xa'zai</p>
	<p class="roman">dei-lo             zhikomakem-Ø-Ø  Ø-deize-zham-zhon         dar-Ø            zikizhai-Ø-pal         <emph>kolixazai</emph></p>
	<p class="gloss">G_AN-ERG  doctor-DF-SG         IND-direct-PST-ZHON  G_AB-ABS  experiment-DF-PL  <emph>firmly</emph></p>
	<p class="meaning">The doctor <emph>firmly</emph> directed the experiments.</p>
</div>

<div class="trans">
	<p class="literal">dei'lo dà'mi'ko'kem ku'ro'zham u'ka'pu'kol'zai</p>
	<p class="roman">dei-lo            dàmikokem-Ø-Ø       Ø-kuro-zham-Ø                        <emph>ukapukolzai</emph></p>
	<p class="gloss">G_AN-ABS  park_ranger-DF-SG  IND-cook-PST.G_AN-CONT  <emph>joyfully</emph></p>
	<p class="meaning">The park ranger was cooking <emph>joyfully</emph>.</p>
</div>

Because adverbs are applied after verb clauses, some ambiguous situations can occur.

<div class="trans">
	<p class="literal">dei'lo mo're na'kà'mi dei xi'xi i'kei'lo do'mi kei'lo pu'ru'kai</p>
	<p class="roman">dei-lo            more-Ø-Ø     Ø-nakàmi-Ø-Ø             dei-Ø             xixi-Ø-Ø</p>
	<p class="gloss">G_AN-ERG  dog-DF-SG  IND-love-PRS-CONT  G_AN-ABS  baby-DF-SG</p>
	<p class="roman">ikei-lo               Ø-domi-Ø-Ø                 keilo          <emph>purukai</emph></p>
	<p class="gloss">G_AN.1-ERG  IND-feed-PRS-CONT  REL.ABS  <emph>lazily</emph></p>
	<p class="meaning">The dog <emph>lazily</emph> loves the baby that I am feeding.</p>
	<p>or</p>
	<p class="meaning">The dog loves the baby that I am <emph>lazily</emph> feeding.</p>
</div>

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


## Location

Prepositions that handle spatial information are divided into three categories:

- **Relative** spatial prepositions, which specify the spatial relation between objects.
- **Adjacent** spatial prepositions, which are a particularization of Relative prepositions that add the meaning of very close proximity, adjacency, or some other similar specialization.
- **Directional** spatial prepositions, which characterize some direction of movement.

All Locative Prepositions are created by adding the corresponding prefix of its type to a root word (usually associated with location). Many of these prepositions have a similar correspondence in English and other common languages; the table below shows all three spatial preposition type prefixes, as well as a short approximation of their meaning for each combination with the roots. For a more complete explanation of every preposition, as well as special use cases, look into their definitions in the [Vocabulary section](../vocabulary/main.md).

<table class="common-table">
	<tr>
		<td class="header" colspan="4">Location Prepositions, Prefixes and Roots</td>
	</tr>
	<tr>
		<td class="header">Root</td>
		<td class="header">Relative</td>
		<td class="header">Adjacent</td>
		<td class="header">Directional</td>
	</tr>
	<tr>
		<td class="header"></td>
		<td class="header">ñe-</td>
		<td class="header">zho-</td>
		<td class="header">leu-</td>
	</tr>
	<tr>
		<td>àki</td>
		<td>above</td>
		<td>on top (touching)</td>
		<td>upwards</td>
	</tr>
	<tr>
		<td>boza</td>
		<td>below</td>
		<td>under (touching)</td>
		<td>downwards</td>
	</tr>
	<tr>
		<td>ipi</td>
		<td>left</td>
		<td>left (touching)</td>
		<td>leftwards</td>
	</tr>
	<tr>
		<td>lupar</td>
		<td>right</td>
		<td>right (touching)</td>
		<td>rightwards</td>
	</tr>
	<tr>
		<td>kol</td>
		<td>among</td>
		<td>inside</td>
		<td>across</td>
	</tr>
	<tr>
		<td>bumu</td>
		<td>outside</td>
		<td>on the surface</td>
		<td>around</td>
	</tr>
	<tr>
		<td>kère</td>
		<td>in front of</td>
		<td>front (touching)</td>
		<td>towards (general direction)</td>
	</tr>
	<tr>
		<td>kèrai</td>
		<td>∅</td>
		<td>∅</td>
		<td>towards (sth specifically)</td>
	</tr>
	<tr>
		<td>piña</td>
		<td>between</td>
  		<td>∅</td>
		<td>in between</td>
	</tr>
	<tr>
		<td>dalme</td>
		<td>parallel to</td>
		<td>parallel to (while touching)</td>
		<td>alongside</td>
	</tr>
	<tr>
		<td>zeni</td>
		<td>beyond</td>
		<td>behind</td>
		<td>away from</td>
	</tr>
	<tr>
		<td>doki</td>
		<td>near (visible)</td>
		<td>aside (touching)</td>
		<td>∅</td>
	</tr>
	<tr>
		<td>balkem</td>
		<td>near (invisible)</td>
		<td>emotionally/conceptually close</td>
		<td>∅</td>
	</tr>
	<tr>
		<td>ziñel</td>
		<td>far</td>
		<td>weakly reminiscent</td>
		<td>∅</td>
	</tr>
</table>

The Locative Prepositions are mainly used together with noun phrases to form Locative Clauses, which add the associated locative meaning to a sentence. Whenever a noun phrase is part of a Locative Clause, it is inflected using the [Locative Case](nouns.md#locative-case), to show accordance with the Locative Preposition. 

<div class="trans">
    <p class="literal">ñe'bo'za dem'chek blo'ke dei ko'le'xa'zhu dron</p>
    <p class="roman"><emph>ñeboza  dem-chek        bloke-Ø-Ø</emph>     dei-Ø             kolexa-zhu-Ø  Ø-dron-Ø-Ø               </p>
    <p class="gloss"><emph>under    G_AR-LOC  chair-DEF-SG</emph>  G_AN-ABS  cat-INDF-SG   IND-be-PRS-CONT</p>
    <p class="meaning">There is a cat <emph>under the chair</emph>.</p>
</div>

<div class="trans">
    <p class="literal">leu'ze'ni i'kei'lem'chek zhi'ek drè'zhon</p>
    <p class="roman"><emph>leuzeni         ikei-lem-chek</emph>          zhiek-Ø-Ø              Ø-drè-Ø-zhon      </p>
    <p class="gloss"><emph>away_from  G_AN.1-PL-LOC</emph>  G_AN.2-SG-ABS  IND-go-PRS-SP  </p>
    <p class="meaning">Get <emph>away from us</emph>!</p>
</div>

The Locative Case can also be used to form a Locative Clause without any Locative Pronoun, which has a very broad sense of location similar to English's *in/on/at* prepositions.

<div class="trans">
    <p class="literal">dem'chek do'me i'kei'chem zhi'ek dron</p>
    <p class="roman"><emph>dem-chek      dome-Ø-Ø          ikei-Ø-chem</emph>            zhiek-Ø-Ø             Ø-dron-Ø</p>
    <p class="gloss"><emph>G_AR-LOC  house-DEF-SG  G_AN.1-SG-GEN</emph>  G_AN.2-SG-ABS  IND-be-PRS-CONT</p>
    <p class="meaning">He's <emph>in my house</emph>.</p>
</div>

<div class="trans">
    <p class="literal">mi'chek loi'xa'zal i'kei'lo drè'zhen zhà'xe</p>
    <p class="roman"><emph>mi-chek         loixazal-Ø-Ø</emph>       ikei-Ø-lo                Ø-drè-zhen-Ø                             zhàxe-Ø-Ø</p>
    <p class="gloss"><emph>G_GE-LOC  school-DEF-SG</emph>  G_AN.1-SG-ERG  IND-meet-FUT.G_AN-CONT  G_AN.3-SG-ABS</p>
    <p class="meaning">I'll meet her <emph>at school</emph>.</p>
</div>