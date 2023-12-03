Git repository containing files to build a docker image with shiny-server and `learnr` lessons for a bio-informatics course, designed for and with Dr. Jess Kaufmann.

Lessons include:

* A lesson on logical (boolean) vectors: `logical-vectors`.
    * A follow-up lesson applying logical vectors to filtering rows of a data frame: `filtering`.
* A lesson building on logical vectors and grepl() to do an application on 23 and Me data: `23nMe`

Keeping in mind that the `learnr` lesson files must be *locally rendered* to create the .HTML-file before they will work, the docker build runs a script to create these files.
