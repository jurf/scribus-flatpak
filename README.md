> NB: This package is **unmaintained**. You can now find Scribus on [Flathub](https://flathub.org/apps/details/net.scribus.Scribus).

# Scribus Flatpak

[![pipeline status](https://gitlab.com/jurf/scribus-flatpak-repo/badges/master/pipeline.svg)](https://gitlab.com/jurf/scribus-flatpak-repo/commits/master)

This repository hosts unofficial Flatpak manifests for Scribus. A development
and a nightly version is available, with the latter being available pre-built.
You can find the list of known issues [here][0]. Testing and contributions
welcome!

## Installation

You will need Flatpak [installed][1].

You can install the nightly version of Scribus either by clicking on [this link][2],
or using the command line:

    # Install the nightly version
    flatpak install http://drjurf.tk/scribus-flatpak/scribus-nightly.flatpakref

(The development version is no longer available pre-built, it was too
resource-heavy to maintain both versions, but you can still build it yourself.)

You can find the source code on [GitHub][3].

[0]: https://github.com/jurf/scribus-flatpak/issues
[1]: http://flatpak.org/getting.html
[2]: http://drjurf.tk/scribus-flatpak/scribus-nightly.flatpakref
[3]: https://github.com/jurf/scribus-flatpak
