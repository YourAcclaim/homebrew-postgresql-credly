# homebrew-postgresql-credly
Homebrew recipe for whatever postgresql version Acclaim (by Credly) production is on.

### Installation Instructions:
- tap the repo
    - `brew tap YourAcclaim/homebrew-postgresql-credly git@github.com:YourAcclaim/homebrew-postgresql-credly.git`
- install the recipe
    - `brew install postgresql@12.3`
    - if that isn't recognized, try
        - `brew install youracclaim/postgresql-credly/postgresql@12.3`
- stop your running installation of postgres
    - if using homebrew, it's probably something like `brew services stop postgresql@11`
- register and start the tapped version
    - `brew services start postgresql@12.3`
    - if that isn't recognized, try
        - `brew services start youracclaim/postgresql-credly/postgresql@12.3`
