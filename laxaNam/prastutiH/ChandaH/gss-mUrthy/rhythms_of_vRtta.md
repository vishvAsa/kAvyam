+++
title = "Rhythms of vRtta"
+++

An Investigation of Rhythms Characterizing Sanskrit vṛtta-śloka-s.

G S Srinivasa Murthy


## Abstract

_The rhythmic essence of a set of Metres can be captured and encapsulated in what is called an Adjacency Table which generates not only the Metres on which the Table is based  but also other recognized Metres as well as a large number of entirely new rhythmic Metres. Starting from clustering different Metres around a comparatively long common sequence of guru-s and laghu-s the paper proceeds to work out a small set of ‘rhythm-elements’ the stringing of which in different orders as per the Adjacency Table yields different Metres. Results on 4 sets of Base Metres are presented. _

**_[Key words: Sanskrit prosody, chandas, prosodic Metre, rhythm, rhythm-element, adjacency table]_**



## 1.0 Introduction:
 A person who has repeatedly listened to, read or composed a Sanskrit vṛtta śloka becomes familiar with what may be loosely called the “rhythm” of the vṛtta. This familiarity with the rhythm of the vṛtta enables him to detect any violation committed by the reader or the poet in the metrical structure. This paper reports the results of a study directed at sets of rhythmic and popular vṛtta-s.  The study indicates how  the rhythmic essence of a set of vṛtta-s can be captured and encapsulated in what is called an Adjacency Table which generates not only the vṛtta-s on which the Table is based  but also other recognized vṛtta-s as well as a large number of entirely new rhythmic vṛtta-s. Before we proceed with the subject matter, we give a very brief introduction to Sanskrit Prosody for the benefit of general readers. For a detailed study of the subject, books listed at 1 and 2, both in Sanskrit, in Section 8.0 are recommended.

## 2.0 Principles of Sanskrit prosody:
 The principles of Sanskrit prosody can be stated as follows:



1. The time duration of a short vowel (hrasva svara) when pronounced is called ‘laghu’ and a ‘laghu’ is taken to be of one mātrā duration, where mātrā is a unit of time undefined in absolute terms.
2. The time duration of a long vowel (dīrgha svara) is called ‘guru’ and a ’guru’ is taken to be 2 mātrās. The traditional symbols for laghu and guru are an ‘inverted cap’ and a dash (-). We shall abandon these inconvenient symbols and we shall meaningfully indicate a laghu by ‘1’ and a guru by ‘2’.
3. A consonant (vyañjana) by itself is of zero mātrā duration. A conjunct consonant (saṃyukta-akṣara) which is a sequence of consonants without any vowels intervening is also treated as a consonant and therefore of zero duration
4. A vowel, long or short, followed by anusvāra or visarga is treated to be a guru.
5. A syllable (akṣara) could be 1.a vowel (mostly at the beginning of a word) or 2. a consonant followed by a vowel or 3. a vowel followed by visarga/anusvāra or 4. a consonant followed by a vowel followed by visarga/anusvāra
6. A syllable which precedes a conjunct-consonant (saṃyuktākṣara) is taken to be “guru” and hence of duration 2 mātrās.
7. A verse in Sanskrit has 4 quarters. A quarter can be taken as a line of verse. Depending on the structure of the verse, a verse will fall into one of these categories.
   1. Anuṣṭup which has 8 syllables in a quarter with certain constraints.
   2. vṛtta-s like ārya/giti based on what is called “mātrāgaṇa system”. In this system, a 3-mātragaṇa has a total of 3 mātra-s consisting of any of the following combinations: laghu-laghu-laghu (1-1-1), guru-laghu(2-1) or laghu-guru(1-2). A 4-mātra gaṇa has a total of 4 mātrā-s having any one of the following combinations: 1-1-1-1, 2-2, 2-1-1,1-2-1 or 1-1-2. 5-mātrā and 6-mātrā gaṇas can also be defined similarly. In a mātrā-gaṇa based verse, a quarter of a verse is built up of a sequence of mātrā-gaṇas. Although mātrā-gaṇa based verses are extensively used in Prākṛt poetry, their use is limited to a few Metres like āryā, giti etc in Sanskrit.
   3. In akṣaragaṇa-based system, a quarter of a verse consists of a rigid sequence of laghu-s and guru-s. For example, indravajrā which has 11 syllables in a quarter is defined by the following sequence of laghu-s and guru-s. 22122112122. We shall call this binary string the characteristic string of indravajrā. To facilitate memorizing this sequence, our ancient prosodists adopted a coding system by bunching 3 consecutive syllables as follows:  221**-**221-121-22.  As each syllable is prosodically 1 or 2, a sequence of 3 syllables has 8 variants: 111,112,121,122,211,212,221 and 222. These 8 triads form the akṣara-gaṇa and each triad is identified by an alphabet as follows: 1. ‘ya’ gaṇa: laghu-guru-guru (122)-Ex: यशस्विन्; 2.’ma’ gaṇa: guru-guru-guru(222)-Ex:माजाने; 3.‘ta’ gaṇa:guru-guru-laghu(221)-Ex:तप्तोऽस्मि; 4. ‘ra’ gaṇa:guru-laghu-guru(212)-Ex:राम हे; 5. ‘ja’ gaṇa:laghu-guru-laghu(121)-Ex:जनेश; 6. ‘bha’ gaṇa:guru-laghu-laghu(211)-Ex:भार्गव; 7. ‘na’ gaṇa:laghu-laghu-laghu(111)-Ex:निमिष; and 8. ‘sa’ gaṇa:laghu-laghu-guru(112)-Ex:सुमते. As per this coding, indravajrā can be represented as ततजगुगु where गु stands for गुरु. If all the 4 quarters of a verse follow a common characteristic string, the verse is a sama-vṛtta; if the odd quarters follow one characteristic string and the even quarters a different but compatible characteristic string, the verse is a viṣama-vṛtta.
