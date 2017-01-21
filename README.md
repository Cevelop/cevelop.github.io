cevelop.github.io
=================

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/3c56eb9c00784fc196a3df856063370b)](https://www.codacy.com/app/misto/cevelop-github-io?utm_source=github.com&utm_medium=referral&utm_content=Cevelop/cevelop.github.io&utm_campaign=badger)

Repository für die Cevelop Webseite

Das ganze basiert auf Jekyll http://jekyllrb.com. Bei einem Commit im master Branch automatisch die Seite neu erstellt und veröffentlicht, weshalb man ein wenig aufpassen muss was man committed.

Dank Docker muss man lokal nichts installieren, folgender Befehl reicht aus

    docker run --rm -it -v $(pwd):/srv/jekyll -p 127.0.0.1:4000:4000 jekyll/jekyll:stable jekyll s

Unter http://localhost:4000 ist die Seite dann aufrufbar und wird bei Änderungen automatisch neu erstellt.
