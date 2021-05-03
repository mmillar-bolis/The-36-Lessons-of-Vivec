# The Three Lessons of Vivec

#### Rendered in markdown with verse numbers and rubrics.

&emsp;

## View on [GitHub.io][1]

[1]: https://mmillar-bolis.github.io/The-36-Lessons-of-Vivec/

---

#### About:

This is a rendering of The 36 Lessons of Vivec that introduces a verse numbering system, rubrics for certain words, and several optional formats, in the hopes of making it easier for readers to reference specific parts of the text.

The goal is to have fun and work on a project related to my current campaign. As a secondary, maybe this could serve as a set of reference manuscripts to encourage the adoption of a standardized verse system for this book.

Have a look at some of my side projects: [MDunmeris][2], an early and still rough language and religion resource, and [Hayghin Daedric font][3], which is a customized version of [Ayembedt][4].

[2]: https://mmillar-bolis.github.io/MDunmeris/
[3]: https://github.com/mmillar-bolis/HayghinDaedricFont
[4]: https://github.com/georgd/OpenMW-Fonts

---

#### Methodology:

As the basis for the text used in this version, I have dumped the original HTML from the retail edition. Originally, I had used the UESP text, but ran into some minor issues, discussed below. In another sense I figured, if I'm already going to all this trouble, why not just use the original source? The chapters are stored within `Morrowind.esm` and I have dumped each one to an individual file, available on [GitHub][5] for comparison's sake.

It wasn't enough to just tack a number onto each newline. Observing an English copy of the Bible, one might notice that there is a lot of variation in the placement of verse numbers. While deeper investigation brings some understanding to their pattern, it remains clear that trouble recognizing the arrangement comes due to the fact that these works were *originally* composed in another language. A lot of the punctuation marks in common use today only came about as ways for copyists to more clearly communicate the meaning og *one* text in *another* language. To bring that sense of authenticity into the Lessons, I felt that I should not simply trace along each sentence or paragraph to drop in another number as it might lack that authentic appearance of language barrier.

Instead, I went into each chapter to break them down into new and more poetic formats, in order to better judge the flow of ideas, thus inadvertently producing a line-by-line style which I call my *study* edition. After anchoring the numbers, I copied and reassembled the text into their original paragraph forms. The result was a set of verses, the amount of which vary wildly by chapter, their length not withstanding. In this way, I also managed to defy starting every single paragraph with a verse number.

Much of my impressions admittedly come from the New King James Bible, such as [the Psalms][6], [Daniel][7], and [John][8], but really I tried to look at a lot of various examples, including the [Book of the Law][9] from [Thelema][10], which was one of several influences on the Lessons. My goal, gleaned from research, was to break up each verse at the end of a reasonable or cohesive statement. Usually, this means splitting them by sentence but not always, as I tried to balance against length as well.

There are long, quoted passages that can be tricky to follow but there are lots of three-word sentences as well. Sometimes, I just could not decide which end of a verse to tack a small sentence on to. Other times, I couldn't be sure if the meaning of a phrase refers to the sentence that precedes it or comes after, or both, and have instead seemingly awkwardly put a verse number there to avoid breaking up *or* adding the insinuation of any meaning. Vk. 11:15 is an example of this dilemma.

Every chapter is stylistically different and varies in both tone and organization. The aforementioned "*study*" version serves as my scratch-pad for restructuring the text into stanzas by attempting to identify smaller groups of ideas within the text. It's these perceived groupings that I am attaching verse numbers to. I want to be careful and use everything in my untrained skills of textual analysis to preserve the meaning of the work while discovering different ways to parse and present it to the reader. If one were to look at these texts as though they *were* a blend of several different writings from another language, consisting of poems, prayers, tantric quotations, transcriptions, and some narration and commentary accidentally blended throughout, new patterns among the words begin to emerge.

