cevelop.github.io
=================

Repository for the Cevelop website.

The site is based on [Jekyll](http://jekyllrb.com). Each commit on the master branch builds and releases the site automatically.

Thanks to [Docker](https://www.docker.com/), no dependencies have to be installed locally. Just execute the following command:

    docker run --rm -it -v $(pwd):/srv/jekyll -p 127.0.0.1:4000:4000 jekyll/jekyll:pages bash -c "gem install webrick && jekyll serve"

The site will then be available on http://localhost:4000 and is rebuilt automatically with each change.
