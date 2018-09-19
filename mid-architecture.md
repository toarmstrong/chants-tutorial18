# collections
* `validation.cex`
  * current editorial status of completed pages

# dse
<p>directory for dse files<br>
see <a href="https://cite-architecture.github.io/dse/">DSE Model</a> for documentation</p>

* `XXX.cex`
  * indexes transcribed text,  image documentary evidence, and surface
  * req'd header: `passage#imageroi#surface`

# editions
* `XXX.xml`
  * for example, eins121.xml or eins121-neumes.xml
* `catalog.cex`
* `citation.cex`

# header
<p>used when compiling repository into a single .cex file<br>
see <a href="https://cite-architecture.github.io/citedx/CEX-spec-3.0.1/">CEX 3.0.1</a> for documentation</p>

* `0.library.cex`
* `1.dse-prolog.cex`

# paleography
<p>directory for files with paleographic observations</p>

* `XXX.cex`
  * req'd header: `observation#text#image#comments`

# parser

# scripts
* `mom.sc`
  * a scala script for validating your work

# template-copy-paste
<p>files used for character reference when editing</p>

* `character-reference.md`
  * summary of allowed characters
