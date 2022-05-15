+++
title = "Computer aided classification"
+++


Computer-aided Classification of akṣaragaṇavṛttas on the bases of mātrāgaṇas: A new perspective [^1]:

G S S Murthy[^2]

## 1.0 Introduction 

For investigating the rhythms characteristic of akṣara-gaṇa-vṛttas, the author developed a computer program that brings out the beat-structure of a given Metre. This paper shows how based on this beat-structure, it is possible to define akṣara-gaṇa-vṛttas in terms of mātrā-gaṇas leading to a re-classification of akṣara-gaṇa- vṛttas. This re-classification enables generating new Metres and recognizing the closeness of Metres, which may differ in number of akṣaras[^3] (syllables) in a pāda (quarter of a verse).

For the benefit of those who may not be familiar with the subject of Sanskrit Prosody, it would be appropriate to provide a brief introduction to the subject.

## 2.0 Elements of Sanskrit prosody

Elaborate and detailed study of Metres is the subject matter of chandaḥ śāstra. While there are many books dealing with the subject, the three most important treatises on the subject are the chandaḥ śāstra of Piṅgala, vṛttaratnākara of Kedārabhaṭṭa and chando'nuśāsana of Hemacandra. A hrasva-svara (short vowel) has a duration of one unit of time, called mātrā, whereas a dīrgha-svara (long vowel) has a duration of two units. A consonant by itself is taken to be of zero duration. For purposes of prosody, an akṣara of one mātrā  is laghu  (literally meaning “light”) and an akṣara of two _mātrā_s is _guru _(literally meaning ”heavy”). A svara (vowel) followed by a saṃyuktākṣara (conjunct consonant), _anusvāra_, or _visarga _ is treated as _guru_  and of two _mātrā_s even though it may be _laghu_  when it stands alone. The last akṣara of a pāda of a verse is treated as a guru even though it may be a laghu. Traditionally a laghu is represented by a “dash” and a guru is represented by a “cap”. There is no reason to continue with the old symbols in this digital age and in this paper, a laghu is “1” and a guru is “2”.

Verses in Sanskrit which consist of four pādas can be broadly classified into three categories.



1.
Metres where a pāda is characterized by a specific and rigid string of laghus and gurus, being called a “characteristic string” in this paper, come under the category of akṣara-gaṇa-vṛttas. Mostly, the four pādas of a verse are composed to follow one characteristic string. In order to easily remember the specific string, the string is broken down into units of 3 akṣaras, starting from the first akṣara of a pāda, sometimes leaving at the end a stub of one or two akṣaras. A string of 3-akṣaras, called “varṇa-gaṇa”, can be any of the eight combinations: 111,112,122, 222, 221, 212,121 and 211, which are denoted by the letters: na, sa, ya, ma, ta, ra, ja and bha respectively. There is a nice mnemonic “ya-mā-tā-rā-ja-bhā-na-sa” which when written as a binary string is 12221211. Ya-mā-tā is “ya-gaṇa” (gaṇa means a group); mā-tā-rā is “ma-gaṇa”; “tā-rā-ja” is “ta-gaṇa”- - - “na-sa-ya” is “na gaṇa” and ”sa-ya-mā” is “sa-gaṇa”. Any arbitrary sequence of akṣaras can be broken down to a sequence of these 8 gaṇas. A verse composed in a Metre, specified by a name and defined by a characteristic string, is generally called a vṛtta or vṛttaŚloka. In this paper we shall use “vṛtta” to mean a generic metrical verse in Sanskrit and “Metre” to mean a specific metrically defined characteristic string having a specific name. The main point to note is that any random string for a given length does not become a Metre. Only certain specific strings for a given number of akṣaras in the string yield a Metre.
One can take the example of a Metre called “rathoddhatā” which has 11 akṣaras in a pāda. It is defined as follows, “rānnarāviha rathoddhatā lagau”[^4]. It means, “ra, na and ra gaṇas and a laghu and a guru constitute “rathoddhatā”. Based on the mnemonic given above one can write out the characteristic string as follows: 212-111-212-12. As the verse has 11 akṣaras, a 2-akṣara stub remains at the end after 3 3-akṣara gaṇas.  There is an internal rhythm inherent in the Metre which can be discerned by a trained listener.

For some Metres, the instants where a word has to end within a pāda is specified and this pause is called “yati”. A word cannot bridge an instant of yati. Yati is specified in terms of akṣaras. For example, Śālinī Metre, is specified with a yati at the end of 4 akṣaras. The end of a pāda provides another natural yati.