8. The last syllable of a quarter is treated a guru, even if it is inherently a laghu.
9. Points of pause called ‘yati’ where a word has to end are prescribed for certain Metres. Taking into account all the rules that determine whether a syllable is a guru or laghu it is possible to write a computer program that identifies the Metre when a quarter of a verse is input.[^1]

This paper deals with only akṣaragaṇa vṛttas and does not deal with anuṣṭup or mātrāgaṇa-based vṛtta-s. The author has dealt with anuṣṭup in an earlier paper[^2]. In what follows we shall use the word Metre to convey a specific characteristic string generally denoted by a name like vasantatilakā or sragdharā etc.


## 3.0 Rhythm in akṣaragaṇa vṛtta-s


Anyone who has often recited or listened to an akṣaragaṇa-vṛtta verse of a particular Metre cannot fail to perceive a sort of a rhythm characteristic of that Metre. It is not that a beat of a certain duration is perceived although while reciting certain Metres a beat could be perceived. Occurrence of beats with its internal structure of लय is dealt in an earlier paper[^3]. The complex stream of laghu-s and guru-s which characterizes the Metre and which has its own points of pause, whether prescribed or not, when listened to or recited repeatedly, causes the listener or reciter to lock on to this complex rhythm and enables him/her to recognize the Metre. 


The point to note is that any random sequence of laghu-s and guru-s does not result in a Metre. Only certain sequences of laghu-s and guru-s have the ability to create a sense of a pleasant though complex rhythm. It is to be stressed that the word ‘rhythm’ does not adequately denote what is being attempted to be explained and that ‘rhythm’ is used in the absence of a more appropriate word. Perhaps this ‘rhythm’ in a Sanskrit Metre is not unlike a ‘raga’ in Indian music. 


It is to be however noted that the origin of this pleasant rhythm cannot be anything other than the binary variations of syllabic durations that go to form the Metre. 


Although books on Sanskrit prosody enumerate and delineate a large number of Metres, not all the Metres specified are equally rhythmic. Poets generally employ 20 to 30 Metres where the number of syllables in a quarter ranges from 10 to 21. These Metres are popular because of their inherent rhythm as it is the rhythm which enables the poet to compose a verse without manually checking if the composed verse meets the specifications of the Metre.


The objective of our investigation into the rhythms of vṛtta-ślokas is to form a set of rules by following which one can define and compose a large set of different rhythmic vṛtta-s. The investigation comprises of the following components:



1. General observations on a small set of rhythmically related popular vṛtta-s.
2. Forming a proposition based on our observations and working out a detailed set of rules based on the proposition which enable us to construct a larger set of rhythmic vṛtta-s.
3. Checking to see to what extent the rules formed meet the objective.

It needs to be noted that our investigation does not enable us to define the ‘rhythm’ of a vṛtta śloka and that it only attempts to provide a method to construct rhythmic vṛtta ślokas.



## 4.0 General observations



1. The akṣaragaṇa system of coding eminently meets the objective of specifying a Metre. But the actual variations of laghu-s and guru-s which create the rhythm get lost in the coded form. For example let us look at upendravajrā and indravajrā Metres. Upendravajrā is ja-ta-ja-gu-gu and indravajrā is ta-ta-ja-gu-gu. The coded specifications of the two look very different. But the two Metres are rhythmically so near to each other that poets mix them up often in a single verse. ( Such mixing up is allowed and such hybrids form upajāti vṛtta-s.) The nearness of the Metres is quite evident if we write out the Metre in laghu-s and guru-s (characteristic string):

22122112122 indravajrā


12122112122 upendravajrā


As our investigation relates to the rhythm of a Metre, we need to look at a Metre at the level of its characteristic string only.

2. A person familiar with Sanskrit Metres would be aware that several of the Metres end in a similar manner. To avoid dealing with bland and boring binary sequences comprising ‘1’ and ‘2’ we shall use standardised Sanskrit phrases. Obviously our interest is only in the prosodic content of the phrase and not its semantic content:

शालिनी: कंसारे हे मध्वरेपाहिशौरे[^4]. [a][^5]


मालिनी: मधुमथन हरे हे मध्वरेपाहिशौरे.[b] 


भुजङ्गप्रयातम्:हरे हे हरे मध्वरेपाहिशौरे.[c]


मन्दाक्रान्ता: कंसारे हे मधुमथन हे मध्वरेपाहिशौरे.[d]


स्रग्धरा: कंसारे हे हरे हे मधुमथन हरे मध्वरेपाहिशौरे [e]


All the above 5 popular Metres end in a common phrase ‘मध्वरेपाहिशौरे’. It goes without saying that this 7-syllable long phrase contributes significantly to the rhythmic quality of these Metres. One cannot also fail to notice that certain phrases are repeatedly employed. In fact, these 5 Metres are made up of the following five phrases only: कंसारे, मधुमथन, हरे, हे and मध्वरेपाहिशौरे. It is to be stressed that these phrases integrally participate in the perception of the rhythm of each of the Metres without violating accepted points of pause whether prescribed or not.


## 5.0 A proposition


Now a thought occurs. Can we treat these 5 phrases as rhythm elements and based on these 5 Metres, which we shall call ‘Base Metres’, work out what could be the rules which these rhythm elements follow in these 5 rhythmic lines of verse?


