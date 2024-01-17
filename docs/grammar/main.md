# Adèkora Grammar

This section provides a basic description of the Grammar of Adèkora, covering Morphology (the formation of words) and Syntax (the formation of sentences). The topics are ordered with the intention of putting the simpler and more neccesary concepts first, and then going into finer details. More examples and exceptions are listed in the respective sub-pages. Examples are written using the [romanization system](../phonology/main.md#romanization).


## Word Order

Adèkora follows [SVO Word Order](https://en.wikipedia.org/wiki/Subject%E2%80%93verb%E2%80%93object_word_order), which means that sentences usually have the Subject, then the Verb and lastly the Objejct. This is the same as English, so a sentence such as *"The cat follows her"* would have the words for *cat* (<*kolexa*>), *follow* (<*plau*>) and *her* (<*ilzhàxelem*>) in that same order.

## Gender

The concept of [grammatical gender](https://en.wikipedia.org/wiki/Grammatical_gender) appears in many languages as a way of partitioning nouns into categories. There are five gender classes in Adèkora:

- The **Animate** gender: people and most animals. 
- The **Natural** gender: plants, celestial objects, some living beings.
- The **Artificial** gender: man-made objects and concepts, tools, clothing, culture.
- The **Abstract** gender: intangible ideas, invisible concepts.
- The **Geographical** gender: places and their names.

Every noun in Adèkora falls into one of this categories. Unlike some languages with gender that make an arbitrary classification, Adèkora's genders try to partition the entire noun space in a sensible manner.

Gender is marked with certain affixes in verbs, there is no gender marking for nouns.

## Case

There are four noun cases: 

- **Ergative**, used for subjects of transitive verbs (see [Ergativity](./main.md#ergativity))
- **Aboslutive**, used for subjects of intransitive verbs or direct objects (see [Ergativity](./main.md#ergativity))
- **Dative**, used for recipients of an action
- **Genitive**, used for indicating relation between nouns, commonly possesion

Case is marked using [noun declensions](./main.md#noun-declensions).

## Verb Conjugation

Verbs are conjugated according to four distinct *axes* of meaning:

- **[Mood]((https://en.wikipedia.org/wiki/Grammatical_mood) )**: The modality (*attitude*) of the verb.
- **[Tense](https://en.wikipedia.org/wiki/Grammatical_tense)**: The time reference of the verb.
- **[Aspect](https://en.wikipedia.org/wiki/Grammatical_aspect)**: The relation of the verb to the timeframe of its tense.
- **[Evidentiality](https://en.wikipedia.org/wiki/Evidentiality)**: The veracity of the information conveyed by the verb.

Verbs are conjugated using affixes to mark for one option in every axis. Some axes are not required as they have a default value (such as Evidentiality), and some combinations of axes are disallowed (e.g. marking Evidentiality in the Imperative Mood).

The order of the affixes is as follows:  *mood-* + **root** + *-tense* + *-aspect* + *-evidentiality*. For example, an action such as *"I was told by someone I trust that she was praying today"* could be translated using the verb *lam* (to pray) like: *lamximzhoker* (*<no mark\>-lam-xim-zhok-er*), and so the verb is conjugated using the Indicative mood, Near Past tense, Simple aspect, Trusted Reportative evidence.

### Verb Mood

The mood of the verb expresses the **attitude of the action** expressed, in order to differentiate if an action stated has actually happened, is an order, a hypothetical scenario, etc.

<table class="common-table">
	<tr>
		<td class="header left">Mood</td>
		<td class="header">Affix</td>
		<td class="header">Usage</td>
	</tr>
	<tr>
		<td class="header left">Indicative</td>
		<td>No&nbsp;mark</td>
		<td>Covers all other mood uses (known actions, wishes, doubts, etc.)</td>
	</tr>
	<tr>
		<td class="header left">Imperative</td>
		<td><em>zhuk-</em></td>
		<td>When talking about orders</td>
	</tr>
	<tr>
		<td class="header left">Conditional</td>
		<td><em>chil-</em></td>
		<td>When talking about hypothetical actions that conditionally depend upon other conditions</td>
	</tr>
	<tr>
		<td class="header left">Interrogative</td>
		<td><em>men-</em></td>
		<td>When asking questions about actions</td>
	</tr>
</table>


### Verb Tense

The tense of the verb **situates the action** in a moment before, after or in the present. Both Past an Future have Near and Remote variants to further discern the distance of the action to the present.

<table class="common-table">
	<tr>
		<td class="header left">Tense</td>
		<td class="header">Affix</td>
		<td class="header">Usage</td>
	</tr>
	<tr>
		<td class="header left">Present</td>
		<td>No&nbsp;mark</td>
		<td>Actions occuring at the present time of discourse (now)</td>
	</tr>
	<tr>
		<td class="header left">Near Past</td>
		<td><em>-xim</em></td>
		<td>Actions that have occured in the past, usually no older than today</td>
	</tr>
	<tr>
		<td class="header left">Remote Past</td>
		<td><em>-xil</em></td>
		<td>Actions that have occured in the past, usually before today</td>
	</tr>
	<tr>
		<td class="header left">Near Future</td>
		<td><em>-chen</em></td>
		<td>Actions ocurring in the future, usually in the same day as the present</td>
	</tr>
	<tr>
		<td class="header left">Remote Future</td>
		<td><em>-cher</em></td>
		<td>Actions ocurring in the future, usually after today</td>
	</tr>
</table>

### Verb Aspect

The aspect of the verb relates the verb's tense with its extension over time, providing more detail about the nature of the action. A general description of each aspect is provided, but the concrete meaning is specific to its usage with a tense.

<table class="common-table">
	<tr>
		<td class="header left">Aspect</td>
		<td class="header">Affix</td>
		<td class="header">Usage</td>
	</tr>
	<tr>
		<td class="header left">Simple</td>
		<td><em>-zhok</em></td>
		<td>Focus on action as a point in time</td>
	</tr>
	<tr>
		<td class="header left">Continuous</td>
		<td>No&nbsp;mark</td>
		<td>Focus on action as it continues into the time of reference</td>
	</tr>
	<tr>
		<td class="header left">Perfect</td>
		<td><em>-pail</em></td>
		<td>Focus on effect of action's being complete at the time of reference</td>
	</tr>
	<tr>
		<td class="header left">Perfect Continuous</td>
		<td><em>-pok</em></td>
		<td>Focus on effect of action's progress at the time of reference</td>
	</tr>
</table>

### Verb Evidentiality

The evidentiality of the verb specifies the degree of certainty the speaker has about the action.

<table class="common-table">
	<tr>
		<td class="header left">Evidence Type</td>
		<td class="header">Affix</td>
		<td class="header">Usage</td>
	</tr>
	<tr>
		<td class="header left">Canonical</td>
		<td><em>-boi</em></td>
		<td>Commonly known to be true, obvious, etc.</td>
	</tr>
	<tr>
		<td class="header left">Participative</td>
		<td><em>-mei</em></td>
		<td>The speaker participated in the action</td>
	</tr>
	<tr>
		<td class="header left">Direct</td>
		<td>No&nbsp;mark</td>
		<td>The speaker sensed the action directly (e.g. saw, felt, heard, etc.)</td>
	</tr>
	<tr>
		<td class="header left">Trusted Reportative</td>
		<td><em>-er</em></td>
		<td>The speaker indirectly obtained information about the action via a reputable source</td>
	</tr>
	<tr>
		<td class="header left">Doubtful Reportative</td>
		<td><em>-kner</em></td>
		<td>The speaker indirectly obtained information about the action via a questionable source</td>
	</tr>
	<tr>
		<td class="header left">Trusted Logical</td>
		<td><em>-zhel</em></td>
		<td>The speaker came to the conclusion that the action is real and is confident of its veracity</td>
	</tr>
	<tr>
		<td class="header left">Doubtful Logical</td>
		<td><em>-pŕzhel</em></td>
		<td>The speaker speculates the action is real, guesses, speculation, etc.</td>
	</tr>
	<tr>
		<td class="header left">Rhetorical</td>
		<td><em>-dŕzhai</em></td>
		<td>The speaker does not believe in the veracity of the action</td>
	</tr>
</table>

## Agglutinativity

As an [**agglutinative language**](https://en.wikipedia.org/wiki/Agglutinative_language), Adèkora uses many **affixes to mark for aspects of grammar** such as person, number, evidentiality, completion of an action, etc. This affixes are also used to derive complex words from simpler roots.

## Noun Declensions

### Case

The four [noun cases](main.md#case) (**Ergative**, **Aboslutive**, **Dative** and **Genitive**) are marked with particles or suffixes as shown below, for both nouns and pronouns.

<table class="common-table">
	<tr>
		<td class="header" colspan="4">Noun Cases</td>
	</tr>
	<tr>
		<td class="header left">Case</td>
		<td class="header">Marked with</td>
		<td class="header">Example</td>
	</tr>
	<tr>
		<td class="header left">Ergative</td>
		<td>particle <em>lo</em></td>
		<td>lo zhàke, lo xiroka</td>
	</tr>
	<tr>
		<td class="header left">Absolutive</td>
		<td>Not marked</td>
		<td>zhàke, xiroka</td>
	</tr>
	<tr>
		<td class="header left">Dative</td>
		<td>suffix <em>-kim</em></td>
		<td>zhàkekim, xirokakim</td>
	</tr>
	<tr>
		<td class="header left">Genitive</td>
		<td>suffix <em>-dem</em></td>
		<td>zhàkedem, xirokadem</td>
	</tr>
</table>

### Plurality

Plurality is divided between Singular and Plural, like in English. Singularity is not marked, and Plurality is marked with the suffix *-pal* for nouns (e.g. *"piŕou, piŕoupal"* ) and the suffix *-lem* for pronouns (e.g. *"ñà, ñàlem"*).

## Pronouns

Adèkora has pronouns marked for **person** (1°, 2° or 3°), **plurality** (singular or plural), **grammatical gender** (animate, natural, artificial, abstract or geographical), and in some cases **formality** (formal or informal). The below table illustrates all existing pronouns:

<table class="common-table">
	<tr>
		<td class="header" colspan="7">Pronouns in Ergative Case</td>
	</tr>
	<tr>
		<td class="header left">Gender</td>
		<td class="header">1° s.</td>
		<td class="header">1° pl.</td>
		<td class="header">2° s.</td>
		<td class="header">2° pl.</td>
		<td class="header">3° s.</td>
		<td class="header">3° pl.</td>
	</tr>
	<tr>
		<td class="header left">Animate (formal)</td>
		<td>ixei</td>
		<td>ixelem</td>
		<td>zhiex</td>
		<td>zhiexlem</td>
		<td>zhàxe</td>
		<td>zhàxelem</td>
	</tr>
	<tr>
		<td class="header left">Animate (informal)</td>
		<td>ikei</td>
		<td>ikelem</td>
		<td>zhiek</td>
		<td>zhieklem</td>
		<td>zhàke</td>
		<td>zhàkelem</td>
	</tr>
	<tr>
		<td class="header left">Natural</td>
		<td>-</td>
		<td>-</td>
		<td>uxem</td>
		<td>uxelem</td>
		<td>uxà</td>
		<td>uxàlem</td>
	</tr>
	<tr>
		<td class="header left">Artificial</td>
		<td>-</td>
		<td>-</td>
		<td>ñiem</td>
		<td>ñielem</td>
		<td>ñà</td>
		<td>ñàlem</td>
	</tr>
	<tr>
		<td class="header left">Abstract</td>
		<td>-</td>
		<td>-</td>
		<td>zharem</td>
		<td>zharelem</td>
		<td>zhà</td>
		<td>zhàlem</td>
	</tr>
	<tr>
		<td class="header left">Geographical</td>
		<td>-</td>
		<td>-</td>
		<td>midem</td>
		<td>midelem</td>
		<td>midà</td>
		<td>midàlem</td>
	</tr>
</table>

Pronoun marking uses affixes to indicate certain aspects; for example, for the Animate pronouns, the affix *-x-* is used in turn of *-k-* to indicate formality. Similarly, the suffix *-lem* indicates plurality.

The first person pronouns only exist for the Animate gender, since the use case of talking as an inanimate object is considered too contrived.

### Other Noun Cases

As discussed in [Noun Cases](main.md#case), pronouns for all other cases are formed with their respective particles/suffixes.

## Verb Inflections

### a

## Ergativity

Unlike English, which uses [nominative-accusative alignment](https://en.wikipedia.org/wiki/Nominative–accusative_alignment), Adèkora uses **[ergative-absolutive alignment](https://en.wikipedia.org/wiki/Ergative–absolutive_alignment)**. The main difference is the usage of the two grammatical cases present (which in English would correspond to *"I"* and *"me"*).

In English, the nominative case (e.g. *"I"*) is used for the subject of all verbs, [transitive](https://en.wikipedia.org/wiki/Transitive_verb) or [intransitive](https://en.wikipedia.org/wiki/Intransitive_verb). Therefore, we use *"I"* for both *"I saw her"* and *"I slept"*. The accusative case (e.g. *"me"*) is reserved only for direct objects of transitive verbs (e.g. *"He loved me"* instead of *"He loved I"*).

However, Adèkora uses the **Absolutive** case (what would be the nominative) for the **subject of intransitive verbs** and **direct objects**, whereas the **Ergative** case is used only for **subjects of transitive verbs**. Therefore, we use *ikei* (e.g. *"I"*) for both *ikei lamTODO* (*"I pray"*) and *lo zhàke plauTODO ikei* (*"She followed me"*, literally *"her followed I"*). Note the *lo* particle for *lo zhàke*.