ii)  Metres which employ what are called “mātrā-gaṇa”s. For example a 4-mātrā gaṇa is a sequence of akṣaras, which has a total of 4 mātrās. The following syllabic sequences are all of 4 mātrā duration: 22, 1111, 121, 112, 211. We remark in passing that the number of possible sequences for an n-mātrā gaṇa is F(n+1) where F(n) is the nth term of the Fibonacci sequence [1,1,2,3,5…etc]. Indian prosodists made use of the Fibonacci sequence and its recurrence formula, F(n) = F(n-1)+F(n-2), much before Fibonacci publicized it. We will not go into this aspect any further.

If a pāda of a verse is defined as, let us say, a sequence of four 4-mātrā gaṇas and a “guru”, the definition is much less rigid than that based on “varṇa-gaṇa” and a line of the verse could have a minimum of 9 akṣaras to a maximum of 17 akṣaras, so long as it follows the definition.

Generally mātrāgaṇas employed are limited to mātrās of 2,3,4,5 and 6 only. They are represented by letters da, ta, ca, pa  and ṣa [^5](Initial letters of words dvi, tri, catur, pañca and ṣaṭ), respectively. The number of all possible sequences for these gaṇas are:      da-gaṇa: 2; ta-gaṇa: 3; ca-gaṇa: 3+2=5; pa-gaṇa: 5+3=8; ṣa-gaṇa: 8+5=13. The actual sequences for da, ta and ca- gaṇas are (11 and 2), (111, 12, 21), (1111, 112,121, 211, 22) respectively. Mātrā-gaṇa based Metres are seen to be employed more in prākṛta texts and their use in classical Sanskrit is so far limited to 4-mātrā gaṇa’s.

iii)  Metres where a specified number of akṣaras constitutes a pāda of a verse. The well-known and ubiquitous Metre anuśṭup, which has 8 akṣaras in a pāda, belongs to this category. Characteristics of anuṣṭup are dealt with in an earlier paper[^6] by the author.

## 3.0  Rhythm and beat structure in a Metre

Intrinsic rhythm of a Metre is something not easily definable. All that we can say is that this rhythm enables a poet to compose a verse without checking manually if the verse composed is as per its lakṣaṇa (definition). Again, it enables a trained listener or reader to quickly recognize if the verse fails to meet the lakṣaṇa. The particular sequence of laghus and gurus of a Metre creates the rhythm intrinsic to the Metre. It needs to be mentioned that the Metres defined in works on Sanskrit Prosody are not equally rhythmic. That is why we find that poets choose to compose verses limited to a repertoire of say 30 or 40 Metres, which are more rhythmic than the rest.

Intuitively one can say that if, successive akṣaras in a pāda of a verse could be grouped into small segments, each group having the same duration and ending in a vowel, one could perceive a beat of constant duration leading to a sense of rhythm. That means that if a pāda could be broken down into segments of equal mātrās (mātrā-gaṇas) a rhythmic beat could be perceived. An example is the famous hymn of śrī śaṅkarācārya,  bhajagovindam, which is composed in a Metre based on mātrā-gaṇas. It has a beat which any one can discern.

भज गोविन्दं भज गोविन्दं गोविन्दं भज मूढमते ।

संप्राप्ते सन्निहिते काले नहि नहि रक्षति डुकृञ् करणे ॥

bhaja govindaṃ bhaja govindaṃ govindaṃ bhaja mūḍhamate ।

saṃprāpte sannihite kāle nahi nahi rakṣati ḍukṛñ karaṇe ॥

A little examination will show that it can be broken into syllabic segments of duration 4 mātrās as follows:

112-22-112-22-22-211-211-2 ।

22-22-112-22-1111-211-121-12 ||

It is also observed that a stub of 2 or 3 mātrās at the end will not affect the overall rhythm of the line and often improves the quality of the rhythm.

In a similar manner could verses based on varṇa-gaṇas be broken down into mātrā-gaṇas, so that such a structure based on mātrā-gaṇas provides a beat for the verse? For any beat to be perceived, it should be possible to break the pāda into at least two segments of equal duration with or without a stub remaining. In order to study this aspect let us again look at the rathoddhatā Metre which has a total of 16 mātrās and whose characteristic string is 212-111-212-12. It can be broken into two 7- mātrā segments with a stub of ‘2’ at the end as 21211-12121-2. The interval of time between the start of a segment and the start of the next segment, which can be called the period, is 7 mātrās in this case. The beat of 7 mātrās could be further re-inforced if each 7-mātrā sequence reveals the same internal pattern. Within 7-mātrā segment, no common structure emerges. In this study we shall say that a tāla of 7-mātrās exists in rathoddhatā Metre