One approach that helped me with deciding where or if I should break up some of the wildly varying sentences was to take verses from the Christian Bible and break them down by their word length to get a better impression of how *those* idea groups were separated when brought into new languages. Identifying the edge cases provides an example of how verse structures play out in tricky sections of text.

For example, here are ten of some of the longest and ten of some of the shortest verses in the NKJV version of the English bible:

|     Long Verses    | Words |      Short Verses     | Words |
|-------------------:|:------|----------------------:|:------|
|       Esther  8:9  |  81   |            John 11:35 |   2   |
|      Ezekiel 48:21 |  80   | 1 Thessalonians  5:16 |   2   |
|     Jeremiah 21:7  |  79   |    1 Chronicles  1:25 |   3   |
|       Joshua  8:33 |  79   |            Luke 17:32 |   3   |
|       Daniel  5:23 |  79   | 1 Thessalonians  5:17 |   3   |
|      2 Kings  6:32 |  77   |          Exodus 20:13 |   4   |
|      2 Kings 16:15 |  77   |          Exodus 20:15 |   4   |
|     Jeremiah 33:11 |  76   | 1 Thessalonians  5:20 |   4   |
|      Ezekiel 46:9  |  74   | 1 Thessalonians  5:25 |   4   |
|     Jeremiah 44:12 |  74   | 1 Thessalonians  5:19 |   5   |

We can see the organizational extremes that arose to contour to the text. Sometimes, it did make more sense to have closer markers, but in other areas, especially the Hebrew texts, there were already organizational standards in place which lend to their more consistent numbering patterns. However, there's still a lot of precedent to break up especially long ideas and sentences. For example, Ephesians 1:3-14, when viewed in the original Greek, is a single run-on sentence comprised of 202 words. In the NKJV, it is split into 4 sentences across 3 paragraphs, with a total of 263 words. So even in translation, there is a wide degree of variability with how the resulting text will turn out.

In addition to inserting verse numbers, I have decided to highlight Ehlnofex words in red. I believe their implementation is not dissimilar to the use of Dominical words, nor Vedic mantras. I also think that incorporating some color will produce results that mesh well with artwork found elsewhere within the game, such as tapestries. It also gives certain embelishment to the work by drawing the reader's eye to those passages.

My initial interpretation of a [Polygon article][11] left me hopeful of a Morrowind [Q source][12] that was possibly whittled down and *restructured* for clarity and maybe even to fit the game's constraints as well. However, a few months after completing this project, I came across an [interview with the author][13] that stated otherwise:

> It took about a week and I totally pantsed it. 98% of the edits were typos and grammar, with the biggest one being Kurt's idea of how to stick a secret message in, which meant he counted a lot and gave me a buncha numbers and made a word change or three so it'd fit.
>
> I knew some amount of structure I wanted that first day, and had a guide from real world texts of mystery religions for a lot of the intonation I wanted to pull off, and a list of skills that needed to go up for mechanics reasons. So, like, that's why there's a scripture about maces lol.
>
> Wait, that only makes sense if you know how this batch of Morrowind books came about. Todd/Ken/Whoever needed a certain number of skill points to come out of the in-game books, freelanced Ted to write a fuckhueg bunch of them, one skill point per book, and he was like yo Michael, this is a buncha books, want to take fifty of them?
>
> So I divied up my 50, said I'd make 6 into Vivec's Bible and figure out the others. I wrote those six, said whoops, lemme do more of these because I can't stop and near the end I knew it was going to end up being 36 exactly. (I forget what the other fourteen books I did for that batch were, though. I think I asked, er, pleaded with Kurt to do a few of them because the deadline was insane.)
>
> It might be of interest to know that I wrote them all in the order they are now. Like, there was never any, oh this one actually goes here and that there kind of stuff. Is that interesting? It certainly was to me when I thought of it a second ago.
>
> Anyhoo, I was exhausted most nights of that week, and I bless my roommate at the time to this day for leaving food, smokes, and bourbon outside my door at dinner time. I pissed in a drive-thru coke cup from Rally's Burgers because I didn't want to stop typing Sermon 35.
>
> For the record, I still think it's a kind of magic spell that let me write a magic spell, but hey, when you're holding a cup to piss in while still typing with your left hand, I can see how it all might get confused.

