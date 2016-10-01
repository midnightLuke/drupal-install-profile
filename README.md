# Drupal Install Profile

This is a basic Drupal install profile with the modules/themes I usually have 
installed.  After years of simply using the standard install profile and then
`drush`ing the site into submission I put this together.  It's optimized to
quickly set up a site for prototyping basic stuff out for developers.

## Basic Usage

1. Use the makefile to build the site out (drush make is cool with remote
makefiles).  
`$ drush make https://raw.githubusercontent.com/midnightLuke/drupal-install-profile/7.x-1.x/luke.make.yml [subdirectory]`
2. Use the install profile to install the site.  
`drush site-install luke --db-url=mysql://[user]:[password]@localhost/[database]`

Boom, quick and easy.