It can also be broken into two 8-maatra segments as 212111 and 21212.  It can be observed that within each 8-mātrā segment a pattern of 2-1-2-1-2 indeed exists as 2-1-2-1-1-1 is equivalent to 2-1-2-1-2 as far as timing is concerned. We shall say that rathoddhatā exhibits, in addition to the 7- mātrā  tāla, a tāla of 8-mātrās with a laya 2-1-2-1-2. The tāla has sub-periods 2, 1, 2, 1 & 2 within a period of 8 mātrās. Words, tāla and laya (internal beat) may be treated as technical terms specific to this study, although they may denote something else in music or any other field.

It is important to recognize that the beat of 8 mātrās and the internal pattern 2-1-2-1-2  found in rathoddhatā  provides a frame of timings and that this beat with the internal pattern of timings will be preserved even if any of 2’s is replaced by “11”. Therefore we can replace pattern 2-1-2-1-2 by “da1da1da” where “da” is a 2-mātrāgaṇa.  Thus, “da1da1da-da1da1da” defines a set of Metres, characterized by a tāla of 8-mātrā period with a laya 2-1-2-1-2 and rathoddhatā is just a member of this set. As the last akṣara in a pāda has to be a guru, the last “da” in the string can only be 2, a guru. It is obvious that the option of replacing all “da”s by ‘11’ will end up in a rhythm-less string of ‘1’s and therefore has to be assumed as invalid.

We have 2^5=32 different strings all of which meet the requirement “da1da1da-da1da12”. Five of the strings are shown in Table 1:

Table-1:  5 of 32 strings meeting “da1da1da-da1da12”

| da | 1 | da | 1 | da | da | 1 | da | 1 | 2 |
|----|---|----|---|----|----|---|----|---|---|
| 2  | 1 | 2  | 1 | 11 | 2  | 1 | 2  | 1 | 2 |
| 2  | 1 | 2  | 1 | 11 | 2  | 1 | 11 | 1 | 2 |
| 11 | 1 | 2  | 1 | 11 | 2  | 1 | 2  | 1 | 2 |
| 11 | 1 | 2  | 1 | 2  | 11 | 1 | 2  | 1 | 2 |
| 2  | 1 | 2  | 1 | 11 | 2  | 1 | 11 | 1 | 2 |

The first row can be seen to be rathoddhatā. Rows 2 to 5 have rhythms akin to that of rathoddhatā, but with subtle differences. We could treat them as different flavours of rathoddhatā. In fact, rows 2 and 3 turn out to be two defined Metres, namely chandravartma and priyaṃvadā

[A Metre could be recited by replacing 1 by, say “na” and 2 by, say “te”. rathoddhatā could be recited as “tenatenanana tenate nate” although it is a meaningless sequence of akṣaras.] Rows 4 and 5 are apparently two new Metres and can be defined on the akṣaragaṇa system. As an alternative, If we define a mātrā-gaṇa-vṛtta by “da1da1da-da1da12”, all the variants would become permissible pādas.   Thus, by studying the tālas and associated layas of akṣara-gaṇa-vṛttas, it would be possible to define a set of akṣara-gaṇa Metres in terms of mātrā-gaṇas. This set could contain Metres already defined and others yet to be defined as per akṣaragaṇa system. All members of the set would have the same number of mātrās although the number of akṣaras may differ. Each one would meet the requirement of the specified tāla with its laya, characterizing the set. Each member would of course have its own intrinsic rhythm, which may not be fully captured by the over-arching tāla with associated laya. To study the tālas and layas of a large number of Metres, it was considered worthwhile to develop a computer program. And, we briefly explain in the next section a computer program, which outputs all the tālas and layas when a pāda of the verse is input as per a specified transliteration scheme. We shall not however go into the technical aspects of the program such as procedures and algorithms built into the program.

## 4.0 The computer program

When a pāda of a verse is input as per a specified transliteration scheme, the program[^7] output answers the following questions

What is the characteristic string of the Metre? How many akṣaras are there? What is its length in terms of mātrās? Does the string exhibit any tālas? If yes, how many tālas are there? For each tāla, what is its period in mātrās? Does the tāla exhibit a laya? if, yes, what is the laya?

The program takes care of the following aspects:

A hrasva-svara is treated as 1. A dīrgha-svara is treated as 2. A svara followed by a saṃyuktākṣara, visarga or anusvāra is treated as 2. The last akṣara of the input pāda is treated as 2.