In order to explore further, we set up what we call an “Adjacency Table” which is a convenient way of recording which phrase comes after which phrase in these 5 Metres.


Table 1: Adjacency Table

| next phrase->    | कंसारे | मध्वरेपाहिशौरे | मधुमथन | हरे  | हे    |
|------------------|------|-------------|-------|-----|------|
| phrase           |      |             |       |     |      |
| कंसारेade          | 0    | 0           | 0     | 0   | 1ade |
| मध्वरेपाहिशौरेabcde | 0    | 0           | 0     | 0   | 0    |
| मधुमथनbde         | 0    | 0           | 0     | 1be | 1d   |
| हरेbcde           | 0    | 1c          | 0     | 0   | 1bce |
| हेabcde           | 0    | 1abde       | 1d    | 1ce | 0    |

In this table each rhythm element has a dedicated row and a dedicated column. ‘1’ in a cell indicates that in one or more of these 5 Metres the phrase to which the column of the cell is dedicated comes immediately after the phrase to which the row of the cell is dedicated. 


One can read from the Table that



* कंसारे comes only as the beginning phrase of a Metre [कंसारे column is all zeros]
* मध्वरेपाहिशौरे comes only as the end phrase of a Metre [मध्वरेपाहिशौरे row is all zeros.]
* मध्वरेपाहिशौरे comes only after हरे or हे.
* मधुमथन comes only before हे.
* स्रग्धरा does not provide any unique adjacency and therefore redundant for constructing the Adjacency Table. The number of Base Metres becomes four.

The same information can be shown in this way:


Table 2:

| phrase      | next phrase  |
|-------------|--------------|
| कंसारे        | हे            |
| मध्वरेपाहिशौरे | -            |
| मधुमथन       |  हरे          |
|             | हे            |
| हरे          |  मध्वरेपाहिशौरे |
|             |  हे           |
| हे           | मध्वरेपाहिशौरे  |
|             | मधुमथन        |
|             | हरे           |


What we have called here Adjacency Table is in fact an Adjacency Matrix[^8] in the mathematics of graphs (graph theory). The syntaxes of languages, natural or artificial can be represented by directed graphs where each category of words (noun, verb, preposition, adjective, adverb etc. for English) forms a node. The syntax or grammar of the rhythm elements which is brought out by the Adjacency Table can also be visually represented by a directed graph as shown in Fig.1.(Adjacency Diagram.) We can construct Metres, which are the analogue of sentences, by following the permissible sequences in Fig.1. The existence of endless loops (हरे->हे->हरे--- and हे->मधुमथन->हरे->हे--) in the particular graph necessitates imposing an artificial condition that a constructed Metre may not have more than one or two instances of a loop. 


There are various ways for working out the permissible Metres based on the Adjacency Table. A short computer program can be written. They can be worked out on an XL-sheet. Here for the sake of understanding we demonstrate a manual method which is illuminating.


We first build up all permissible dyads of rhythm elements and categorize into start-dyads(आद्ययुग्म), middle-dyads(मध्ययुग्म) and end-dyads (अन्त्ययुग्म). (Table 3). 


Table 3

| आद्ययुग्मम्     | मध्ययुग्मम्                         | अन्त्ययुग्मम्          |
|-------------|---------------------------------|-------------------|
| क१-कंसारे हे   | -                               | च१-हे मध्वरेपाहिशौरे  |
| क२-मधुमथन हरे | ग१-हे हरे                         | च२-हरे मध्वरेपाहिशौरे |
| क३-हरे हे     | ग२-हे मधुमथन                      |                   |
|             | ग३-मधुमथन हे                      |                   |
|             | ग४-हरे हे                         |                   |
|             | ग५-मधुमथन हरे                     |                   |
|             | ग२ग३-हे मधुमथन हे                  |                   |
|             | ग२ग५-हे मधुमथन हरे                 |                   |
|             | ग१ग४-हे हरे हे                     |                   |
|             | ग२ग५ग४-हे मधुमथन हरे हे             |                   |
|             | ग४ग२ग३-हरे (हे)+हे (मधुमथन)+मधुमथन हे |                   |



We shall construct Metres by joining these dyads such that the second phrase of the dyad is identical with the first phrase of the succeeding dyad. We shall call this the compatibility rule. A constructed Metre starts with a beginning dyad and ends with an ending dyad. [This is an additional restriction not inherent in the Adjacency Table.] The middle dyads can be joined among themselves as long as they meet the compatibility rule. While joining two dyads, we drop the second phrase of the first dyad as it is a repetition. 


The method of using an Adjacency Table to construct Metres is based on the premise that preserving the adjacency observed in a closely related set of rhythmic metres ensures that any Metre so constructed is also rhythmic. It may be also noted that the Adjacency Table is shorn of the names of the Base Metres. Each rhythm element has an affinity to certain other elements in becoming their neighbour and this affinity is so to say captured in the Adjacency Table. To the extent that the rhythm in a line of verse may be also dependent upon not only an element’s neighbour but also the other neighbour of its neighbour, we are making a first order of approximation. For example, in स्रग्धरा Metre,


कंसारे हे हरे हे मधुमथन हरे मध्वरेपाहिशौरे, although the fact that मधुमथन is preceded by हे is reflected in the Adjacency Table the fact that the left neighbour of हे is हरे is not taken into account[^10]. 


In constructing the Metres, we shall take note of the following points:



