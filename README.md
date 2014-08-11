# test rails application for bower rails and mapbox

This is just a quick throw away rails application to demonstrate and issue with bower-rails and mapbox.js

## Installation

    git clone https://github.com/teknofire/test-bower-rails.git
    cd test-bower-rails
    bundle
    rake bower:install
    rake assets:precompile
    # rake aborted!
    # Sprockets::FileNotFound: couldn't find file 'mapbox.js/'