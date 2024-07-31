jekyllmap
=========

A simple jekyll site that generates a map!

- 🗺️ **Demo:** [jcody.github.io/jekyllmap](https://jcody.github.io/jekyllmap)

Installation
-------------
    $ git clone https://github.com/jcody/jekyllmap.git
    $ bundle install
    $ bundle exec jekyll serve

Jekyll should then serve the app locally at [http://127.0.0.1:4000/jekyllmap/](http://127.0.0.1:4000/jekyllmap/) (configurable in [`_config.yml`](/_config.yml)).

Note the site is built and served from the [`_site`](/_site/) directory. To make any changes, look at the [`_layouts/`](/_layouts/), [`_includes/`](/_includes/) directories and [`_config.yml`](/_config.yml). All changes will be reflected into a newly built `_site/` static set of HTML pages.

Adding Locations
-----------------
Locations live in the [`locations/`](/locations/) folder as `.markdown` files, supporting images reside in [`images/`](/images/). Jekyll will compile all markdown files by default regardless of filename.

The text file must be structured as follows:

    ---
    title: Address of Parklet
    host: Sponsoring Business
    image: "image_file_name.jpg"

    latitude: 37.776368
    longitude: -122.408594
    ---

Latitude and longitudal coordinates can be found via Google Maps.

Contributions
-------------
Special thanks to [Mick Thompson](https://github.com/mick) & [Code for America](https://www.codeforamerica.org/).