While checking for tālas, a pāda which exhibits a tāla of n-mātrās could also exhibit tālas of  2n, 3n—etc. The program only gives the lowest of such multiples. For example, if a pāda input shows a tāla of 2 mātrās, it could also exhibit tālas of 4 mātrās and 6 mātrās, but the program gives the tāla of 2 mātrās only. Further, if the program has discovered a laya in a tāla for a specified input, it does not search for another possible laya for the tāla.

When the program is checking for a tāla of period, say, 9-mātrās in a, say, 26-mātrā- long Metre, if such a tāla is detected, there will be an unstructured stub of 8 mātrās. (26=2x9+8)

When the computer program is launched [ Fig. 1]

The program outputs, “**_Please enter a pāda of a vṛtta_**”.

You enter the pāda in Roman script as per a specified transliteration scheme, say, “syaadidravajraa jatajaastato gau”.

The program outputs as follows:

**_No. of akṣara’s=11_**

**_No. of Mātrā’s=18_**

**_ScanOut=22122112122_**

**_No. of basic taals=2_**

**_taalBasic_**[^8]**_[0]=7_**

**_taalBasic[1]=9_**

**_laya in basic taal of 7 mātrās is 2-2-3_**

**_laya in basic taal of 9 mātrās is 2-2-1-2-2_**

**_I know the vṛtta_**

**_Its name is indravajrA_**

In the above interaction shown, scanOut gives the characteristic string of indravajrā. As the program has the characteristic string of indravajrā in its database, it outputs its name.

If however the database does not have the characteristic string, the program will output all the details of the input pāda and then say as follows (Fig. 2):

**_I do not know this vṛtta_**

**_Would you like me to learn it?_**

**_If yes, enter the name of the vṛtta, else enter NO._**

If you enter NO, the program does nothing.

If you enter the name of the vṛtta, it will say:

**_Please enter YES to confirm that you _**

**_have spelt the name correctly, else enter the name again correctly _**

If you input YES, it will say:

**_I have learnt the new vṛtta_**

The data output by the program for most of akṣaragaṇa vṛttas specified in vṛttaratnākara and chando'nuśāsana was consolidated on a spread sheet and the result is given in Table 2, after appropriate sorting.

Fig. 1 (Command prompt figure missing)

Fig 2  (Command prompt figure missing)



<div class="spreadsheet" src="../chandas-classification_tbl-2.tsv" fullHeightWithRowsPerScreen=8> </div>  





## 5.0 Description of Table 2

Table 2, where each row contains data corresponding to a particular Metre, has the following columns:

A: A serial number

B: Name of the Metre. The number given after the name refers to the serial number in “ chando'nuśāsanam”. For some of the Metres, chapter number and serial number in “vṛttaratnākara” are given as VR ____.

C: Scan of the Metre. The “under-score” at the beginning of a scan serves a technical purpose and has no significance. A comma in the scan indicates yati.

D: No of akṣaras in the input pāda.

E: No of mātrās in the input pāda.

F: tālas / layas. In this column, to conserve space, certain conventions are followed. Period of tāla is mentioned if there is no laya associated. If there is a laya, only laya is specified, total sum of laya segments being the period of tāla. Further, laya is specified as a string of numerals. Semicolons separate tālas. For example, pṛthvī Metre (Sl.No.240) has in the tāla / laya column 12212; [11]; 13143. It means that the scan exhibits 3 tālas; tāla1 has a laya 1-2-2-1-2, the period of tāla being 1+2+2+1+2= 8 mātrās; tāla 2 has a period of eleven mātrās with no laya (a 2-digit number is always enclosed by square brackets [ ] to distinguish it from a sequence of single digit numbers.); tāla 3 has a period of 1+3+1+4+3=12 mātrās with laya 1-3-1-4-3. As pṛthvī has 24 mātrās (column E), tāla1, 2 & 3 leave a stub of 0, 2 & 0 mātrās respectively.

G: This column gives a proposed definition of the Metre based on mātrā-gaṇa system. In this column 2,3,4,5 & 6-mātrā gaṇas are written as da, ta, ca, pa & ṣa respectively as per the standard convention. If the Metre exhibits only one tāla we could define a mātrā-gaṇa-based definition without any ambiguity. If, however, it exhibits several tālas we have as many options and in this exploration one of the tālas is chosen based on the following criteria: i) a tāla having a laya is preferred to a tāla without any laya. ii) a tāla which does not leave a stub is preferred to one which leaves a stub. iii) between two tālas,  tāla having a lower period is preferred. For example, in case of pṛthvī Metre we have 3 tālas specified by 12212; [11];13143. Out of the three we opt for 12212 as it does not leave a stub and its period being 8 mātrās is less than that of the other two (11 and 12  mātrās). Therefore, in column G, we choose to define pṛthvī in terms of mātrā gaṇas as 3(1dada1da), where 3 denotes the number of times the phrase in the bracket   “1dada1da” repeats in a pāda. As yati is an instant of pause, wherever yati is specified, it is necessary to ensure that the end of a mātrā-gaṇa coincides with the instant of yati. Based on these reasonable criteria, a mātrā-gaṇa-based definition is given in Column G for every Metre.

