dr7-drupal-runner-example
=====

Minimal vanilla [Drupal](https://www.drupal.org/) 7 build set-up for testing Drupal Runner.


## Usage

    cd /path/to/your/webroot/dr7.drupal.dev
    ln -s /path/to/this/repo/examples/dr7-drupal-runner-example sites/dr7
    cd sites/dr7
    composer install

    # Can use a relative path to the docroot:
    vendor/bin/robo drupal:magic ../..

    # Or, more sensibly, an absolute path:
    vendor/bin/robo drupal:magic /path/to/your/webroot/dr7.drupal.dev
