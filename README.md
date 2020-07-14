# homebrew-postgresql-credly
Homebrew recipe for whatever postgresql version Acclaim (by Credly) production is on.

### Installation Instructions:
- tap the repo
    - `brew tap bruschill/homebrew-postgresql-credly git@github.com:bruschill/homebrew-postgresql-credly.git`
- install the recipe
    - `brew install bruschill/postgresql-credly/postgresql@11.6`
- stop your running installation of postgres
    - if using homebrew, it's probably something like `brew services stop postgresql@11`
- register and start the tapped version
    - `brew services start bruschill/postgresql-credly/postgresql@11.6`