Making use of the “sort” facility in Spread-sheet, rows have been arranged in the ascending order of “number of mātrās” and for a given “number of mātrās” column G has been rearranged alphabetically. As a result, Metres having same number of mātrās are grouped sequentially and within the group, Metres having the same definition appear sequentially.

## 6.0 A discussion of Table 2.

Table 2 has the distinguishing features that  i) it analyses a large set (339) of Metres giving the name, scan, number of akṣaras and number of mātrās besides tāla / laya and ii)  Metres having the same length in terms of mātrās, though not in terms of akṣaras, get grouped and appear sequentially, which enables comparing their mātrā-gaṇa structure.

It is to be noted that excepting a few, all Metres display at least one tāla with or without laya and the maximum number of tālas that a Metre displays is five. Longer a Metre in terms of mātrās more the likelihood of multiple tālas and tālas of longer period. Tālas of longer period could also lead to longer stubs and such tālas may not be of use in defining the Metre in terms of mātrāgaṇas.

All tālas which a Metre displays, together convey information on the structure of the Metre. If two Metres of equal length in mātrās display the same set of tālas with their layas, they would be rhythmically very near to each other. Given a set of tālas with their layas displayed by a Metre, we can synthesize a string which satisfies the set. The method of synthesis is shown in appendix-1 and we discuss the results of synthesis here.

Synthesised string for pṛthvī turns out to be (see appendix 1): 1da111da1da111da1dada12.

We can see that this is indeed the characteristic string of pṛthvī!  Out of the three talas displayed by pṛthvī, tāla 2 is redundant. We could say that the intrinsic rhythm of pṛthvī is fully defined by tāla 1 and tāla 3 or simultaneous playing of these 2 tālas results in a rhythm characteristic of pṛthvī.

However, not all Metres can be thus fully defined in terms of their tālas and layas. For example, in case of praharṣiṇī, the synthesised string is dadadada11dacada2 which accommodates 5*(2^6)=160 variants.   In Table 2 however, mātrā-gaṇa definition for praharṣiṇī is shown as 2(dacadada), based on only one of the tālas, 2422.  praharṣiṇī or any Metre for that matter, could also be defined in terms of 1’s and da-gaṇas simply by replacing ‘2’ (guru) in the characteristic string by da-gaṇa. For praharṣiṇī it would be

dadada1111da1da1da2. There are 2^6 = 32 variants meeting this definition.

So, we have for praharṣiṇī three ways of providing a definition in terms of mātrāgaṇas.

Method 1: We repalce 2’s (guru’s) in the characteristic string by ‘da’s.

‘2221111212122’ -> ‘dadada1111da1da1da2’.  This provides a sharp or targeted definition, all variants (2^6=32) of which are likely to have rhythms hovering around the rhythm of praharṣiṇī. But its coverage of other known Metres is limited.

Method 2: We base the definition on the synthesized string. The synthesized string is 2-2-2-2-1-1-2-4-2-2-> dadadada11dacadada. Although it has 5*(2^6) =160 variants, unless the set of tālas with layas is applicable to another Metre also, its coverage would not be significantly larger than that of method 1.

Method 3: We base our definition on one of the tālas, which is selected pragmatically on a set of criteria. This is the method followed in the definition given in Column G of Table 2 and the criteria for selecting a tāla is explained in Section 4 above. For praharṣiṇī it is 2(dacadada)->dacadada-dacada2, which has (2^5)*(5^2)= 32*25=800 variants!.

It is to be pointed out that, in general, a mātrā-gaṇa based Metre need not have any tāla at all as defined in this paper. For example a mātrā-gaṇa-based Metre could be defined as (pacata)2 where no tāla is apparent. The purpose of making the mātrā-gaṇa-based definition dependant on a tāla associated with the corresponding akṣaragaṇa-based Metre, is to avoid the rhythm of the former straying away from the rhythm of the latter.

One can observe from Table 2 that the same mātrā-gaṇa-based definition is applicable to a group of Metres. We record some of these definitions and the corresponding serial numbers (Table 2) of Metres in Table 3.

Table 3

