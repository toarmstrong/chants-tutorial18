# Conceptual Frameworks in other Chants Projects

## Cantus Manuscript Database

_Cantus is a searchable digital archive of Latin chants, primarily from antiphonaries and breviaries._
-	The Cantus ID number was initially built from Rene-Jean Hesbert’s system in the Corpus Antiphonalium Officii with a letter suffix for certain genres.  Chants not included in Hesbert are given an arbitrary number.
   - 00 preceeds all CAO numbers (allows for growth in the database)
   - Six-digit numbers for all chants not included in Hesbert
   - *Current*: arbitrary numbers assigned to new texts with ‘a’ or ‘g’ for Office and Mass.
- Records contain: text of the chant, folio number, and when possible links to digital images
- Searchable text and music (uses Volpiano to encode staffed music as notes)

## Music Encoding Initative
_MEI draws on XML schema to create a machine-readable encoding system for musical documents._
- Musical text (a term which can be defined either as a unit or a composite of units) and can contain musical texts within it = the largest component of tagging scheme <music>
- Music notation is represented by three elements: note (“single pitched event”), chord (“A simultaneous sounding of two or more notes in the same layer with the same duration”), and rest (a non-sounding event)
-	Other elements (i.e. clef, accidentals) are noted as events with specified tags
- Vocally performed text is encoded directly with notes <br>
`<note dots="1" dur="4" oct="5" pname="c" syl="Hal-"></note>`
- Goal: to create a universally applicable music encoding scheme.

## Antiphonale Synopticum
_Antiphonale Synopticum, via Universität Regensburg is a German project collecting musical variations in specific manuscripts._
-	Aligns images of melodies to transcribed texts
-	Organizes music melodies Solesmes-style
-	Arbitrary(?) identification number, but aligned with CANTUS and CAO numbers
-	Reviews 12 specific manuscripts

## Cantus Ultimus (via SIMSSA with Optical Musical Recognition)

_Cantus Ultimus builds on the Cantus database to align transcribed texts with images of the associated manuscript page._
-	Volpiano-based searching for melodies & text searching
-	Links transcriptions of music and text to image of each page
-	Aims to use OMR to search pages for neumes (but this option does not appear to be available yet)

## Old Hispanic Office Project

_Via Bristol University, the Old Hispanic Office project uses Chant Editing and Analysis Program (CEAP) to describe Old Hispanic Chant._
-	Uses directionality (neutral, high, low) to describe musical notation
-	Primary focus on melodic analysis and patterns (does not appear to associate text, though CEAP is currently offline)

## Global Chant Database

_Combines Cantus among other chant databases to make a combined repository dedicated to searching melodies._
-	Uses Volpiano font to make chant data searchable based on melody
-	Search by text and melody functionality


## Still need to cover:
- ELVIS project
- NEUMES project