1. The number of syllables in a Metre to be between 10 and 21 syllables.
2. Traversing any loop as seen in the Adjacency diagram to be not more than two times.
3. The beginning and end phrases of a Metre to be restricted to those seen in the Base Metres.

The constructed Metres turn out as follows:


१ कंसारे (हे)+हे मध्वरेपाहिशौरे –क१च१—[शालिनी]


२ कंसारे (हे)+ हे (हरे) + हरे मध्वरेपाहिशौरे –क१ग१च२


३ कंसारे (हे)+हे (हरे)+हरे(हे)+हे मध्वरेपाहिशौरे—क१ग१ग४च१—[बिंबालक्ष्यम्[^11]  ]


४ कंसारे (हे)+हे (मधुमथन)+मधुमथन (हे)+हे मध्वरेपाहिशौरे—क१ग२ग३च१—[मन्दाक्रान्ता  ]


५ कंसारे (हे) +हे (मधुमथन)+मधुमथन (हरे)+ हरे मध्वरेपाहिशौरे  -- क१ग२ग५च२ [चन्द्रलेखा  ]


६ कंसारे (हे)+ हे (मधुमथन)+मधुमथन (हरे)+हरे (हे)+ हे मध्वरेपाहिशौरे – 


७ कंसारे (हे)+हे (हरे)+हरे(हे)+हे (मधुमथन)+मधुमथन (हे)+हे मध्वरेपाहिशौरे—


८ कंसारे (हे)+हे (हरे)+हरे(हे)+हे (मधुमथन)+मधुमथन (हरे)+हरे मध्वरेपाहिशौरे—[स्रग्धरा  ]


९ कंसारे (हे)+हे (हरे)+हरे(हे)+हे (मधुमथन)+मधुमथन (हरे)+हरे (हे)+हे मध्वरेपाहिशौरे—


१० मधुमथन (हरे)+ हरे मध्वरेपाहिशौरे –क२च२—[नान्दीमुखी  ]


११ मधुमथन (हरे)+ हरे (हे)+हे मध्वरेपाहिशौरे क२च१—[मालिनी  ]


१२ मधुमथन (हरे)+ हरे (हे)+ हे (मधुमथन)+मधुमथन (हे)+ हे मध्वरेपाहिशौरे--


१३ मधुमथन (हरे)+ हरे (हे)+हे (मधुमथन) +मधुमथन (हरे) + हरे मध्वरेपाहिशौरे—क२ग४ग२ग५च२—


१४ हरे (हे)+ हे मध्वरेपाहिशौरे – क३च१--


१५ हरे (हे) +हे (हरे)+हरे मध्वरेपाहिशौरे- क३ग१च२—[भुजङ्गप्रयातम्  ]


१६हरे (हे)+हे (मधुमथन)+मधुमथन (हे) +हे मध्वरेपाहिशौरे –क३ग२ग३च१--


१७ हरे (हे)+हे मधुमथन (हरे) + हरे मध्वरेपाहिशौरे-- क३ग२ग५च२—


१८ हरे (हे)+हे मधुमथन (हे) + हे मध्वरेपाहिशौरे –क३ग२ग३च१-- 


Let us recapitulate the steps in this process. We gather a set of Metres which have in common a fairly long syllabic sequence. This sequence acts as an anchor or a spine for the rhythm of each of these Metres. We fill up the remaining portion of each Metre with suitable shorter sequences such that they are as long as possible and occur as often as possible. This is based on the following premise. The longer the sequence the larger is its contribution to the over-arching rhythm of the Metre. The longer a common sequence, the greater is the affinity of the Metres. This filling up process does not lead to a unique solution. Depending on the choice, the Metres constructed may vary although all choices lead to the Base Metres.


From a set of only 4 related Metres we constructed an Adjacency Table and this Adjacency Table has yielded 18 different Metres out of which 4 are the Base Metres, 4 are Metres recognized and named by Sanskrit prosodists and the remaining ten are new Metres. It is the contention of the author that the ten new Metres are as rhythmic as the four named Metres. But it would not be a surprise if some scholars and poets whose perceptions would be trained and tuned to the familiar Metres find it difficult to accept the rhythmic quality of the new Metres. It is well recognized that a certain amount of familiarity is an essential component of acceptance and appreciation. 


One can question the purpose of this exercise. “There are enough numbers of elegant and rhythmic Metres. We do not need more Metres. We would rather have more poetry and more poets.” The criticism is well taken. Even if the construction of new rhythmic Metres is treated as unimportant, just the discovery of how by stringing a small set of 5 phrases in a manner specified by the Adjacency Table one can obtain 8 recognized Metres is worth all the effort put in this investigation. 


One can also envisage constructing an Adjacency Table based on akṣara gaṇas. In general, we could have a 11x11(8 gaṇas, 22,12 & 2) Adjacency Table which could encompass every possible Metre. As akṣaragaṇas mechanically dissect a line of verse without any consideration for the natural pauses which carry the essence of the rhythm they are inherently deficient for this exercise.


In the next section we shall show the results of extending this method to cover a larger set of rhythmic vṛtta-s without repeating the explanations. 


## 6.0 Extensions


We give below the various steps detailed in Section 5.0 [ मध्वरेपाहिशौरे group] for three more groups, each group being denoted by the spine rhythm-element: माधवपाहिमां, दयाजलनिधे, and केशवपाहिहरे. For each group we give a. The Base Metres, with the rhythm elements spelt out on which the Adjacency Table is derived. b. The Adjacency Table c. The chain of dyads and d.The resultant set of Metres.




###  6.1 माधवपाहिमां group 


#### 6.1.1	Base Metres of माधवपाहिमां group