| Mātrā-gaṇa definition | Serial Number (Table 2)       |     |
|-----------------------|-------------------------------|-----|
|                       | From                          | To  |
| 6(da)                 | 32                            | 41  |
| 7(da)                 | 60                            | 74  |
| 8(da)                 | 101                           | 125 |
| 10(da)                | 179                           | 181 |
| 15(da)                | 293                           | 302 |
| 16(da)                | 319                           | 327 |
| 3(ta)2                | 6                             | 10  |
| 2(da1da1da)           | 84                            | 87  |
| 3(pa)2                | 128                           | 132 |
| 3(dadapa)             | 264                           | 267 |

The method of treating an akṣaragaṇa-based Metre as a broader mātrāgaṇa-based Metre appears to be prevalent in Prakṛt poetry where pa-gaṇa is employed in place of ya-gaṇa in bhujangaprayātam Metre[^9].

In our quest for commonality between Metres, we could go even one step further. For example, for bhujaṅgaprayātam (serial.no.189), column G entry is 4(1dada) as per the chosen laya (column F) 122; sragviṇī (sl no.193) has a laya of 212. Both can be clubbed into a laya 32, although in the process laya is rendered coarser. Similarly  prabhadrakam (sl.no.182) laya 11233, kalabhāṣiṇī (sl.no.183) laya 121312, ṛṣabhagajavilasitam (sl.no.184) laya 211213 and  dardurakaḥ (sl.no.187) 31312 can all be clubbed into a common laya 433. The common definition in terms of mātrā-gaṇas for these Metres becomes 4(catata). Again, as da1da, 1dada, tada, da_ta are all subsets of pa-gaṇa we could replace them by the bigger set pa-gaṇa. This method of clubbing has its obvious limitations and if used indiscriminately, variations in rhythm may spread beyond recognition.

It has to be admitted that there are some Metres which do not display any tāla and for them this method of providing a mātrā-gaṇa definition fails. Ex: vātormI (sl.no. 178). There are also some other Metres which have large tāla periods without any meaningful laya and attempting to provide a definition to them through this method is not purposeful. It is a matter of dismay that popular Metres such as śārdūlavikrīḍitam (sl.no.230), and sragdharā (sl.no.333) belong to this category.

<div class="spreadsheet" src="../chandas-classification_tbl-4.tsv" fullHeightWithRowsPerScreen=8> </div>  


As an adjunct to Table 2, Table 4 provides an alphabetical index to names of Metres where, against the name of a Metre, the serial number of the Metre in Table 2 is given facilitating the search of any particular Metre in Table 2.

Preparation of Table 2 involved entering manually in to an Excel sheet the data output by the program. Every possible care has been taken to ensure accuracy of the data shown in Table 2. The correctness of data in a row can however be checked by first noting the akṣaragaṇa-based definition of the particular Metre from any standard book on Sanskrit Prosody and converting it to the characteristic string. Once the characteristic string is checked, total number of akṣaras and total number of  mātrās can be verified. tāla/laya data can also be verified from the characteristic string.

## 7.0 Compositions in New Metres based on this exploration :

As a sample of what is possible, we give below some verses composed as per mātrā-gaṇa definition of a few popular Metres. From the point of view of  akṣaragaṇa system the mātrā-gaṇa definition applies to a varga (group) of Metres. For example, svāgatāvargaḥ refers to a group of Metres which are rhythmical neighbours of svāgatā Metre. Each pāda of a verse may have its own characteristic string, but all the four pādas follow a common mātrā-gaṇa definition. It is to be pointed out that this varga concept is different from the traditional concept of upajāti.

**१२४ २(द१तद)->स्वागतावर्गः**

** **पाहि कृष्ण पतितं सदयं मां तववदनस्मितरुचिविषयोऽहम् ।

सपदि माधव भवानि यथा त्वं मन्मनसा निष्कासय पापम् ॥

124 2(da1tada)->svāgatāvargaḥ

pāhi kṛṣṇa patitaṃ sadayaṃ māṃ tavavadanasmitaruciviṣayo'ham ।

sapadi mādhava bhavāni yathā tvaṃ manmanasā niṣkāsaya pāpam ॥

**८४ २(द१द१द)->रथोद्धतावर्गः**

** **भावयामि यमुनानदीतटे नन्दतनय दरहसितविद्युता ।

भ्राजमानघनविग्रहं तव प्रतिदिनं मनसि हर्षतुन्दिलः ॥

84 2(da1da1da)->rathoddhatāvargaḥ

bhāvayāmi yamunānadītaṭe nandatanaya darahasitavidyutā ।