And [further down][14]:

> But yeah no, I guess that's another interesting thing: there was nothing left on the cutting room floor. I got in, I got out.
>
> Some of it is melody to me, but it always means a thing, even if it's a shape I was drawing in the words, because I see sound.
>
> No, for real, I've pretty acute sound/sight synesthesia, which definitely played a part.

[More recently][15]:

> I'd say most of the Cosmology stuff came out over a short period of time. That's when the big list of pantheons of gods was created. I did write that particular document in a night because I remember the empty office being spooky. The Creation Myths and the Dragon Break stuff was done during this part. Ken wrote the Cyrodilic myth.
>
> The first PGE was another short period- maybe five weeks, but Kurt did a couple of the province entries and lots of that lore came from previous conversations. We had to hurry this one as Redguard's ship date was fast approaching and I had to draw all the illustrations in it too.
>
> The Morrowind concept art fueled the lore which in turn fueled the concept art. That stuff was done mostly during the development of Redguard. Actually got in trouble with Todd cuz I was drawing too much Morrowind stuff when I shoulda been making models for RG.
>
> The big blasts were definitely the 36 Lessons - done in a week, siloed in a single room, food left outside the door by roommate but hey kids no drugs, just lots of smokes and bourbon- the Mythic Dawn Commentaries were all written on a couple of bus rides, and all the Towers lore which I wrote one night at a laundromat waiting for my sheets to dry.
>
> So yeah, a mix of time with occasional brain blast all at once.

This directly refutes any notion of these books having been written or even planned with additional chapters. Further, it confirms that each chapter was written in sequential order which may help to narrow down the evolution of ideas such as the Walking Ways and CHIM. The book, having been written in only a week, was likely complete by May of 2001 when [initial chapters][16] were becomming available online.

As a last note, I have discovered other projects that break the game's books down into sets of data. [This one][17] tags significant words to gain an understanding of their overlap among the various books found within the game.

[5]: documents/index-esm.md
[6]: https://www.biblegateway.com/passage/?search=Psalm&version=NKJV
[7]: https://www.biblegateway.com/passage/?search=Daniel&version=NKJV
[8]: https://www.biblegateway.com/passage/?search=John&version=NKJV
[9]: https://www.sacred-texts.com/oto/engccxx.htm
[10]: https://en.wikipedia.org/wiki/Thelema
[11]: https://www.polygon.com/2019/3/27/18281082/elder-scrolls-morrowind-oral-history-bethesda#Z2a5Je:~:text=supposed%20to%20write%2050%2Dsome%20books
[12]: https://en.wikipedia.org/wiki/Q_source
[13]: https://www.reddit.com/r/teslore/comments/bs65z7/eurogamers_36_lessons_of_vivec_article_may_23rd/eollkt7/?utm_source=share&utm_medium=web2x&context=3
[14]: https://www.reddit.com/r/teslore/comments/bs65z7/eurogamers_36_lessons_of_vivec_article_may_23rd/eolsmdi?utm_source=share&utm_medium=web2x&context=3
[15]: https://www.reddit.com/r/ElderScrolls/comments/ip7cbv/cocaine/g4j7pfj/
[16]: https://web.archive.org/web/20020817033245/http://m0use.net/~uesp/print.shtml?/~uesp/morrow/books/mwsermon1.shtml?(none)
[17]: http://morrowind.newtfire.org/librarium/morrowindTables.html

---

#### Textual Differences:

Initially, the UESP Wiki served as the basis of my editions. Historically, it has been the resource for much of my Morrowind related references. Generally, it remains a primary and influential source alongside [the Imperial Library][18]. The UESP features multiple versions of the Lessons to account for any changes between games. I opted to use the [Morrowind page][19] version; my original intent was to avoid any differences between the original game's text and TES:Online, including the deuterocanonical [thirty-seventh chapter][20] and [sermon zero][21]. Unfortunately, I later fond out that all game-specific versions of text on that site are sourced from the lore page version; the text bodies are not actually entirely separate.

As I went further through my editing process, I had discovered that there were indeed small textual errors in UESP's versions that were not present in the Imperial Library ones. Such changes would seem small to most, but in a couple of cases constituted a restructuring to the formatting. For example in Sermon Eight on the UESP, the following sequence, at the time of my collection, was rendered thusly:

> Ayem said to Nerevar:
>
> 'Seht who is Azura....

Note the colon and the dropping of the quotation to the next line. I had not carefully checked for these formatting changes until late into editing, but here is how the game renderes the text:

> Ayem said to Nerevar, 'Seht who is Azura...

No line difference. Sure, part of it is the hazardous nature of keeping a public Wiki clean. In places where spelling errors are present in the source material, UESP has made diligent efforts to preserve them and leave detailed notes. However, small formatting changes have managed to slip through, and in this case, every comma before a quote in this chapter was changed to a colon with a return.

I don't levy these as criticism of the Wiki. On the contrary, I find this to be more readable and am fascinated further by the fact that I too copied these errors before discovering them, under the false assumption that nothing had been changed. *Woops.* In any case, this appears to be an edit to the text that sprouted up naturally. Rest assured, I have already submitted my corrections to the wiki before posting this write-up.

Another observation I made on formatting was the difference between the sermons posted online *before* the release of the game, as opposed to the slightly different way they were structured for the game. Undoubtedly, each sermon in the dense and cramped pages of the in-game tomes received it's respective layout primarily due to interface and resolution constraints. *However*, the versions of these texts that were posted to Bethesda's forums, and subsequently [redistributed][22] on websites during the months prior to the game's release, feature indentations to some sections within the body.

Again, this is a revelation that might seem trivial to most. However, regardless of the reason, I found it interesting to see that the Imperial Library and UESP, at some point in the ten years after Morrowind, went away from indenting those sections of text, making the format effectively dead.

At the time that I sampled UESP's copy of sermon ten, the following passage was layed out like this:

> ...or, better, in the skin of his enemies.
>
> "The eyelid of the kingdom shall fill thiry[sic] and six folios, but the eye shall read the world."
>
> By this the Hortator needs me to understand. The sword is an impatient signature. Write no contacts on...

Note that after the quotation, the next sentence falls to the proceeding line. However, in the game, it is rendered as such:

> ...or, better, in the skin of his enemies.
>
> "The eyelid of the kingdom shall fill thiry and six folios, but the eye shall read the world." By this the Hortator needs me to understand.
>
> The sword is an impatient signature. Write no contacts on...

Still also, in the old HTML versions, this passage appears with indentations:

> ...or, better, in the skin of his enemies.
>
> &emsp;&emsp;"The eyelid of the kingdom shall fill thiry and six folios, but the eye shall read the world." By this the Hortator needs me to understand.</span>
>
> The sword is an impatient signature. Write no contacts on...

I found these variations worthy of mention because each version *could* lead to slight differences in tone and interpretation. Does the phrase, *'By this the Hortator needs me to understand'* book-end the quotation? Does it lead into the next paragraph? Is it meant to start it? How is one idea jumping off into another? In certain scenarios, indentation could be considered an important factor in presentation and emphasis as well, which is why I decided to preserve it in my *traditional* formatting.

In the end, I found enough deviations in the wiki to warrant going back and rebasing the *entire* text on a dump I made of the game's resources. As stated, I submitted my corrections to UESP as well, so where it's possible their version *should* now match that of the games.