| नाम            | अक्षर | मात्रा |                                   |
|----------------|------|-------|-----------------------------------|
| इन्द्रवज्रा       | ११   | १८    | _लक्ष्मीपते माधवपाहिमां हे             |
| वंशस्थ           | १२   | १८    | _दयानिधे माधवपाहिमां हरे             |
| द्रुतविलम्बितम्    | १२   | १६    | _पतितपावन माधवपाहिमां              |
| वसन्ततिलका      | १४   | २१    | _लक्ष्मीपते वरद माधवपाहिमां हे         |
| शार्दूलविक्रीडितम् | १९   | ३०    | _शौरे माधवपाहिमां नरहरे लक्ष्मीपते मध्वरे |
| पुष्पिताग्रा_उ    | १३   | १८    | _रघुवर माधवपाहिमां मुरारे             |
| ललिता_पू        | १०   | १४    | _जय माधवपाहिमां हरे                 |
| ललिता_उ        | ११   | १६    | _जय हे माधवपाहिमां हरे               |



#### 6.1.2 Adjacency Table माधवपाहिमां group [Blank cell=०]

| Next phrase -> | जय | दयानिधे | नरहरे | पतितपावन | मध्वरे | माधवपाहिमां | मुरारे | रघुवर | लक्ष्मीपते | वरद | शौरे | हरे | हे |
|----------------|----|--------|------|----------|------|------------|------|------|---------|-----|-----|----|---|
| phrase         |    |        |      |          |      |            |      |      |         |     |     |    |   |
| जय             |    |        |      |          |      | १          |      |      |         |     |     |    | १ |
| दयानिधे         |    |        |      |          |      | १          |      |      |         |     |     |    |   |
| नरहरे           |    |        |      |          |      |            |      |      | १       |     |     |    |   |
| पतितपावन       |    |        |      |          |      | १          |      |      |         |     |     |    |   |
| मध्वरे           |    |        |      |          | १    |            |      |      |         |     |     |    |   |
| माधवपाहिमां     |    |        | १    |          |      |            | १    |      |         |     |     | १  | १ |
| मुरारे           |    |        |      |          |      |            |      |      |         |     |     |    |   |
| रघुवर           |    |        |      |          |      | १          |      |      |         |     |     |    |   |
| लक्ष्मीपते        |    |        |      |          |      | १          |      |      |         | १   |     |    |   |
| वरद            |    |        |      |          |      | १          |      |      |         |     |     |    |   |
| शौरे            |    |        |      |          |      | १          |      |      |         |     |     |    |   |
| हरे             |    |        |      |          |      |            |      |      |         |     |     |    |   |
| हे              |    |        |      |          |      | १          |      |      |         |     |     |    |   |



#### 6.1.3 Dyad-chain of माधवपाहिमां group


| आद्ययुग्मम्             | मध्ययुग्मम्         | अन्त्ययुग्मम्            |
|---------------------|-----------------|---------------------|
| लक्ष्मीपते माधवपाहिमां  |                 | माधवपाहिमां हे        |
| दयानिधे माधवपाहिमां   |                 | माधवपाहिमां हरे       |
| पतितपावन माधवपाहिमां |                 | पतितपावन माधवपाहिमां |
| लक्ष्मीपते वरद         | वरद माधवपाहिमां  |                     |
| शौरे माधवपाहिमां      | माधवपाहिमां नरहरे |                     |
|                     | नरहरे लक्ष्मीपते    | लक्ष्मीपते मध्वरे        |
| रघुवर माधवपाहिमां     |                 | माधवपाहिमां मुरारे     |
| जय माधवपाहिमां       |                 |                     |
| जय हे                | हे माधवपाहिमां    |                     |


#### 6.1.4 Resultant Metres:

[18 recognized Metres of which 8 are Base Metres. 14 unrecognized Metres.]

१.लक्ष्मीपते माधवपाहिमां हे।  [इन्द्रवज्रा]

२.लक्ष्मीपते माधवपाहिमां हरे। [इन्द्रवंशा]

३.लक्ष्मीपते माधवपाहिमां मुरारे।

४.लक्ष्मीपते माधवपाहिमां नरहरे लक्ष्मीपते मध्वरे।

५.दयानिधे माधवपाहिमां हे। [उपेन्द्रवज्रा]

६.दयानिधे माधवपाहिमां हरे। [वंशस्थम्]

७.दयानिधे माधवपाहिमां मुरारे।

८.दयानिधे माधवपाहिमां नरहरे लक्ष्मीपते मध्वरे।

९.पतितपावन माधवपाहिमाम् [द्रुतविलम्बितम्]।

१०.पतितपावन माधवपाहिमां हे।

११.पतितपावन माधवपाहिमां हरे। [अवरोधवनिता-उ]

१२.पतितपावन माधवपाहिमां मुरारे।

१३.पतितपावन माधवपाहिमां नरहरे लक्ष्मीपते मध्वरे।

१४.लक्ष्मीपते वरद माधवपाहिमां हे। [वसन्ततिलका]

१५.लक्ष्मीपते वरद माधवपाहिमां हरे।

१६.लक्ष्मीपते वरद माधवपाहिमां मुरारे।

१७.लक्ष्मीपते वरद माधवपाहिमां नरहरे लक्ष्मीपते मध्वरे। [>21 syllables]

१८.शौरे माधवपाहिमां हे। [&lt; 10 syllables]

१९.शौरे माधवपाहिमां हरे। [शुद्धविराट्]

२०.शौरे माधवपाहिमां मुरारे। [विश्वविराट्]