bhrājamānaghanavigrahaṃ tava pratidinaṃ manasi harṣatundilaḥ ॥

**१९० ४(१दद)->भुजङ्गप्रयातवर्गः**

** **नमस्ते भुजङ्गप्रयातप्रवीण द्विजिह्व त्वया सह कदापि प्रसङ्गः ।

न भूयात् कुटिल मे तथा संचर त्वं यथा मत्सकाशं न गच्छेरनल्पः ॥

190 4(1dada)->bhujaṅgaprayātavargaḥ

namaste bhujaṅgaprayātapravīṇa dvijihva tvayā saha kadāpi prasaṅgaḥ ।

na bhūyāt kuṭila me tathā saṃcara tvaṃ yathā matsakāśaṃ na gaccheranalpaḥ ॥

**१४६ २ (दद१दद) ->इन्द्रवज्रावर्गः**

मेघानतीत्यास्ति हिमालयाख्यो दिश्युत्तरस्यामधिपो नगानाम् ।

पूर्वापराब्धिमितसुदीर्घबाहुः गाढहिमपुञ्जैरभिषिक्तशृङ्गः ॥

146 2(dada1dada) ->indravajrāvargaḥ

meghānatītyāsti himālayākhyo diśyuttarasyāmadhipo nagānām ।

pūrvāparābdhimitasudīrghabāhuḥ gāḍhahimapuñjairabhiṣiktaśṛṅgaḥ ॥

**१९९ ३ (दतद)-> वसन्ततिलकावर्गः **

भवितासि मम हृदयमन्दिरदेवता त्वम् कथमहो बुद्ध्वापि मां मदनाग्निदग्धम् ।

रुष्टेव भग्नेव मानिनि भाषसे त्वम् याचे क्षमां कथय कोऽस्ति ममापराधः ॥

199 3(datada)-> vasantatilakāvargaḥ

bhavitāsi mama hṛdayamandiradevatā tvam

kathamaho buddhvāpi māṃ madanāgnidagdham ।

ruṣṭeva bhagneva mānini bhāṣase tvam

yāce kṣamāṃ kathaya ko'sti mamāparādhaḥ ॥

## 8.0 Conclusion :

Although the age-old akṣara-gaṇa-system has served poets and readers of Sanskrit very well by its precise method of defining Metres, its opacity has been an obstacle for studying in detail the beat-structure inherent in Metres. This paper describes how by directly studying the characteristic strings of Metres, one can discover the beat-structure of Metres through the twin concepts of tāla and laya. An appropriate computer program developed for the purpose has rendered this attempt easier and has in addition helped in compiling data for a large number of Metres (Table 2). Table 2 itself is quite innovative in that it is a unique attempt to provide data on a large number of Metres arranged serially in terms of total number of mātrās instead of the traditional sequence in terms of akṣaras. Compositions in new Metres demonstrate the utility of the approach. It is hoped that this paper based on an out-of-the-box approach will open up a new and rich area for further exploration in Sanskrit prosody.

## 9.0 References

Primary Sources:



1. Vṛttaratnākaraḥ of Kedārabhaṭṭa: Edited by  śilāskandhamahāsthavira; Nirṇayasāgar press; Mumbai; 1948.
2. Chando'nuśāsanam  of Hemacandrasūri: Edited by H D Velankar; Singhījainaśāstraśikṣāpīṭh Bhāratīyavidyābhavan, Mumbai 1961

Papers:

Murthy G S S: Characterizing classical anuṣṭup: A Study in Sanskrit Prosody; Vol.LXXXIV. Annals of BORI: 2003



## Appendix-1

We demonstrate how starting from the set of tālas with their layas displayed by a Metre one could arrive at a string consisting of  1’s and mātrāgaṇas da,ta,ca etc which fully complies with the set. In some cases we arrive at a string which is a replica of the characteristic string except that a ‘2’(guru) is replaced by ‘da’-gaṇa. In other cases synthesis results in a string which contains ‘ta’,’ca’ etc. mātrāgaṇas also.

We work out the method for 2 Metres, namely pṛthvī and praharṣiṇī.

I) For pṛthvī we have the following data:

No. of akṣaras = 17; No. of mātrās = 24.

Tāla 1: period = 8 mātrās; laya = 1-2-2-1-2; stub = nil.

Tāla 2: 11; laya = nil; stub = “2”.

Tāla 3: period  = 12; laya = 1-3-1-4-3; stub = nil.

We number the mātrās 1 to [24] and mark on which mātrās the periods of tāla and the sub-periods of laya end, as follows:

Tāla 1: 1, 3, 5, 6, 8, 9,11,13,14,16,17,19, 21, 22, 24.

