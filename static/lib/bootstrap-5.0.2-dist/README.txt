Bootstrap 5.0.2 distribution folder

The page currently loads the official Bootstrap 5.0.2 compiled CSS and bundle JS from jsDelivr CDN.
The execution environment used to prepare this project had no outbound network access, so the official distribution files could not be copied into this folder.

To make the project fully offline, download the official compiled distribution from:
https://getbootstrap.com/docs/5.0/getting-started/download/

Extract the Bootstrap 5.0.2 distribution here, preserving its css/ and js/ folders, then change index.html references to:
static/lib/bootstrap-5.0.2-dist/css/bootstrap.min.css
static/lib/bootstrap-5.0.2-dist/js/bootstrap.bundle.min.js