२१.शौरे माधवपाहिमां नरहरे लक्ष्मीपते मध्वरे। [शार्दूलविक्रीडितम्]

२२.जय माधवपाहि मां हे।

२३.जय माधवपाहिमां हरे। [ललिता-पू]

२४.जय माधवपाहिमां मुरारे। [पिचुलम्]

२५.जय हे माधवपाहिमां हे। [महिमावसायि]

२६.जय हे माधवपाहिमां हरे। [सीधु][ललिता-उ]

२७.जय हे माधवपाहिमां मुरारे। [बधिरा]

२८.जय हे माधवपाहिमां नरहरे लक्ष्मीपते मध्वरे। [मत्तेभविक्रीडितम्]

२९.रघुवर माधवपाहिमां हे।

३०.रघुवर माधवपाहिमां हरे। [मालती]

३१.रघुवर माधवपाहिमां मुरारे। [मृगेन्द्रमुखम्][पुष्पिताग्रा-उ]

३२.रघुवर माधवपाहिमां नरहरे लक्ष्मीपते मध्वरे।


### 6.2 दयाजलनिधे group


#### 6.2.1 Base Metres of दयाजलनिधे Group

| नाम            | अक्षर | मात्रा | श्लोकपादः                         |
|----------------|------|-------|----------------------------------|
| मञ्जुभाषिणी      |   १३ |    १९ | _मध्वरे दयाजलनिधे नमोनमो            |
| वसन्ततिलका      |   १४ |    २१ | _शौरे दयाजलनिधे सुमते नमस्ते           |
| नर्दटकम्         |   १७ |    २२ | _जय सुमते दयाजलनिधे सुमते सुमते         |
| पृथ्वी           |   १७ |    २४ | _दयाजलनिधे दयाजलनिधे रमायाःपते      |
| शार्दूलविक्रीडितम् |   १९ |    ३० | _शौरे हे सुमते दयाजलनिधे शौरे रमायाःपते |
| स्वागता         |   ११ |    १६ | _हे दयाजलनिधे जय शौरे               |

#### 6.2.2 Adjacency Table of दयाजलनिधे group [Blank cell=०]


|           | जय | दयाजलनिधे | नमस्ते | नमोनमो | मध्वरे | रमायाः पते | शौरे | सुमते | हे |
|-----------|----|----------|------|--------|------|-----------|-----|-----|---|
|           |    |          |      |        |      |           |     |     |   |
| जय        |    | १        |      |        |      |           | १   | १   |   |
| दयाजलनिधे  | १  | १        |      | १      |      | १         | १   | १   |   |
| नमस्ते      |    |          |      |        |      |           |     |     |   |
| नमोनमो    |    |          |      |        |      |           |     |     |   |
| मध्वरे      |    | १        |      |        |      |           |     |     |   |
| रमायाः पते |    |          |      |        |      |           |     |     |   |
| शौरे       |    | १        |      |        |      | १         |     |     | १ |
| सुमते       |    | १        | १    |        |      |           |     | १   |   |
| हे         |    | १        |      |        |      |           |     | १   |   |

#### 6.2.3 Dyad-chain of दयाजलनिधे group

| आद्ययुग्मम्           | मध्ययुग्मम्      | अन्त्ययुग्मम्          |
|-------------------|--------------|-------------------|
| मध्वरे दयाजलनिधे     |              | दयाजलनिधे नमोनमो   |
| शौरे दयाजलनिधे      | दयाजलनिधे सुमते | सुमते नमस्ते          |
| जय सुमते            | सुमते दयाजलनिधे | सुमते सुमते           |
| दयाजलनिधे दयाजलनिधे |              | दयाजलनिधे रमायाःपते |
| शौरे हे             | हे सुमते        |                   |
|                   | दयाजलनिधे शौरे | शौरे रमायाःपते      |
|  हे दयाजलनिधे       | दयाजलनिधे जय  | जय शौरे            |

#### 6.2.4 Resultant Metres
 [8 recognized Metres of which 6 are Base Metres. Unrecognized Metres are 13.]

१.मध्वरे दयाजलनिधे नमो नमो। [मञ्जुभाषिणी]

२. मध्वरे दयाजलनिधे रमायाः पते ।

३. मध्वरे दयाजलनिधे सुमते नमस्ते ।

४. मध्वरे दयाजलनिधे सुमते सुमते ।

५. मध्वरे दयाजलनिधे सुमते दयाजलनिधे नमो नमो ।

६. मध्वरे दयाजलनिधे सुमते दयाजलनिधे रमायाः पते ।

७. शौरे दयाजलनिधे नमो नमो। [ललिता]

८. शौरे दयाजलनिधे रमायाः पते । [मर्मस्फुरम्]

९. शौरे दयाजलनिधे सुमते नमस्ते । [वसन्ततिलका]

१०. शौरे दयाजलनिधे सुमते सुमते ।

११. शौरे दयाजलनिधे सुमते दयाजलनिधे नमो नमो ।

१२. दयाजलनिधे दयाजलनिधे नमो नमो।

१३. दयाजलनिधे दयाजलनिधे रमायाः पते । [पृथ्वी]

१४ दयाजलनिधे दयाजलनिधे सुमते नमस्ते ।

१५ दयाजलनिधे दयाजलनिधे सुमते सुमते ।

१६. दयाजलनिधे दयाजलनिधे सुमते दयाजलनिधे नमो नमो ।

१७. शौरे हे सुमते सुमते ।

१८. शौरे हे सुमते नमस्ते ।

१९. शौरे हे सुमते दयाजलनिधे नमो नमो ।