Tāla 2: 11, 22, 24

Tāla 3: 1, 4, 5, 9, 12,13,16,17, 21, 24.

We treat these as 3 sets of numbers and write out the union of these 3 sets in an order. Any member which appears in any set will be a member of the union.

Union: 1,3,4,5,6,8,9,11,12,13,14,16,17,19,21,22,24.

Now we take the successive differences of the ordered members of the union set.

1-2-1-1-1-2-1-2-1-1-1-2-1-2-2-1-2.

For clarity the synthesis is shown graphically at Table 5

Table 5

| mātrā            | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 |
|------------------|---|---|---|---|---|---|---|---|---|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|
| tāla             |   |   |   |   |   |   |   |   |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
| 1                | 1 |   | 3 |   | 5 | 6 |   | 8 | 9 |    | 11 |    | 13 | 14 |    | 16 | 17 |    | 19 |    | 21 | 22 |    | 24 |
| 2                |   |   |   |   |   |   |   |   |   |    | 11 |    |    |    |    |    |    |    |    |    |    | 22 |    | 24 |
| 3                | 1 |   |   | 4 | 5 |   |   |   | 9 |    |    | 12 | 13 |    |    | 16 | 17 |    |    |    | 21 |    |    | 24 |
| Union            | 1 |   | 3 | 4 | 5 | 6 |   | 8 | 9 |    | 11 | 12 | 13 | 14 |    | 16 | 17 |    | 19 |    | 21 | 22 |    | 24 |
| Resulting string | 1 |   | 2 | 1 | 1 | 1 |   | 2 | 1 |    | 2  | 1  | 1  | 1  |    | 2  | 1  |    | 2  |    | 2  | 1  |    | 2  |

As we are only concerned with the timings of beats and sub-beats, ‘2’ in the resultant string is a ‘da’ gaṇa and it is proper to write the string as

1da111da1da111da1dada12.

We can see that this is indeed the characteristic string of pṛthvī! We also note that tāla 2 does not provide any mātrā instant which does not appear in tāla 1 or  tāla 3. It is a redundant tāla or it is a tāla which gets automatically satisfied when tāla 1 and tāla 3 are satisfied. We could say that the intrinsic rhythm of pṛthvī is fully defined by tāla 1 and tāla 3 or  simultaneous playing of these 2 tālas results in a rhythm characteristic of pṛthvī. However, not all Metres can be thus fully defined in terms of their tālas and layas.

ii) For praharṣiṇī (sl.no.185) we have the following data: akṣaras =13;  mātrās = 20;

tāla / laya: 4; 6; 9; 2422.

We number the mātrās 1 to [24] and mark the mātrā-instants on which the periods of tāla and the sub-periods of laya end, as follows:

tāla 1: 4,8,12,16, 20

tāla 2: 6,12,18,

tāla 3: 9,18

tāla 4: 2,6,8,10,12,16,18,20

Union: 2,4,6,8,9,10,12,16,18,20.

Now we take the successive differences of the ordered members of the union set.

2-2-2-2-1-1-2-4-2-2-> dadadada11dacadada.

_ _ _ _ _


## Notes

[^1]:
Some aspects of this paper were presented by the author in the 17<sup>th</sup> World Sanskrit Conference held in Vancouver, 9<sup>th</sup> to 13<sup>th</sup> July, 2018 under the Title,”Computer-aided study of rhythm in _akṣaragaṇa_ based Metres”.

[^2]:
Email ID: murthygss@gmail.com

[^3]:
When a Sanskrit term is used, an English equivalent is provided in brackets at the first appearance of the term, wherever feasible.

[^4]:

[^5]:
“द्वित्रि चतुः पञ्च षट्कला दतचपषा द्वित्रिपञ्चाष्टत्रयोदशभेदा मात्रागणाः ॥ १-३ ॥“ “dvitri catuḥ pañca ṣaṭkalā datacapaṣā dvitripañcāṣṭatrayodaśabhedā mātrāgaṇāḥ ॥ 1-3 ॥“ : Velankar: Chando'nuśāsanam  of Hemacandrasūri page २.

[^6]:
Murthy: 2003, Annals BORI, 101-115.

[^7]:
The source code of the program written in Java computer language is available at: [https://github.com/GSSMurthy/VruttaRhythms](https://github.com/GSSMurthy/VruttaRhythms)

[^8]:
What is referred to as “tāla” in this paper is “taalBasic” or “basic taal” in the program, which was written much earlier.

[^9]:
Velankar: Chando'nuśāsanam  of Hemacandrasūri : para 14 of Introduction 

