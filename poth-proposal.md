# 2018 proposal

## Editing Manuscripts with Neumes Using the "Virgapes" Digital Neume Alphabet

In this project, we present a new system for digitally encoding Medieval manuscripts with chant marked with neumatic musical notation. We show how we can use these editions to search for patterns such as the longest group of neumes which repeat, or the longest melisma, or to explore correlations between neume patterns and the vowels of the corresponding text.

We begin by aligning parallel transcriptions of text and musical notation; both transcripts are indexed to manuscript pages and to visual evidence using standard identifiers. This design makes systematic querying of the transcribed neumes possible. It also supports interactive browsing of automatically created views juxtaposing facsimiles with transcriptions. This standard allows us to compare patterns across manuscripts.

The key to digital search and manipulation of the editions is an "alphabet" for encoding neumes, which we call "Virgapes," named for two one-note neumes, virga and pes. Each distinct neume is encoded with a unique four-part code indicating the number of pitches, and the presence of episma and liquescence. This encoding system can be uniformly applied across manuscripts varying in style, hand, or the set of neumes used, and can be extended. In the course of our work, we have defined encodings for St. Gall style neumes used in Einsiedeln codex 121: the same principles can be applied to other neumes in other manuscripts.

Our poster will illustrate querying of digital editions of neumes, including embedding of illustrations automatically generated from the high-quality public-domain photography of the e-codices project.

> The "Virgapes" system is groundbreaking in digitizing manuscripts; no other extant system has the flexibility, search and retrieval ability, and standardization*** of this system.

# 2019 Proposal

## Semantic Neume Encoding

The “Virgapes” system is a semantic encoding scheme used to digitally represent non-staffed musical notation.  The four-part code point describes the number of pitches and written performative aspects (episema and liquescence).  The musical notation, called neumes, is a graphic representation used in early chant manuscripts.  It does not include information about pitch or length of each note or musical phrase, only relative pitch.  The “Virgapes” system is a solution for an efficient and diplomatic encoding of a chant manuscript with neumes. 

Existing projects interested in encoding neumes either assign pitches to each neume or using extensive XML tags to describe each part of each neume.  In response to the former solution, imposing pitches requires broad editorial decisions that do not fit with a diplomatic reading.  However, excessive tags are unwieldy and inconsistent when completed by different editors. 

The “Virgapes” system is based on Unicode to create a code point for each unique neume character. A virga, which is a one-note neume, is represented as 1.1.0.0.  The first 1 represents the number of pitches (one), the second is an identifier within the one-note neumes.  The next two numbers represent the presence or absence of episema and liquescence, two performance changes noted in writing.  Neumes for the same syllable of text are encoded with dash (-) characters, and for different syllables separated by white space.  

The semantic encoding system employed in “Virgapes” permits specific analysis (based on characters rather than descriptors) and is designed for the digital environment.

> "Virgapes" builds on existing projects and ideas (including unicode and MEI) to develop a new scheme for encoding neume characters.  This is revolutionary to the field of chant scholarship, and will permit extensive analysis not possible with existing tools.
