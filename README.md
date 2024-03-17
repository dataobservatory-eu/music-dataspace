# Towards a European Music Dataspace

- Make sure you fork this repository (i.e., create an own copy for yourself, see Introduction to GitHub) and do not try to work in the master joint repository.
- Create a` not_included/` subfolder in your local copy if you want a sandbox for your doodles and unfinished work. They will be excluded by `.gitignore`, i.e., they will never leave your computer.
- 🌈 You must abide by the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) Code of Conduct.
- We have a [Contributor's Handbook](https://manual.dataobservatory.eu/).

## Standard folder strucutre and files

### Source and renderred files

The source files (for editing) are Quarto-flavored markdown (`.qmd`) files. The text can be edited with any markdown editor, but to render good-looking presentations and documents, you need Quarto.

_If you render the source files in Quarto, they are exported to the `docs/` folder. These are not synchronised to GitHub. However, we place from time-to-time rendered version on the web, and at each milestone deposit an authoritative copy with DOI in the [Digital Music Observatory](https://zenodo.org/communities/music_observatory/records?q=&l=list&p=1&s=10&sort=newest) space on Zenodo._

`music-data-space.qmd`: 

`SKCMDb.qmd`: _Towards a European Music Dataspace_ from the perspective of [The Digital Music Observatory and the Slovak Comprehensive Music Database (SKCMDb)](https://music.dataobservatory.eu/documents/open_music_europe/slovakia/SKCMDb.html)

`SKCMDb-presentation.qmd`: _Towards a European Music Dataspace_
 from the perspective of [Listen Local Slovakia & SKCMDb](https://music.dataobservatory.eu/documents/open_music_europe/slovakia/SKCMDb-presentation.html#/title-slide).

`slovak-cult-stat-pilot.qmd`: _Pilot Program for Novel Music Industry Statistical Indicators in the Slovak Republic_  Business-to-government data sharing, novel re-use of public sector information for the creation of missing marco-, industry-, and institutional KPIs for the Slovak cultural and creative industry strategy implementation  [living working document](https://music.dataobservatory.eu/documents/open_music_europe/slovakia/slovak-cult-stat-pilot.html) 13 December 2023, DOI: [10.5281/zenodo.10372026](https://zenodo.org/records/10372026)

### Images

`png/` contains illustrations in Portable Network Graphics (.png) format.


### Bibliographies

The `bib` folder contains Biblatex bibliographical information for citations. For example:
- `bib/OpenMusE.bib`: for cross-referencing Open Music Europe documents and statistical products.
- `bib/statisticalLOD.bib`: linked open data in statistics
- `bib/archivesLOD.bib`: linked open data in archives
- `bib/libraryLOD.bib`: linked open data in libraries

Some bibliography is accompanied by Readers.

`reader-dataspace.qmd`: A reader for some of the `bib` files. 

## Templates

`docx`: Document template(s) for rendering to Word.

## Repository history

This repository is an offspring of [antaldaniel/data-ppp](https://github.com/antaldaniel/data-ppp). You can trace back some of the work for earlier commits into that repository.


## Funding 

Some of the work here is _funded by the European Union under Grant No. 101095295. Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Commission's Citizens, Equality, Rights and Values Programme, or the official views of the Ministerstvo kultúry SR, Štatistický úrad SR, Infostat or IKP. Neither the European Union, the Slovak public bodies nor the granting authority can be held responsible for them._