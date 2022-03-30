# VirtualBow User Manual

The VirtualBow user manual is created with [Asciidoctor](https://asciidoctor.org/), a tool that reads files in AsciiDoc format and converts them into various output formats.
Asciidoctor and the required extensions for generating [PDF](https://asciidoctor.org/docs/asciidoctor-pdf/) and [multi-page HTML](https://github.com/owenh000/asciidoctor-multipage) require [Ruby](https://www.ruby-lang.org/) and can be installed with

    gem install asciidoctor
    gem install asciidoctor-pdf
    gem install asciidoctor-multipage    

To generate the HTML output, run

    asciidoctor-multipage book.adoc -D build/

To generate the PDF output, run

    asciidoctor-pdf book.adoc -D build/
