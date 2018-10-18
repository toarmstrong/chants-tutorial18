# Editing Neumes with Virgapes

The virgapes system assigns a unique identifier to every type of neume listed in Cardine's guide to neumes. With a four-part identifier, we can distinguish the number of pitches in the neume, the relative motion of the pitches, the presence and location of an episema, and the presence of a liquescent form. Each part is signified with a number and each part is separated by a period.

## Syntax of Virgapes

`(pitch).(id_number).(episema).(liquescence)`

### Pitch

Number of pitches in a neume

- Virga has one pitch, so is encoded: `1.`
- Pes has two, so is encoded: `2.`

Must be 0, 1, 2, 3, or 4.

### ID Number

Distinguishes between neumes with the same number of pitches with an arbitrary identifier, beginning with one.

- Punctum is the first one pitch neume: `1.1.`
- Virga is the second one pitch neume: `1.2.`

Begins with 1, can extend limitlessly.

### Episema

Notes whether a neume has episema.

- If yes, 1; if no, 0
- Virga with episema: `1.2.1.`
- Virga without episema: `1.2.0.`

### Liquescence

Notes whether a neume has liquescence.

- If yes, 1; if no, 0
- Virga with liquescence: `1.2.0.1`
- Virga without liquescence: `1.2.0.0`
- Virga with liquescence and episema: `1.2.1.1`

## Significative letters

Significative letters follow the same scheme as neumes in Virgapes.  For 'pitch' they are encoded with a `0`, since they carry no pitch.  

A significative letter A: `0.1.0.0`

## Entering neumes

Neumes are edited with relation to the Latin syllables.  

- A blank space stands for separation between syllables
- A dash `-` connects neumes for the same syllable
- Workflow: left to right (beginning with neumes closest to the text), otherwise top to bottom when a significative letter is directly above a neume
- Assume neumes proceed in a continuous line, except for where the scribe is out of space