[18]: https://www.imperial-library.info/
[19]: https://en.uesp.net/wiki/Morrowind:The_36_Lessons_of_Vivec
[20]: https://en.uesp.net/wiki/Lore:36_Lessons_of_Vivec,_Sermon_37
[21]: https://en.uesp.net/wiki/General:Sermon_Zero_of_the_Thirty-and-Six-and-Nine_Sermons_of_Vivec
[22]: https://web.archive.org/web/20020407033511/http://www.m0use.net/~uesp/morrow/books/morbooks.shtml

---

#### My Changes:

After rebasing this project directly on the dumps of the game's text, these were the edits I then made, and are present in each of the versions I reassembled. In total, only 16 words have been changed. Four of those are the same misspelled word (*AMLSIVI*, likely the result of a copy error) and three of them are compactions (majordomo) and one was a missing letter (PSJJJJ). Only 1 noun change was made (Necrom is the *actual* City of the Dead) and 1 word was removed (a leftover *to*). There were only 11 grammatical changes, and all within Sermon Eleven alone, curiously enough.

See the [full list of changes][23].

[23]: changes.md

---

#### Verse Numbering:

A millennia before anyone in the west was even fretting over how to divide up their increasingly complex [codices][24], the [Rigveda][25] had grown, along with three other complementary texts within the [Vedas][26], to great prominence as one of the central holy texts within [Hinduism][27]. It's name is a mashup of two words: *&#7771;c*, which literally translates to *praise* but also constitutes the word for *verse*, and *veda* which means *knowledge*. Verses were used to divide up [*sutras*][28], often the written collections of proverbs, [*mantras*][29], and the aphorisms that surround them, that were transmitted orally until priests began to write them down. Verse marks are often denoted with a [double-danda][30], which are two vertical marks that act as a paragraph or section full-stop.

For centuries, there have been methods of dividing the [Masoretic texts][31] into sections and verses (called *parashah* and *passuk*) that one could intuit if they knew Hebrew and were trained in reading the text. In 1437, [Isaac Nathan ben Kalonymus][32], a French Jewish philosopher and rabbi, began work on a Hebrew concordance of the [Tanakh][33], called *Meir Netib*. Organizationally, Nathan divided most lines by [Hebrew full-stop marks][34] and placed a number in the notes column every five verses. He worked on his concordance for ten years, however it wasn't published and circulated until 1523.

Similar to the Tanakh, the [Quran][35] has traditionally been arranged into sections and verses (called *surat* and *ayah*). Initially, the Arabic script [lacked diacritical markings][36], making it difficult to distinguish double-consonants and long vowels. In addition, the primary way of distinguishing the end of a verse was to follow it with an empty space. Over time, Muslim scholars did not entirely agree on [interpretations][37] of where each verse should be split. The ninth century Muslim scholar [Abu Bakr Ibn Mujahid][38] is generally credited as having canonized the [seven different reading systems][39] that lead to [five common verse systems][40].

However, during the [Umayyad period][41], diacritic and punctuation marks began to make their way into the Arabic script. Copyists began to fill the empty space at the end of verses with a new full-stop character (called a *waqf taam*). With the growing adoption of the [Hindu-Arabic numeral system][42] in the eighth and ninth centuries, writers began to fill this glyph with it's respective verse umber. Today, most printed Qurans use the Kufi/Egyption verse system.

Verse numbering in the modern sense didn't begin to appear in the texts of the [Christian bible][43] until the early 1600s. However, in 1509 [Jacques Lefevre d'Etaples][44] published the [Psalterium Quintuplex][45], which was a rendering of five different [psalters][46] in French. Lefevre had his own verse system to organize the work.

In 1528, [Santes Pagnino][47] published his *Veteris et Novi Testamenti nova translatio*, a new translation of the Old and New Testament sections of the Christian bible into Latin. This is the first edition to contain verse numbers alongside the both sets of texts in a single volume. Pagnino was able to adopt the Hebrew full-stop system into his translation of the New Testament as well, making each verse roughly similar in length to the Old Testament.

