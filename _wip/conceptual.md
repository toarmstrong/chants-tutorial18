
A digital scholarly edition presents the opportunity for a multidimensional text encoding scheme.  It is first organized into a citable structure which is canonical, universal, and reproducible.  Next, the XML structure provides information necessary to create different editions of the text (digital, diplomatic, etc.).  Finally, it provides analytical information via indexes and tags.

-	Citable Structure
-	Variable editions
-	Textual Analysis

CTS URNs provide a canonical scheme for citing a passage of text within a hierarchical structure.  Developed by Neel Smith and Christopher Blackwell for the Homer Multitext Project, CTS notation “aims to model works as they are cited by scholars” rather than as they are catalogued by librarians.  URNs are the most appropriate identifier because they are location-independent and persistent.  The structure entails a namespace and a work identifier, then a passage reference when applicable. The namespace identifies the general category for a work (i.e., ‘chant’ or ‘greeklit’) and is resolved by a recognized CTS service.  The work identifier demonstrates a text group or work and an exemplar (i.e., ‘massordinary’ for chants for the Christian Mass Ordinary; and ‘sgc359’ for St Gall codex 359).  

Encoding variations in text using TEI-compliant XML enables editors to create multiple editions from the same document. For example, encoding an abbreviation or misspelling as it appears on the page and with the editor’s suggestions. From a single document, it is thus possible to create a diplomatic plaintext, an edited text, and so on.  This is useful because it does not require choosing either diplomatic or critical but uses the digital space to create both within the same document.  **parsing? tokenization?

The third element to this scheme uses tags for analysis.  This would include tags for personal names or rubric.  With an index of personal names and tags enabled within the text, we add an additional layer of analysis: how do the selected tags demonstrate an additional layer of the textuality? **

We have applied this abstract model to the Chant project, which is derived from HCMID.  To fulfil the first requirement (citable structure), we apply CITE architecture and CTS URNs.  This structure is further useful to Chant because it allows for separate but parallel aligned documents for text and neumes.   It applies the next (variations) with a specified code library.  
