# Adèkora Syntax

This section provides a description of the [Syntax](https://en.wikipedia.org/wiki/Syntax) of Adèkora, the section of Grammar focused on the formation of sentences by combining [words](../morphology/main.md). The topics are ordered with the intention of putting the simpler and more neccesary concepts first, and then going into finer details. More examples and exceptions are listed in the respective sub-pages. Examples are written using the [romanization system](../phonology/main.md#romanization).

## Word Order

Adèkora follows [SVO Word Order](https://en.wikipedia.org/wiki/Subject%E2%80%93verb%E2%80%93object_word_order), which means that sentences usually have the Subject, then the Verb and lastly the Objejct. This is the same as English, so a sentence such as *"The cat follows her"* would have the words for *cat* (<*kolexa*>), *follow* (<*plau*>) and *her* (<*ilzhàxelem*>) in that same order.


## Head-Directionality

Adèkora is a strongly **head-initial** language. This means that in many types of phrases, the most important component - the head - is usually placed at the start. This applies to the following structures:

- **Noun-Adjective order**: in noun phrases where [adjectives](../morphology/main.md#adjectives) affect a [noun](../morphology/nouns.md), the noun is placed first and the adjectives follow.
- **Verb-Adverb order**: in verb phrases where [adverbs](../morphology/main.md#adverbs) affect a [verb](../morphology/verbs.md), the verb is placed first and the adverbs follow.
- **Adjective-Adverb order**: in cases where an adverb is modifying an adjective, the adjective is placed first with any modifiers following afterwards.
- **Noun-Genitive order**: [genitive clauses](../morphology/nouns.md#genitive-case) - those that express possesion - place the noun first and the genitive afterwards.
- **Preposition-Noun order**: Adèkora mainly uses adpositions that come before clauses - especially noun phrases - to convey various aspects such as relative position, temporal relation, etc.
- **Noun-Relative Clause order**: noun phrases that use relative clauses to further describe the subject typically place the noun first and the relative clause afterwards.

## Negation

Negation is expressed by the use of the **two negation particles *lau* and *ku***. The particle *lau* is placed just before the start of the clause being negated (usually a verb phrase), while *ku* is located at the end of the clause. This effectively encapsulates the clause. 

<div class="trans">
	<p class="literal">i'kei'lem'lo lau chi'che du ken'xol ku</p>
	<p class="roman">ikei-lem-lo              <emph>lau</emph>                   Ø-chiche-Ø-Ø              du-Ø              ken-xol-Ø            <emph>ku</emph>  </p>
	<p class="gloss">G_AN.1-PL-ERG  <emph>NEG_START</emph>  IND-like-PRS-CONT  G_NA-ABS  carrot-INDF-SG <emph>NEG_END</emph></p>
	<p class="meaning">We do <emph>not</emph> like carrots.</p>
</div>

For common phrases in which there is no ambiguity of the clause that is negated, the particle before the clause can be omitted, and the particle placed at the end can be either one of the two particles. This is common in informal speech.

<div class="trans">
	<p class="literal">i'kei'lo ni'pa'le'zhon zhà'ke lau</p>
	<p class="roman">ikei-Ø-lo                Ø-nipale-Ø-zhon   zhàke-Ø-Ø              <emph>lau</emph></p>
	<p class="gloss">G_AN.1-SG-ERG  IND-see-PRS-SP  G_AN.3-SG-ABS  <emph>NEG</emph></p>
	<p class="meaning">I do <emph>not</emph> see her.</p>
</div>

<div class="trans">
	<p class="literal">du pi'roi do'mè'xen'zhon ku</p>
	<p class="roman">du-Ø              piroi-Ø-Ø          Ø-domè-xen-zhon    <emph>ku</emph></p>
	<p class="gloss">G_NA-ABS  rabbit-DEF-SG  IND-sleep-FUT-SP  <emph>NEG</emph></p>
	<p class="meaning">The rabbit will <emph>not</emph> sleep.</p>
</div>


The usage of both particles is especially useful in sentences where there are multiple elements being negated, in order to disambiguate. Compare the following examples:

<div class="trans">
	<p class="literal">i'kei'lo chi'che'zhon dei zhè'ral kei'lo e'da'mè</p>
	<p class="roman">ikei-Ø-lo                Ø-chiche-Ø-zhon   dei-Ø             zhèral-Ø-Ø               keilo          Ø-edamè-Ø-Ø</p>
	<p class="gloss">G_AN.1-SG-ERG  IND-like-PRS-SP  G_AN-ABS  fisherman-DEF-SG  REL.ABS  IND-dance-PRS-CONT</p>
	<p class="meaning">I like the fisherman that is dancing.</p>
</div>

<div class="trans">
	<p class="literal">i'kei'lo lau chi'che'zhon dei zhè'ral kei'lo e'da'mè ku</p>
	<p class="roman">ikei-Ø-lo                 <emph>lau</emph>                    Ø-chiche-Ø-zhon   dei-Ø             zhèral-Ø-Ø</p>
	<p class="gloss">G_AN.1-SG-ERG  <emph>NEG_START</emph>  IND-like-PRS-SP  G_AN-ABS  fisherman-DEF-SG</p>
	<p class="roman">keilo          Ø-edamè-Ø-Ø                 <emph>ku</emph></p>
	<p class="gloss">REL.ABS  IND-dance-PRS-CONT  <emph>NEG_END</emph></p>
	<p class="meaning">I <emph>don't</emph> like the fisherman that is dancing.</p>
</div>

<div class="trans">
	<p class="literal">i'kei'lo chi'che'zhon dei zhè'ral kei'lo lau e'da'mè ku</p>
	<p class="roman">ikei-Ø-lo                Ø-chiche-Ø-zhon   dei-Ø             zhèral-Ø-Ø</p>
	<p class="gloss">G_AN.1-SG-ERG  IND-like-PRS-SP  G_AN-ABS  fisherman-DEF-SG</p>
	<p class="roman">keilo          <emph>lau</emph>                    Ø-edamè-Ø-Ø                  <emph>ku</emph></p>
	<p class="gloss">REL.ABS  <emph>NEG_START</emph>  IND-dance-PRS-CONT  <emph>NEG_END</emph></p>
	<p class="meaning">I like the fisherman that is <emph>not</emph> dancing.</p>
</div>

<div class="trans">
	<p class="literal">i'kei'lo lau chi'che'zhon dei zhè'ral kei'lo lau e'da'mè ku</p>
	<p class="roman">ikei-Ø-lo                 <emph>lau</emph>                    Ø-chiche-Ø-zhon   dei-Ø             zhèral-Ø-Ø</p>
	<p class="gloss">G_AN.1-SG-ERG  <emph>NEG_START</emph>  IND-like-PRS-SP  G_AN-ABS  fisherman-DEF-SG</p>
	<p class="roman">keilo          <emph>lau</emph>                    Ø-edamè-Ø-Ø                  <emph>ku</emph></p>
	<p class="gloss">REL.ABS  <emph>NEG_START</emph>  IND-dance-PRS-CONT  <emph>NEG_END</emph></p>
	<p class="meaning">I <emph>don't</emph> like the fisherman that is <emph>not</emph> dancing.</p>
</div>


### Phrasal Negation

"I dont see the pencils" => "I LAU see pencil(s?) KU
vs
"I see no pencils" => "I see LAU pencil(s?) KU
				 

### Double Negation

"I dont see nothing" => "I LAU see anything KUN" or "I see NEG-anything"
"It is false that I see nothing, I DO see something" => "I LAU see NEG-anything KUN

### Pluralization of Negation

"There are no pencils" or "There is no pencil"
"There are no pencils" => ? revisar Nouns/Countability

## Interrogative Clauses

Uso del interrogative mood!

### Yes/No Questions & Alternative Questions

"Does he like it?" => He INT-likes it PART  + INTONATION
"Does he not like it?" => He INT-likes it PART2   + INTONATION
"Does he like A, B, or C?" => He likes A, B, or C PART3  + INTONATION  

### Content Questions

question words, in situ postioning ("The girl is eating meat" => "The girl is eating WHAT")

## Relative Clauses 

Adèkora features relative pronouns in order to introduce a relative clause. Relative clauses are appended immediately after the modified noun phrase (and before the corresponding verb phrase) with no notation in between. The bounded noun phrase that is present in both clauses is always referred to using a case-dependent relative pronoun in the subordinate clause. Therefore, relative clauses appear as common noun phrases with a particular pronoun somewhere in the phrase.

Relative pronoun are only dependent on the case of the noun phrase, with one pronoun per case as indicated in the following table:

<table class="common-table">
	<tr>
		<td class="header" colspan="5">Relative Pronouns by Noun Case</td>
	</tr>
	<tr>
		<td class="header">Ergative</td>
		<td class="header">Absolutive</td>
		<td class="header">Dative</td>
		<td class="header">Genitive</td>
		<td class="header">Locative</td>
	</tr>
	<tr>
		<td>kzhà</td>
		<td>keilo</td>
		<td>kekeicho</td>
		<td>kexeiche</td>
		<td>kidàchek</td>
	</tr>
</table>

Relative clauses can appear in many parts of speech: in the subject (Ergative, Accusative and Genitive noun phrases), direct object and indirect object,  These pronouns allow the relative clauses to convey many meanings. Some examples are listed below.

#### Base Main Clause Example

<div class="trans">
	<p class="literal">dei'lo don'ma'kem ni'pa'le dei ki'kon</p>
	<p class="roman">dei-lo             donmakem-Ø-Ø     Ø-nipale-Ø-Ø                     dei-Ø             kikon-Ø-Ø</p>
	<p class="gloss">G_AN-ERG  governor-DEF-SG  IND-observe-PRS-CONT  G_AN-ABS  miner-DEF-SG  </p>
	<p class="meaning">The governor is looking at the miner.</p>
</div>

#### Ergative Relative Clause Example


<div class="trans">
	<p class="literal">dei'lo don'ma'kem kzhà bai'kel'zham'zhon dei mo're <br /> ni'pa'le dei ki'kon</p>
	<p class="roman">dei-lo            donmakem-Ø-Ø      <emph>kzhà              Ø-baikel-zham-zhon  dei-Ø            more-Ø-Ø</emph> </p>
	<p class="gloss">G_AN-ERG  governor-DEF-SG  <emph>REL.ERG     IND-calm-PST-SP     G_AN-ABS  dog-DEF-SG</emph>  </p>
	<p class="roman">Ø-nipale-Ø-Ø                     dei-Ø             kikon-Ø-Ø</p>
	<p class="gloss">IND-observe-PRS-CONT  G_AN-ABS  miner-DEF-SG</p>
	<p class="meaning">The governor <emph>who calmed the dog</emph> is looking at the miner.</p>
</div>

#### Absolutive Relative Clause Example

<div class="trans">
	<p class="literal">dei'lo mo're dei'lo don'ma'kem bai'kel'zham'zhon kei'lo <br /> ni'pa'le dei ki'kon</p>
	<p class="roman">dei-lo             more-Ø-Ø     <emph>dei-lo            donmakem-Ø-Ø      Ø-baikel-zham-zhon keilo</emph> </p>
	<p class="gloss">G_AN-ERG  dog-DEF-SG <emph>G_AN-ERG governor-DEF-SG  IND-calm-PST-SP     REL.ABS</emph>  </p>
	<p class="roman">Ø-nipale-Ø-Ø                     dei-Ø             kikon-Ø-Ø</p>
	<p class="gloss">IND-observe-PRS-CONT  G_AN-ABS  miner-DEF-SG</p>
	<p class="meaning">The dog <emph>that the governor calmed</emph> is looking at the miner</p>
</div>

#### Genitive Relative Clause Example

<div class="trans">
	<p class="literal">dei don'ma'kem i'kei'lo na'kà'mi'zham'zhon<br />dei mo're ke'xei'che bà'da'bau</p>
	<p class="roman">dei-Ø             donmakem-Ø-Ø     <emph>ikei-Ø-lo                   Ø-nakàmi-zham-zhon      </emph></p>
	<p class="gloss">G_AN-ABS  governor-DEF-SG  <emph>G_AN.1-SG-ERG   IND-love-PST.G_AN-SP    </emph></p>
	<p class="roman"><emph>dei-Ø              more-Ø-Ø       kexeiche</emph>     Ø-bàdabau-Ø-Ø</p>
	<p class="gloss"><emph>G_AN-ABS   dog-DEF-SG   REL.GEN</emph>  IND-become.bored-PRS-CONT</p>
	<p class="meaning">The governor <emph>whose dog I loved</emph> is getting bored.</p>
</div>

#### Dative Relative Clause Example 

<div class="trans">
	<p class="literal">dei don'ma'kem i'kei'lo dau'zham'zhon <br />dem xol'ñol'pal ke'kei'cho bà'da'bau</p>
	<p class="roman">dei-Ø            donmakem-Ø-Ø      <emph>ikei-Ø-lo                   Ø-dau-zham-zhon</emph></p>
	<p class="gloss">G_AN-ABS  governor-DEF-SG  <emph>G_AN.1-SG-ERG   IND-lend-PST.G_AN-SP</emph></p>
	<p class="roman"><emph>dem-Ø          xol-ñol-pal           kekeicho</emph>   Ø-bàdabau-Ø-Ø</p>
	<p class="gloss"><emph>G_AR-ABS  book-INDF-PL   REL.DAT</emph>  IND-become.bored-PRS-CONT</p>
	<p class="meaning">The governor <emph>to whom I lent some books</emph> is getting bored.</p>
</div>

#### Locative Relative Clause Example 

<div class="trans">
	<p class="literal">mi xol'zal ki'dà'chek i'kei'lo dà'men'zham'zhon<br />zhi'ek kom'bem'men'zhon</p>
	<p class="roman">mi-Ø             xolzal-Ø-Ø          <emph>kidàchek    ikei-Ø-lo                  Ø-dàmen-zham-zhon</emph></p>
	<p class="gloss">G_GE-ABS  library-DEF-SG  <emph>REL.LOC  G_AN.1-SG-ERG   IND-meet-PST.G_AN-SP</emph></p>
	<p class="roman"><emph>zhiek-Ø-Ø</emph>             Ø-kombem-men-zhon</p>
	<p class="gloss"><emph>G_AN.2-SG-ABS</emph>  IND-improve-FUT-SP</p>
	<p class="meaning">The library <emph>in which I met you</emph> will thrive.</p>
</div>