२०. शौरे हे सुमते दयाजलनिधे रमायाः पते ।

२१.शौरे हे सुमते दयाजलनिधे शौरे रमायाः पते । [शार्दूलविक्रीडितम्]

२२.हे दयाजलनिधे नमो नमो । [रथोद्धता]

२३.हे दयाजलनिधे रमायाः पते ।

२४.हे दयाजलनिधे सुमते नमस्ते ।

२५.हे दयाजलनिधे सुमते सुमते ।

२६.हे दयाजलनिधे शौरे रमायाः पते ।

२७.हे दयाजलनिधे जय शौरे । [स्वागता]


### 6.3 केशवपाहिहरे group


#### 6.3.1 Base Metres of केशवपाहिहरे group

| नाम         | अक्षर | मात्रा |                         |
|-------------|------|-------|-------------------------|
| दोधकम्       | ११   | १६    | केशवपाहिहरे नरकारे         |
| तामरसम्      | १२   | १६    | रघुवर केशवपाहिहरे हे        |
| तोटकम्       | १२   | १६    | जय केशवपाहिहरे सुमते        |
| नर्दटकम्      | १७   | २२    | रघुवर मध्वरे वरद केशवपाहिहरे |
| द्रुतविलम्बितम् | १२   | १६    | वरद केशवपाहिहरे हरे        |

#### 6.3.2 Adjacency Table केशवपाहिहरे group [Blank cell=०]



| Next phrase -> | केशवपाहिहरे | जय | नरकारे | मध्वरे | रघुवर | वरद | सुमते | हरे | हे |
|----------------|-----------|----|-------|------|------|-----|-----|----|---|
| phrase         |           |    |       |      |      |     |     |    |   |
| केशवपाहिहरे      |           |    | १     |      |      | १   | १   | १  | १ |
| जय             | १         |    |       |      |      | १   |     |    |   |
| नरकारे          |           |    |       |      |      |     |     |    |   |
| मध्वरे           |           |    |       |      |      | १   |     |    |   |
| रघुवर           | १         |    |       | १    | १    |     |     |    |   |
| वरद            | १         |    | १     |      |      |     |     | १  |   |
| सुमते            |           |    |       |      |      |     |     |    |   |
| हरे             |           |    |       |      |      |     |     |    |   |
| हे              |           |    |       |      |      | १   |     |    |   |



#### 6.3.3 Dyad-chain of केशवपाहिहरे group

| आद्ययुग्मम्         | मध्ययुग्मम्  | अन्त्ययुग्मम्        |
|-----------------|----------|-----------------|
| केशवपाहिहरे नरकारे |          | केशवपाहिहरे नरकारे |
| रघुवर केशवपाहिहरे  |          | केशवपाहिहरे हे     |
| जय केशवपाहिहरे    |          | केशवपाहिहरे सुमते   |
| रघुवर मध्वरे       | मध्वरे वरद | वरद केशवपाहिहरे   |
| वरद केशवपाहिहरे   |          | केशवपाहिहरे हरे    |

#### 6.3.4 Resultant Metres
 [8 recognized Metres of which 5 are Base Metres. Unrecognized Metres are 9.]

१.केशवपाहिहरे नरकारे  ।  [दोधकम्]

२.रघुवर केशवपाहिहरे नरकारे  ।

३.रघुवर केशवपाहिहरे हे  ।  [तामरसम्]

४.रघुवर केशवपाहिहरे सुमते  ।

५.रघुवर केशवपाहिहरे हरे  ।

६.जय केशवपाहिहरे नरकारे  । [तारकम्]

७.जय केशवपाहिहरे हे  ।  [उदितम्]

८.जय केशवपाहिहरे सुमते  ।  [तोटकम्]

९.जय केशवपाहिहरे हरे  ।  [उपचित्रम्]

१०.रघुवर मध्वरे वरद केशवपाहिहरे  ।  [नर्दटकम्]

११.रघुवर मध्वरे वरद केशवपाहिहरे नरकारे  ।

१२.रघुवर मध्वरे वरद केशवपाहिहरे हे  ।

१३.रघुवर मध्वरे वरद केशवपाहिहरे सुमते  ।

१४.रघुवर मध्वरे वरद केशवपाहिहरे हरे  ।

१५. वरद  केशवपाहिहरे  हरे  । [द्रुतविलम्बितम्]

१६.  वरद  केशवपाहिहरे  नरकारे  ।

१७.  वरद  केशवपाहिहरे  सुमते  ।


### 6.4 Review of results

We have constructed Adjacency Tables for 4 groups of Metres clustered around spines मध्वरेपाहिशौरे, माधवपाहिमां, दयाजलनिधे and केशवपाहिहरे. The procedure established shows how by constructing Adjacency Tables for small groups of Metres bound by a common spine element we can generate systematically not only the Base Metres but also additional recognized Metres and a large number of unrecognized Metres which we assert are no less rhythmic than any recognized Metre. If a procedure leads to obtaining the examined Metres and additional Metres which are both recognized to be rhythmic, by induction all Metres derived through the procedure could be taken to be rhythmic. It would certainly be possible to build more groups to cover more Metres. It needs to be noted that a Metre could find a place in more than one group.[वसन्ततिलका, शार्दूलविक्रीडितम् and नर्दटकम् occur in more than one group.] For a given set of Metres in a group the set of rhythm-elements is not unique. Future research efforts could lead to getting rid of this subjective element in choosing the set.

## 7.0 Conclusion


