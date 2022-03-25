## Bicycle preset with large images

This is the standard bicycle preset from [Beautified JOSM Preset](https://github.com/simonpoole/beautified-JOSM-preset) 
enhanced with large images for type selection in [Vespucci](https://vespucci.io/).

The current images are from the [City of Zürichs bicycle infrastructure map](https://www.stadtplan.stadt-zuerich.ch/zueriplan3/stadtplan.aspx#route_visible=true&basemap=Basiskarte+(Geb%C3%A4udeschr%C3%A4gansicht&map=Mit+dem+Velo+durch+Z%C3%BCrich)

Building the preset files is done with gradle and should work on both unixy operations systems and windows, the "generateAllPresetTypes" task will generate the variants in the `gen` directory.

Building requires `xmlstarlet` installed and on your path, generating the icons from SVG requires `rsvg-convert`to be installed.

Please follow us on [twitter](https://twitter.com/search?q=vespucci_editor) for updates.
