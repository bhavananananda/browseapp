# BrowseEverything

This is a rails application that uses BrowseEverything gem which allows access to user files from cloud storage.
It uses OAUTH2 to authenticate with Dropbox in this example application.

# Note
This gem does not depend on hydra-head/fedora/solr/db

# Get this app working on your localhost

```bash
Clone this app
bundle install
rake assets:precompile
rails server -b 0.0.0.0 
```
Access the application at http://localhost:3000

Bingo!