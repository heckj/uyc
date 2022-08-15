# Underneath Your Code

How to render (pdf & epub):

    docker pull asciidoctor/docker-asciidoctor
    
    docker run --platform linux/amd64 --rm -v $(pwd):/documents/ --name asciidoc-to-pdf asciidoctor/docker-asciidoctor asciidoctor-pdf -v -t -D /documents/output docs/uyc-book.adoc

    docker run --platform linux/amd64 --rm -v $(pwd):/documents/ --name asciidoc-to-epub3 asciidoctor/docker-asciidoctor asciidoctor-epub3 -v -t -D /documents/output docs/uyc-book.adoc

    # docker run -v $TRAVIS_BUILD_DIR:/documents/ --name asciidoc-to-pdf heckj/docker-asciidoctor asciidoctor-pdf -v -t -D /documents/output docs/uyc-book.adoc
    # docker run -v $TRAVIS_BUILD_DIR:/documents/ --name asciidoc-to-epub3 heckj/docker-asciidoctor asciidoctor-epub3 -v -t -D /documents/output docs/uyc-book.adoc
