## Semantical Intonation

Adèkora uses [word intonation](https://en.wikipedia.org/wiki/Intonation_(linguistics)) in a manner similar to English and Spanish. 

### Questions

By default, pitch tends to start somewhat high and slowly lower during a sentence. However, questions commonly have pitch suddenly increase at the final word of the sentence. 

Like in English, there are different pitch patterns to convey the type of question even when the underlying statement is the same. The most common question types used are the following:

- **Yes/No Questions** expect the answer to be either affirmative or negative. They start at a low pitch and gradually increase, reaching its highest at the end of the sentence.
- **Alternative Questions** provide a range of two or more expected answers. These answers are highlighted using a sudden high pitch.
- **"Wh" Questions** ask about aspects like the English "Wh-" words (What/Why/How/etc.). The particle that represent the corresponding "Wh" word in English is highlighted with a sudden high pitch. Unlike English, tone does not keep low after such word, and instead gradually goes up again very much like Yes/No Questions.

Considering the following examples:

- TODO ↘︎you went store or ↗︎park? (Did you went to the store or the park?) as in "Did you went to any of those two places?"
- TODO ↘︎you went ↗︎store ↘︎or ↗︎park? (Did you went to the **store** or the **park**?) as in "Which one of the two did you go to?"
- TODO  ↗︎how ↘︎you went store or ↗︎park? (**When** did you go to the store or the park?) specifically asking about when that happened.


### Focusing

Outside of [questions](intonation.md#questions), a sudden high pitch can be used to stress certain words of sentences, therefore changing the focus of the statement. This is very similar to English, where "I saw a man there" changes meaning depending on which word the high pitch is placed on. 

## Syllable Stress

Adèkora features a [fixed stress system](https://en.wikipedia.org/wiki/Stress_(linguistics)), which means that there is a logical pattern used to select which syllable obtains primary stress, rather than an assigned stress for every particular word. 

To deduce the stress of any given word, the concept of **strong syllables** is used. We categorize as a **strong syllable** any syllable that meets any of the following conditions:

- Its vowel component is either <x>à</x> or <x>è</x>
- Its onset component is three consonants long, as specified by the possible clusters of [Syllable Clustering](phonotactics.md#syllable-clustering)
- Its coda component is geminated, as specified by the rules of [Consonant Repetition](phonotactics.md#consonant-repetition)

With that definition, the process to obtain its stress is the following:

1. If the word contains any **strong syllables**, primary stress corresponds to the leftmost strong syllable. Secondary stress is applied to all other strong syllables.
2. If the word does not contain any **strong syllable**, divide the syllables into [Feet](https://en.wikipedia.org/wiki/Foot_(prosody)#Classical_meter). To do this, start making groups of two syllables, starting from the left. (For example, *bu-ke-dem* would be divided like *(bu-ke)-dem*; one Foot and a solitary syllable). Primary stress corresponds to the left syllable of the rightmost Foot. If there are other complete Feet, the left syllable of each receives secondary stress.

Here are some examples of stress for various words; Feet are marked using parentheses, and strong syllables are marked in **bold**. Primary and secondary stress are marked using ' and , respectively.

- 'kam *(one syllable)*
- ('u-xo) *(two syllables, no strong syllable)*
- ('chi-ki)-zal *(three syllables, no strong syllable)*
- (,a-de)-('kim-zhe) *(four syllables, no strong syllable)*
- '**kà**-lam *(two syllables, penultimate strong syllable)*
- i-'**przhei** *(two syllables, last strong syllable)*
- a-'**dè**-ko-ra *(single strong syllable)*
- ka-'**là**-pu-,**xazhː**-me *(two strong syllables)*

