# Standard Architecture
* <a href="#collections">collections</a>
* <a href="#dse">dse</a>
* <a href="#editions">editions</a>
* <a href="#header">header</a>
* <a href="#parser">parser</a>
* <a href="#scripts">scripts</a>
* <a href="#template-copy-paste">template-copy-paste</a>
* <a href="#validation">validation</a>

# collections
* `validation.cex`
  * current editorial status of completed pages

# dse
<p>directory for dse files<br>
 Diplomatic Scholarly Editions<br>
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

# validation
<p>reports on validation of text are written to this directory</p>

# to add
* analyses
* datasets
* docs
* images
* indices
* notes
* project
* relations
* shared/src
* surfaces
* tut
* views
* morphology (PL)
* comparison (PL)
* text_transcriptions (PL)
* configs (HMT-iliad10)
