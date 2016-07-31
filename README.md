# Naturschutz-Richterswil-Samstagern.github.io
Website for [Naturschutz Richterswil-Samstagern](http://naturschutz-richterswil-samstagern.github.io/)

## Bildergrössen

* Homepage 4 Kategorien: `458px * 200px`
* Headerimages: `950px * 250px`
* Leadimage News: `150px * 200px`
* Bilder Seite (iframes von flickr): `950px x 712px`
* Portraits "Über Uns" `270px x 406px` 

## Newsbeitrag hinzufügen

1. Neue Datei in Ordner `/news/_posts/` anlegen mit dem Dateiname: `YYYY-MM-DD-url-pfad-der-angezeigt-werden-soll.md` (am besten eine bestehende Datei kopieren).
2. In der News-Datei im Header die Attribute `date:` und `image:` setzen. Das `image:` wird auf der Übersichtsseite aller Newsartikel angezeigt.
3. Bilder können innerhalb des Artikels fliessen links oder rechts dargestellt werden. HTML Code dafür:
  * Links: `<img class="float-left mr-20" src="/news/images/platzhalter.jpg" />`
  * Rechts: `<img class="float-right ml-20" src="/news/images/platzhalter.jpg" />`

## Entwicklungsumgebung installieren

* [Foundation](http://foundation.zurb.com/sites/docs/installation.html#command-line-tool.html) (npm install der Version `v1.0.4`)
* [Jekyll](http://jekyllrb.com/) (`v1.4.2`)

## run development

### build sass to css
`npm start`

### run jekyll server on port 4000
`jekyll serve -w`