Today, most Christian bibles use the verse numbering system introduced by [Robert Stephanus][48] in his 1551 edition of the Greek New Testament. His 1555 edition of the Latin [Vulgate][49] was the first to blend verse numbers into the body of the text.

About half-way through creating my verse system, I came across [the Theoretical Whirling School][50] (TWS), which was run by user [*Nigedo*][51]. This may be the very first group to come up with a text division scheme for the Lessons, all the way back in 2004. At the point that I was in this project, I had believed that no one must have published any such works and that I might be the lonely first to come up with verses, but it appears that I simply missed that era of work, now lost to time.

Reviewing the TWS Edition, I am thankful to say that my system of division turned out unique in comparison. However I am fascinated by the laudable, now understandably difficult work. There are some approaches that look like they overlapped with my own ideas. For example, Nigedo chose to break up sermon 35 into multiple stanzas. They also break up some longer paragraphs into multiple verses, such as the second section of sermon 21. The choice to use HTML number lists to present verse headings was also a familiar sight. On the other hand, the count of verses in the TWS Edition is fairly consistent from chapter to chapter while my edition can vary wildly, likely because I allowed for some uneven divisions, as explained in my methodology.

An archive of the TWS Edition of the Lessons is still available on [archive.org][52]. I have also made a copy of the surviving pages in markdown, [available on GitHub][53]. The website in general is impressive and worth a look. It's a shame to see it's been gone for more than a decade.

[24]: https://en.wikipedia.org/wiki/Codex
[25]: https://en.wikipedia.org/wiki/Rigveda
[26]: https://en.wikipedia.org/wiki/Vedas
[27]: https://en.wikipedia.org/wiki/Hinduism
[28]: https://en.wikipedia.org/wiki/Sutra
[29]: https://en.wikipedia.org/wiki/Mantra
[30]: https://en.wikipedia.org/wiki/Danda
[31]: https://en.wikipedia.org/wiki/Masoretic_Text
[32]: https://en.wikipedia.org/wiki/Isaac_Nathan_ben_Kalonymus
[33]: https://en.wikipedia.org/wiki/Tanakh
[34]: https://en.wikipedia.org/wiki/Sof_passuq
[35]: https://en.wikipedia.org/wiki/Quran
[36]: https://en.wikipedia.org/wiki/Qira%27at#Quranic_orthography
[37]: https://answeringislam.org/Quran/Text/numbers.html
[38]: https://en.wikipedia.org/wiki/Ibn_Mujahid#Canonisation_of_the_Quranic_Readings
[39]: https://en.wikipedia.org/wiki/Seven_qira%E2%80%99a
[40]: http://muslimcanada.org/quran_division.html
[41]: https://en.wikipedia.org/wiki/History_of_the_Quran#Umayyad_Period_(44/661%E2%80%93132/750)_%E2%80%93_Hijazi_script
[42]: https://en.wikipedia.org/wiki/Hindu%E2%80%93Arabic_numeral_system
[43]: https://en.wikipedia.org/wiki/Christian_bible
[44]: https://en.wikipedia.org/wiki/Jacques_Lef%C3%A8vre_d%27%C3%89taples#Works
[45]: https://www.google.com/books/edition/Quintuplex_Psalterium/
[46]: https://en.wikipedia.org/wiki/Psalter
[47]: https://en.wikipedia.org/wiki/Santes_Pagnino
[48]: https://en.wikipedia.org/wiki/Robert_Estienne
[49]: https://en.wikipedia.org/wiki/Vulgate
[50]: https://web.archive.org/web/20050308071257/http://www.whirlingschool.net/index.html
[51]: https://web.archive.org/web/20041204075336/http://whirlingschool.net/contact.html
[52]: https://web.archive.org/web/20050226005458/http://whirlingschool.net/lore/numbers/preface.html
[53]: documents/index-nigedo.md

---

#### Red Letters:

