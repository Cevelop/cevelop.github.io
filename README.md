cevelop.github.io
=================

Repository für die Cevelop Webseite

Das ganze basiert auf Jekyll http://jekyllrb.com. Bei einem Commit im master Branch automatisch die Seite neu erstellt und veröffentlicht, weshalb man ein wenig aufpassen muss was man committed.

Dank Docker muss man lokal nichts installieren, folgender Befehl reicht aus

    docker run --rm -it -v $(pwd):/srv/jekyll -p 127.0.0.1:4000:4000 jekyll/jekyll:pages jekyll serve

Unter http://localhost:4000 ist die Seite dann aufrufbar und wird bei Änderungen automatisch neu erstellt.
