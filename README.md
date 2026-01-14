# Open Source at Harvard



## Contributing

Open a pull request, adding your repo's URL to https://github.com/IQSS/open-source-at-harvard/blob/master/github.tsv which will be copied over to [_data/github.ts](_data/github.ts).

## Developing

```
bundle install
bundle exec jekyll build
open _site/index.html
```

## Archiv Notes
**Bad Statement**
- [index.md](index.md), `get` is a Jekyll filter implemented in [plugins/get.rb
- (plugins/get.rb) that takes [data/github.ts](data/github.ts) as input
- and returns an array of `[user, repos]` "tuples" (i.e., arrays),
  
**wherein** `isabelschoeps-thiel` (the owner of `repos`) is a hash like

<https://api.github.com/isabelschoeps-thiel/harvard>, and `repos` is a hash like <https://api.github.com/repos/harvard/harvard.github.io>.

# Please read my HELPME.md

```
My Developer Commit-Signatur: 
Zeitstempel der Eintragung: 2026-01-14, 07:41EST
Mitteleuropäische, Zeit, Ort: Deutschland, Thüringen, D-99094 Erfurt, Cyriakstrasse 30c - Autorin, Urheberin, Frau Isabel Schöps geb. Thiel