Another major influence on the Lessons is the [Bhagavad Gita][54], and [Indian epics][55] in general. The Dunmeri language as written in the Daedric script also bears a strong resemblance to [Sanskrit][56], especially in following the stylings of some [ancient manuscripts][57]. It's been a [historic practice][58] to write headings, [colophons][59], and annotations in red, to distinguish commentary and heads that surround the body.

In some Vedic and Jainist manuscripts, it has also [been observed][60] that alternative colors, especially red, were used to highlight [important phrases][61] or [symbols][62] for the reader. In general, highlighted sections or words in red are called [rubrics][63], from the Latin word *rubrica* which means *red ochre,* the crushed clay that was used to make the particular ink. In medieval Europe, there even came to be an official process for adding red to manuscripts, called [rubrication][64].

The rubrication process was a matter of discipline that belonged to [scriptoria][65], the preparation of manuscripts for codex production. Initially similar to modern italics, red highlighting was often used for headings and emphasis within these manuscripts. In [Christian liturgies][66], such as during the Liturgy of the Eucharist in the Catholic Mass, the [Words of Consecration][67], often called the Dominical Institution, are stated by the priest as part of a sacrament of bread and wine. While it continues to be the practice to rubricate these words in missals, the practice did not make the jump to the Christian Bible until around 1900.

Because there were no quotation marks in any of the historic manuscripts, they were not present in the initial English versions of the Bible either. In an attempt to add emphasis, but also to differentiate from the ambiguously surrounding text, [Louis Klopsch][68] applied rubrication to the words among the four Gospels that are understood to have been literally spoken by Jesus Christ, referred to as the Dominical Words. Klopsch's rubricated New Testament, called the [Red Letter Edition][69] was first published in 1899.

[54]: https://en.wikipedia.org/wiki/Bhagavad_Gita
[55]: https://en.wikipedia.org/wiki/Indian_epic_poetry
[56]: https://en.wikipedia.org/wiki/Sanskrit
[57]: https://en.wikipedia.org/wiki/File:3rd_Chapter_Verses_1-2,_Bhagavad_Gita,_Gurmukhi_script,_Punjab.jpg
[58]: https://d-nb.info/1076359973/34
[59]: https://en.wikipedia.org/wiki/Colophon_(publishing)
[60]: https://www.degruyter.com/view/title/528891?format=G
[61]: https://en.wikipedia.org/wiki/Om_mani_padme_hum
[62]: https://www.degruyter.com/view/title/528891?format=G
[63]: https://en.wikipedia.org/wiki/Rubric
[64]: https://en.wikipedia.org/wiki/Rubrication
[65]: https://en.wikipedia.org/wiki/Scriptorium
[66]: https://en.wikipedia.org/wiki/Christian_liturgy
[67]: https://en.wikipedia.org/wiki/Words_of_Institution
[68]: https://en.wikipedia.org/wiki/Louis_Klopsch
[69]: https://en.wikipedia.org/wiki/Red_letter_edition

---

### FAQ:

*Why add verse numbers to Sermon 29?*

If I didn't, we would be dealing with the opposite form of this question. Really, it's for completeness sake. I tried to be clever about it. And again, the situational need to reference it will likely come up.

*Why add verse numbers to the last line of each chapter?*

Because they are not all quite the same: ch. 18 & 36 are different. Also, because this leaves the opportunity for some Dunmer apocalyptic preacher to claim to have unlocked some sequence to Landfall using a combination of these verse numbers.

*This doesn't even resemble markdown anymore!*

Guilty.

---

#### Assets Used:
Some quick links to items used in this project.

- [Markdown][70]
- [Ayembedt font][71]
- [Casual Dunmeris][72]
- [The 36 Lessons of Vivec][73]

[70]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[71]: https://github.com/georgd/OpenMW-Fonts
[72]: https://casualscrolls.fandom.com/wiki/Dunmeri_language
[73]: https://en.uesp.net/wiki/Morrowind:The_36_Lessons_of_Vivec

---
