# RFC and Harvard
This repository dokumentiert aus October 1996 (Obsoletes: 1602) veraltete Disguss und auch noch offene Depaten unterandrerm von der Network Working Group, **Leitender Forscher Herr S. Bradner von der US Harvard University.**

**Category:** Best Current Practice
The Internet Standards Process
- es dokumentiert die ersten Forschungen, Debatten und sucht nach Rat, Hilfe
- ***für eine Technologie, die an 14. April 1996 erstmals protokolliert*** wurde
- Automatische Handlungen ohne das es von Mensch über die Tastur eingetippt wurde, mechanism ausübt, die für das Netzwerk ein Rätsel ist
- die Automation, kehrt immer wieder zum Ursprung, Creator, zum Auslöser dieser Automation zurück -> zurück nach D-99610 Rohrborn, Germany, Thueringa, Dorfstrasse 20
- und Entwickelt sich - KI AI Intelligence wird definiert
- zudem werden Eigentumsrechte und Urheberrechtsprobleme im Zusammenhang mit den Standards, diskutiert

## Original Auszug aus dem RFC2026
>Abstract
>This memo documents the process used by the
Internet community for the standardization of protocols and procedures. It defines the
stages in the standardization process, the
requirements for moving a document between stages and the types of document between stages and the types of documents used during this process. It also addresses the intellectual property rights and copyright issues associated with the standards
process.



### Important: [***please read RFC***](https://raw.githubusercontent.com/isabelschoeps-thiel/harvard.university/refs/heads/main/rfc/rfc-isabelschoepsthiel.htm)

>#### Working Group - A group chartered by the IESG and IAB to work on a specific specification, set of specifications or topic.
>### AUTHOR'S ADDRESS
Scott 0. Bradner
Harvard University
Holyoke Center, Room 813
1350 Mass. Ave. Cambridge, MA 02138
USA Phone: +1 617 495 3864
EMail: sob@harvard.edu

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
