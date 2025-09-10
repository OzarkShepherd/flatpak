# Gramps Flatpak
These are the manifest and data files required to make a Gramps Flatpak

The flatpak is available on flathub at https://flathub.org/apps/details/org.gramps_project.Gramps
The Gramps flatpak contains dependencies and works with flathub runtimes to work independently regardless of the linux distribution.

# List of Included Dependencies
Dependencies confirmed in the flatpak platform and required for Gramps:
- python3
- gtk
- pygobject
- cairo
- pango
- pangocairo

Dependencies added to the flatpak
- orjson (required for Gramps)
- osmgpsmap with its libsoup dependency (for maps)
- graphviz and pygraphviz (for some chart addons)
- PyICU (for localizations)
- ghostscript (for an addon that creates pdf files)
- gspell (for spellcheck)
- pillow (for images)
- exiv2 and gexiv2 (for "Edit Image Exif Metadata" addon)
- geocodeglib (for copy/paste of gps points in maps)
- goocanvas (for "GraphView" addon)
- networkx (for network chart addon)
- libsecret (for the "Gramps Web Sync" Addon)

To request another prerequisite be added to support another Gramps add-on, you can request it at the gramps project flatpak github or at the flathub Gramps flatpak github.

https://github.com/gramps-project/flatpak

https://github.com/flathub/org.gramps_project.Gramps

Also, the old version of Berkeley Database (BSDDB) that was included with the Gramps 5.0 and 5.1 flatpaks will be dropped for 5.2.

Please make regular full backups of your important genealogy files, and include any attached media files for your genealogy in your backups for your convenience.
