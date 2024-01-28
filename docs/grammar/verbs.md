## Verbs

This section explains concepts core concepts related to verbs, such as agreement with nouns, how Tense, Mood and Aspect is encoded, as well as Valency-changing operations available to verbs.


### Tense

The [Tense](https://en.wikipedia.org/wiki/Grammatical_tense) of the verb **situates the verb in time**. Adèkora has a simple tense system, having only Past, Present and Future. Tense agrees with the [Gender](nouns.md#gender) of the subject (or with the Abstract Gender if the verb is [avalent](#valency)), and is marked by the use of a suffix according to the following table.

<table class="common-table">
	<tr>
		<td class="header" colspan="4">Verb Tense Suffixes</td>
	</tr>
	<tr>
		<td class="header"></td>
		<td class="header">Past</td>
		<td class="header">Present</td>
		<td class="header">Future</td>
	</tr>
	<tr>
		<td class="header left">Animate</td>
		<td><em>-zham</em></td>
		<td>∅</td>
		<td><em>-zhen</em></td>
	</tr>
	<tr>
		<td class="header left">Natural</td>
		<td><em>-xam</em></td>
		<td>∅</td>
		<td><em>-xen</em></td>
	</tr>
	<tr>
		<td class="header left">Artificial</td>
		<td><em>-ñam</em></td>
		<td>∅</td>
		<td><em>-ñen</em></td>
	</tr>
	<tr>
		<td class="header left">Abstract</td>
		<td><em>-zam</em></td>
		<td>∅</td>
		<td><em>-zen</em></td>
	</tr>
	<tr>
		<td class="header left">Geographical</td>
		<td><em>-mam</em></td>
		<td>∅</td>
		<td><em>-men</em></td>
	</tr>
</table>

#### Past

The [**Past Tense**](https://en.wikipedia.org/wiki/Past_tense) conveys that the action or state expressed by the verb belongs to the past. This includes single instances of actions that occured, the previous states of things, habits from the past, etc., which is specified by [Aspect](#aspect).

#### Present

The [**Present Tense**](https://en.wikipedia.org/wiki/Present_tense) conveys that the action or state expressed by the verb is occuring now in some fashion. This includes actions occuring now, current states, habits, etc., which is specified by [Aspect](#aspect).

#### Future

The [**Future Tense**](https://en.wikipedia.org/wiki/Future_tense) conveys that the action or state expressed by the verb has not yet occured and belongs to the future in some fashion. This includes actions expected to occur, predicted states, habits, etc., which is specified by [Aspect](#aspect).

### Aspect

The [Aspect](https://en.wikipedia.org/wiki/Grammatical_aspect) of the verb gives information on how it extends over time, which helps present the action. Aspect is very related to [Tense](#tense), and every combination of Tense-Aspect has a specific meaning. Aspect is marked by the use of a suffix according to the following table.

<table class="common-table">
	<tr>
		<td class="header" colspan="5">Verb Aspect Suffixes</td>
	</tr>
	<tr>
		<td class="header"></td>
		<td class="header">Simple</td>
		<td class="header">Continuous</td>
		<td class="header">Perfect</td>
		<td class="header">Perfect Continuous</td>
	</tr>
	<tr>
		<td class="header left">Affix</td>
		<td><em>-zhon</em></td>
		<td>∅</td>
		<td><em>-pon</em></td>
		<td><em>-pail</em></td>
	</tr>
	<tr>
		<td class="header left">Gloss Abbr.</td>
		<td>SP</td>
		<td>CONT</td>
		<td>PFT</td>
		<td>PFT.CONT</td>
	</tr>
</table>

#### Simple

The **Simple Aspect** is used to describe actions presented as a single point in time, with no particular highlight of the duration or the completion of the action. It very similar to the [Perfective Aspect](https://en.wikipedia.org/wiki/Perfective_aspect) in linguistics.

When used with the **Past Tense**, it describes actions that have happened in the past.

When used with the **Present Tense**, it describes actions currently taking place. It can also be used to express orders in the Indicative Mood.

When used with the **Future Tense**, it describes actions expected to occur in the future, usually highlighting said action's implicances over the present.

TODO add examples.

#### Continuous

The **Continuous Aspect** is used to emphasize an action's duration over time, often to compare the action's span with other actions happening before, alongside or after. It is also used with [stative verbs](https://en.wikipedia.org/wiki/Stative_verb) (those that indicate the state of something) and habits. It is very similar to the [Imperfective Aspect](https://en.wikipedia.org/wiki/Imperfective_aspect) in linguistics.

When used with the **Past Tense**, it describes actions that have happened, with particular focus on the duration of the action, what happened during it, or what interrupted the event. (TODO add examples.) It is also used to talk about the state of things in the past, as well as habits from the past.

When used with the **Present Tense**, it describes actions currently taking place, as well as the current state of things and habits.

When used with the **Future Tense**, it describes actions expected to occur in the future, with particular focus on the expected duration of the action, what is expected to happen during the action, or what is expected to interrupt the event. It is also used to talk about the expected state of things in the future, as well as expected habits.

#### Perfect

The **Perfect Aspect** is used to emphasize the effects that an action's completion has over time. This Aspect cannot be used with the **Present Tense** in any Mood.

When used with the **Past Tense**, it describes actions that have occured, with focus on how the past was affected after the action's completion.

When used with the **Future Tense**, it describes actions that are expected to occur, with focus on how the future can be affected after the action's completion.

#### Perfect Continuous

The **Perfect Continuous Aspect** is a combination of both the Perfect and Continuous Aspects in that it is used to emphasize both the verb's completion and duration. This Aspect commonly focuses on what occured after the action or state terminated. This Aspect cannot be used with the **Present Tense** in any Mood.

When used with the **Past Tense**, it describes actions that have occured and previous states, with focus on how the past was affected after the verb's completion. It also allows for greater comparisson with other events occuring alongside the verb than the Perfect Aspect.

Whe used with the **Future Tense**, it describes actions and states that are expected to occur, with focus on how the future can be affected after the verb's completion. It also allows for greater comparisson with other events that are expected to occur alongside the verb than the Perfect Aspect.


### Mood

The [Mood](https://en.wikipedia.org/wiki/Grammatical_mood) of the verb expresses the **attitude of the speaker** towards the action or state expressed. This is useful for separating common speech intents such as wishes, orders, conditional phrases, etc. Mood is marked by the use of a prefix according to the following table.


<table class="common-table">
	<tr>
		<td class="header" colspan="5">Verb Mood Prefixes</td>
	</tr>
	<tr>
		<td class="header"></td>
		<td class="header">Indicative</td>
		<td class="header">Subjunctive</td>
		<td class="header">Optative</td>
		<td class="header">Interrogative</td>
	</tr>
	<tr>
		<td class="header left">Affix</td>
		<td>∅</td>
		<td><em>chil-</em></td>
		<td><em>zhu-</em></td>
		<td><em>meñ-</em></td>
	</tr>
	<tr>
		<td class="header left">Gloss Abbr.</td>
		<td>IND</td>
		<td>SJV</td>
		<td>OPT</td>
		<td>INT</td>
	</tr>
</table>

#### Indicative Mood

The [**Indicative Mood**](https://en.wikipedia.org/wiki/Realis_mood) is used to convey that the speaker considers that the verb expresses a real state of affairs (or will do so, when used with the Future Tense). This Mood also acts as an umbrella category for many other patterns of speech, such as orders, requests, exclamations, reasonings, etc. Its combination with the Tenses and Aspects has been covered in the [Aspect](#aspect) subsections.

#### Subjunctive Mood

The [**Subjunctive Mood**](https://en.wikipedia.org/wiki/Subjunctive_mood) is used to express unreal scenarios as well as conditions and their hypothetical consequences. This Mood can only be used with the Simple and Continuous Aspects in all three Tenses.

When used with the **Past Tense**, it conveys conditional scenarios in which a possible action or state in the past could have affected reality, as well as actions or states that may have occured in the past, arising from a hypothetical scenario. It is used with the **Simple Aspect** for actions and with the **Continuous Aspect** for stative verbs.

When used with the **Present Tense**, it conveys conditional scenarios in which a possible action or state in the present could affect reality, as well as actions or states currently taking place, arising from a hypothetical scenario. It is used with the **Simple Aspect** for actions and with the **Continuous Aspect** for stative verbs.

When used with the **Future Tense**, it conveys actions or states that may have occured in the future, arising from a hypothetical scenario. It is used with the **Simple Aspect** for actions and with the **Continuous Aspect** for stative verbs.

TODO add explanation of conditionals and examples.

#### Optative Mood

The [**Optative Mood**](https://en.wikipedia.org/wiki/Optative_mood) indicates wishes and desired states of affairs. This Mood can only be used with the Simple and Continuous Aspects in all three Tenses.

When used with the **Past Tense**, it expresses a desire for the action or state to have ocurred in the past. It is used with the **Simple Aspect** for actions and with the **Continuous Aspect** for stative verbs.

When used with the **Present Tense**, it expresses a desire for the action or state to be currently effective. It is used with the **Simple Aspect** for actions and with the **Continuous Aspect** for stative verbs.

When used with the **Future Tense**, it expresses a desire for the action or state to occur sometime in the future. It is used with the **Simple Aspect** for actions and with the **Continuous Aspect** for stative verbs.

#### Interrogative Mood

The [**Interrogative Mood**](https://en.wikipedia.org/wiki/Interrogative) is used exclusively in interrogative clauses to indicate that the action or state conveyed by the verb is not actually stated, but is expressed as a request to the listener to confirm the veracity of the verb. Its combination with the Tenses and Aspects is very similar to that of the Indicative Case, but with the question-like meaning aggregated. This means that questions can give focus to the duration or completeness of the verb being asked, in order to place the interrogative clause in context with other actions at the time.

TODO add example.


### Evidentiality

The [Evidentiality](https://en.wikipedia.org/wiki/Evidentiality) of the verb specifies the degree of certainty the speaker has about the action. Evidentiality is optional, and marked by the use of a suffix according to the following table.

<table class="common-table">
	<tr>
		<td class="header" colspan="4">Verb Evidentiality Suffixes</td>
	</tr>
	<tr>
		<td class="header"></td>
		<td class="header">Affix</td>
		<td class="header no-break">Gloss Abbr.</td>
		<td class="header">Usage</td>
	</tr>
	<tr>
		<td class="header left no-break">Canonical</td>
		<td class="no-break"><em>-boi</em></td>
		<td class="no-break">EV.CAN</td>
		<td>Commonly known to be true, obvious, etc.</td>
	</tr>
	<tr>
		<td class="header left no-break">Participative</td>
		<td class="no-break"><em>-mei</em></td>
		<td class="no-break">EV.PAR</td>
		<td>The speaker participated in the action</td>
	</tr>
	<tr>
		<td class="header left no-break">Direct</td>
		<td class="no-break"><em>-knei</em></td>
		<td class="no-break">EV.DIR</td>
		<td>The speaker sensed the action directly (e.g. saw, felt, heard, etc.)</td>
	</tr>
	<tr>
		<td class="header left no-break">Trusted Reportative</td>
		<td class="no-break"><em>-er</em></td>
		<td class="no-break">EV.TR.REP</td>
		<td>The speaker indirectly obtained information about the action via a reputable source</td>
	</tr>
	<tr>
		<td class="header left no-break">Doubtful Reportative</td>
		<td class="no-break"><em>-kner</em></td>
		<td class="no-break">EV.DF.REP</td>
		<td>The speaker indirectly obtained information about the action via a questionable source</td>
	</tr>
	<tr>
		<td class="header left no-break">Trusted Logical</td>
		<td class="no-break"><em>-zhel</em></td>
		<td>EV.TR.LOG</td>
		<td>The speaker came to the conclusion that the action is real and is confident of its veracity</td>
	</tr>
	<tr>
		<td class="header left no-break">Doubtful Logical</td>
		<td class="no-break"><em>-pŕzhel</em></td>
		<td class="no-break">EV.DF.LOG</td>
		<td>The speaker speculates/guesses the action</td>
	</tr>
	<tr>
		<td class="header left no-break">Rhetorical</td>
		<td class="no-break"><em>-dŕzhai</em></td>
		<td class="no-break">EV.RT</td>
		<td>The speaker does not believe in the veracity of the action</td>
	</tr>
</table>

Evidentiality can only be marked when using the [Indicative Mood](#indicative-mood).

### Verb Conjugation

Adèkora morphologically conjugates Verbs in order to mark for [Tense](#tense), [Aspect](#aspect), [Mood](#mood) and optionally [level of evidence](#evidentiality). Each of these categories has their respective list of affixes that do not morphologically interact with each other. The conjugations of Verbs have the following structure:

<div class="center showcase">
	<span> {MOOD}-{VERB}-{TENSE}-{ASPECT}-{EVIDENTIALITY} </span>
</div>

<table class="common-table">
	<tr>
		<td class="header" colspan="4">Verb Mood Prefixes</td>
	</tr>
	<tr>
		<td class="header">Indicative</td>
		<td class="header">Subjunctive</td>
		<td class="header">Optative</td>
		<td class="header">Interrogative</td>
	</tr>
	<tr>
		<td>∅</td>
		<td><em>chil-</em></td>
		<td><em>zhu-</em></td>
		<td><em>meñ-</em></td>
	</tr>
</table>

<table class="common-table">
	<tr>
		<td class="header" colspan="4">Verb Tense Suffixes</td>
	</tr>
	<tr>
		<td class="header"></td>
		<td class="header">Past</td>
		<td class="header">Present</td>
		<td class="header">Future</td>
	</tr>
	<tr>
		<td class="header left">Animate</td>
		<td><em>-zham</em></td>
		<td>∅</td>
		<td><em>-zhen</em></td>
	</tr>
	<tr>
		<td class="header left">Natural</td>
		<td><em>-xam</em></td>
		<td>∅</td>
		<td><em>-xen</em></td>
	</tr>
	<tr>
		<td class="header left">Artificial</td>
		<td><em>-ñam</em></td>
		<td>∅</td>
		<td><em>-ñen</em></td>
	</tr>
	<tr>
		<td class="header left">Abstract</td>
		<td><em>-zam</em></td>
		<td>∅</td>
		<td><em>-zen</em></td>
	</tr>
	<tr>
		<td class="header left">Geographical</td>
		<td><em>-mam</em></td>
		<td>∅</td>
		<td><em>-men</em></td>
	</tr>
</table>

<table class="common-table">
	<tr>
		<td class="header" colspan="4">Verb Aspect Suffixes</td>
	</tr>
	<tr>
		<td class="header">Simple</td>
		<td class="header">Continuous</td>
		<td class="header">Perfect</td>
		<td class="header">Perfect Continuous</td>
	</tr>
	<tr>
		<td><em>-zhon</em></td>
		<td>∅</td>
		<td><em>-pon</em></td>
		<td><em>-pail</em></td>
	</tr>
</table>

<table class="common-table">
	<tr>
		<td class="header" colspan="4">Verb Evidentiality Suffixes</td>
	</tr>
	<tr>
		<td class="header">Canonical</td>
		<td class="header">Participative</td>
		<td class="header">Direct</td>
		<td class="header">Trusted Reportative</td>
	</tr>
	<tr>
		<td><em>-boi</em></td>
		<td><em>-mei</em></td>
		<td><em>-knei</em></td>
		<td><em>-er</em></td>
	</tr>
	<tr>
		<td class="header">Doubtful Reportative</td>
		<td class="header">Trusted Logical</td>
		<td class="header">Doubtful Logical</td>
		<td class="header">Rhetorical</td>
	</tr>
	<tr>
		<td><em>-kner</em></td>
		<td><em>-zhel</em></td>
		<td><em>-pŕzhel</em></td>
		<td><em>-dŕzhai</em></td>
	</tr>
</table>

### Valency

Like in many languages, each of Adèkora's verbs has a [valency](https://en.wikipedia.org/wiki/Valency_(linguistics)) associated, which counts the number of arguments that the verb needs to have in order to be grammatically correct. The following valency types are present in the language:

- **Avalent** verbs take no argument whatsoever, so there is no Subject nor Object in the sentence. TODO add example with "rain".
- **Monovalent** verbs (also called **Intransitive** verbs) take only one argument - the Subject - and no more. It is a common valency for stative verbs and some actions. TODO add example.
- **Divalent** verbs (also called **Transitive** verbs) take two arguments - the Subject and Direct Object - and no more or less. It is a common valency for many actions. TODO add example.
- **Trivalent** verbs (also called **Bitransitive** verbs) take three arguments - the Subject, the Direct Object and the Indirect Object. This valency is rather uncommon, reserved primarily for actions such as TODO add example give.

Some verbs can also be **Ambivalent**, in the sense that they are gramatically correct with multiple valencies. TODO add example.

The valency of a verb needs to be respected in order to convey a grammatically significant meaning. However, Adèkora features common [valency-changing](https://en.wikipedia.org/wiki/Valency_(linguistics)#Changing_valency) operations that can help adapt the valency of verbs to simplify sentences.

#### Passive Voice

The [passive voice](https://en.wikipedia.org/wiki/Passive_voice) is a common alteration of verbs that is also present in English. This operation transforms a **transitive** verb with Subject A and Direct Object P, and transforms the clause such that P becomes the subject S of a new clause. The original Subject A can be dropped, making the new clause **intransitive**. Every transitive verb can be passivized using the **particle *kañ*** before the verb.

TODO add example.

#### Antipassive Voice

The [antipassive voice](https://en.wikipedia.org/wiki/Antipassive_voice) is an alteration of **transitive** verbs, which acts very similar to passive voice, except that instead of dropping the Subject A of the transitive clause, the Direct Object P is dropped instead, rendering a new **intransitive** clause that has Subject S as the original Subject A. This is used to emphasize the agent of the action, and is common when the object of the verb can be inferred from context. Every transitive verb can be antipassivized using the **particle *kam*** before the verb.

TODO add example.

#### Causative Voice

The [causative voice](https://en.wikipedia.org/wiki/Causative#Causative_voice) is an alteration which transforms **intransitive** clauses - with only a Subject S and no Object required - into a new **transitive** clause. This new clause now takes the original Subject S as the Object P, and the agent that causes the original subject to undergo the effects of the verb is promoted to the new required Subject A. Most intransitive verbs can be put in the causative voice using the **particle *mo*** before the verb.

TODO add example.

#### Valency Operation Combining

It is possible to concatenate valency-changing operations in order to express a more precise meaning. When this occurs, the particles are applied from right to left in the order of the operations executed, and concatenated into a single word.

TODO add example the soldier slept => she made-sleep the soldier => the soldier was made-sleep   or   => she made-sleep.

### Examples

Below are some examples with [interlineal gloss](https://www.eva.mpg.de/lingua/resources/glossing-rules.php) to illustrate how verbs work:

TODO add examples.