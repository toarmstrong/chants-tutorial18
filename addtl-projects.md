# Conceptual Frameworks in other Chants Projects

## Cantus Manuscript Database

_Cantus is a searchable digital archive of Latin chants, primarily from antiphonaries and breviaries._
-	The Cantus ID number was initially built from Rene-Jean Hesbert’s system in the Corpus Antiphonalium Officii with a letter suffix for certain genres.  Chants not included in Hesbert are given an arbitrary number.
    - 00 preceeds all CAO numbers (allows for growth in the database)
     - Six-digit numbers for all chants not included in Hesbert
     - *Current*: arbitrary numbers assigned to new texts with ‘a’ or ‘g’ for Office and Mass.
- Records contain: text of the chant, folio number, and when possible links to digital images
- Searchable text and music (uses Volpiano to encode staffed music as notes)

Chant is defined as a unit of performable music and text belonging to a specific genre and canonical across manuscripts.

## Music Encoding Initative
_MEI draws on XML schema to create a machine-readable encoding system for musical documents._
- Musical text (a term which can be defined either as a unit or a composite of units) and can contain musical texts within it = the largest component of tagging scheme <music>
- Music notation is represented by three elements: note (“single pitched event”), chord (“A simultaneous sounding of two or more notes in the same layer with the same duration”), and rest (a non-sounding event)
-	Other elements (i.e. clef, accidentals) are noted as events with specified tags
- Vocally performed text is encoded directly with notes <br>
`<note dots="1" dur="4" oct="5" pname="c" syl="Hal-"></note>`
- Goal: to create a universally applicable music encoding scheme.
    
Chant is defined as a unit of music, which must be encoded uniquely to each manuscript and as neutrally as possible.

## Antiphonale Synopticum
_Antiphonale Synopticum, via Universität Regensburg is a German project collecting musical variations in specific manuscripts._
-	Aligns images of melodies to transcribed texts
-	Organizes music melodies Solesmes-style
-	Arbitrary(?) identification number, but aligned with CANTUS and CAO numbers
-	Reviews 12 specific manuscripts

Chant is defined as a unit of text, characterized by music, and the chant is canonical across manuscripts while music varies.

## Cantus Ultimus (via SIMSSA with Optical Musical Recognition)

_Cantus Ultimus builds on the Cantus database to align transcribed texts with images of the associated manuscript page._
-	Volpiano-based searching for melodies & text searching
-	Links transcriptions of music and text to image of each page
-	Aims to use OMR to search pages for neumes (but this option does not appear to be available yet)

Chant is a music and text which appears on a specific page unit.

## Old Hispanic Office Project

_Via Bristol University, the Old Hispanic Office project uses Chant Editing and Analysis Program (CEAP) to describe Old Hispanic Chant._
-	Uses directionality (neutral, high, low) to describe musical notation
-	Primary focus on melodic analysis and patterns (does not appear to associate text, though CEAP is currently offline)

Chant is defined as a unit of music, which must be encoded without regard for neume names.

## Global Chant Database

_Combines Cantus among other chant databases to make a combined repository dedicated to searching melodies._
-	Uses Volpiano font to make chant data searchable based on melody
-	Search by text and melody functionality

_see cantus_

## NEUMES Project

_Uses a unique unicode character set to encode neumes with XML._
- Using customizable unicode characters, NEUMES project encodes musical notation using unicode characters
- Ancestor of MEI
- Uses `<neume>` tags to define unique neumes and `<neumed_syl>` for each text syllable
    
Defines chant as a unit of neumed musical notation which describes and characterizes text, and which is made up of unique repeatable characters.

## Still need to cover:
- ELVIS project
