## setup

- to clone this repo in order to work on the **wiki** section, use
`git@github.com:vcavallo/devwiki.wiki.git` - note the `.wiki` in there.
- install **gollum**: `gem install gollum` (you might need to brew install some
  libraries, like `brew install icu4c` or `apt-get install libicu-dev`)

## working on the wiki

- go into the `*.wiki` repo that you cloned previously
- run `gollum` and navigate to `localhost:4567` or whatever it is for you.
- edit pages and whatnot...

- **gotcha!** - keep the structure flat. _Gollum_ is cool with folders, but
  apparently GitHub isn't :( it'll replace your slashes in the links with
  dashes. maybe there's a way to escape it, but I haven't tried yet.