This paper is the result of an idler’s wanderings in the rhythm landscape of vṛtta śloka-s. Whether it has made a trail worth pursuing is for others to say. The joy, partly aesthetic and partly intellectual, that the wanderer has experienced in his wanderings has been immense.

It has attempted to provide an artificial frame work imposing an order in the natural phenomenon of ‘rhythm’ observed in vṛtta śloka-s of Sanskrit. It is not unlike the grammar of a natural language which perceives rules where none exists. Starting from clustering different Metres around a comparatively long common sequence of guru-s and laghu-s the paper proceeds to work out a small set of ‘rhythm-elements’ the stringing of which in different orders yields different Metres. Based on the premise that preserving adjacency of ‘rhythm’ elements as seen in a set of ‘Base Metres’ adequately preserves the quality of being rhythmic, an adjacency table is created using which, one can string not only the Base Metres, which is pretty trivial, but also known Metres beyond the Base Metres and several new Metres yet to be named.

Presently Chandas does not appear to be an important area of research in Sanskrit studies. Being a virgin area it has afforded the author a sense of conquering and the pleasure of experiencing charming unexpected responses. There is plenty of work to be done in this fertile area which will not fail to yield fruitful results. For example, how well a spine of Base Metres discussed above seamlessly merges with  the flow of rhythm in any one of the Base Metres may have much to do with the rhythmic quality of  the resultant Metres and this aspect needs further study. Again, the nature of ‘rhythm’ continues to be elusive. One should be able to objectively define and specify ‘rhythm’ without having to go by subjective understanding only. The novel practice of representing laghu by ‘1’ and guru by ‘2’ as well as the practice of representing a binary string, say 2112112 by केशवपाहिहरे a prosodically equivalent Sanskrit phrase, merit getting standardised in Chandas pedagogy.

## 8.0 References


### Books



1. _Kedārabhaṭṭa_: Vṛttaratnākara nirṇayasāgar Press Mumbai
2. _Hemacandra. _Chandonuśāsanam: Edited by H D Velankar; Singhījainaśāstraśikṣāpīṭh Bhāratīyavidyābhavan, Mumbai 1961


### Articles

3. Murthy G S S : Characterizing Classical Anushtup: Annals of the Bhandarkar Oriental Research Institute: Vol. LXXXIV (2004): pages 101-115

4. Murthy G S S : .A computer program to identify Sanskrit Metres– Praciprajnaa. Vol.-1/2016 [7.A computer program to identify Sanskrit Metres.docx - Google Drive](https://drive.google.com/file/d/0B-ToPRKbb6tuTUJ5Mm9nalZlZWc/view?resourcekey=0-ts5NTt4j5vImaE8-Brltcg)

5. Murthy G S S :** Computer-aided classification of akṣaragaṇavṛtta-s on the bases of mātrāgaṇa-s: A new perspective: **Annals of the Bhandarkar Oriental Research Institute: vol. XCVII 2016 pages 97-138**  **

### Web sites

6. Sanskrit Metres- Metre Identifier: [http://sanskritmetres.appspot.com/](http://sanskritmetres.appspot.com/)

7. Adjacency Matrix: [https://www.sciencedirect.com/topics/computer-science/adjacency-matrix](https://www.sciencedirect.com/topics/computer-science/adjacency-matrix)






## 9.0 Figures:



(?? Missing Adjacency Diagram मध्वरेपाहिशौरे group)
![alt_text](images/image1.png "image_tooltip")



## Notes

[^1]: Murthy G S S : .A computer program to identify Sanskrit Metres– Praciprajnaa. Vol.-1/2016 [7.A computer program to identify Sanskrit Metres.docx - Google Drive](https://drive.google.com/file/d/0B-ToPRKbb6tuTUJ5Mm9nalZlZWc/view?resourcekey=0-ts5NTt4j5vImaE8-Brltcg)

[^2]: Murthy G S S : Characterizing Classical Anushtup: Annals of the Bhandarkar Oriental Research Institute: Vol. LXXXIV (2004): pages 101-115

[^3]: Murthy G S S :** **Computer-aided classification of akṣaragaṇavṛtta-s on the bases of mātrāgaṇa-s: A new perspective**: **Annals of the Bhandarkar Oriental Research Institute: vol. XCVII 2016 pages 97-138

[^4]: The spine rhythm-element is shown as a single word without providing space between its constituent words.

[^5]: [a] Metre शालिनी is denoted by letter ‘a’ in subsequent discussion. Similarly b,c.d and e denote मालिनी,भुजङ्गप्रयातम्,मन्दाक्रान्ता and स्रग्धरा.

[^6]: ‘ade’ denotes that rhythm element कंसारे occurs in Metres a,d and e. Similarly ‘abcde’ after मध्वरेपाहिशौरे denotes phrase occurs in Metres a,b,c,d and e. .

[^7]: ‘ade’ in the cell denotes that the specific adjacency कंसारे हे occurs in Metres a,d and e. Similarly ‘be’ occurring after 1 in the cell common to मधुमथन row and हरे column denotes that मधुमथन हरे occurs in Metres b and e. 

[^8]: Adjacency Matrix: [https://www.sciencedirect.com/topics/computer-science/adjacency-matrix](https://www.sciencedirect.com/topics/computer-science/adjacency-matrix)

[^9]: क१ denotes the dyad कंसारे हे. Similarly ग१ denotes हे हरे etc.

[^10]:
This is similar to assuming 1/(1-x) to be equal to 1+x where x is much less than 1.

[^11]: Names of less popular Metres have been obtained from [http://sanskritmetres.appspot.com/](http://sanskritmetres.appspot.com/)


