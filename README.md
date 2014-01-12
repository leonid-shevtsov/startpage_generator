# Startpage generator

This script is meant to generate a browser startpage that contains several lists of several sites, that are displayed with favicons.

## sites.yml

The script needs a sites.yml file looking like:

    ---
    -
      title: First category
      links:
        "Google": http://google.com
        "Reddit": http://reddit.com

    -
      title: Must visit
      links:
        "Leonid Shevtsov": http://leonid.shevtsov.me

The icons are automatically retrieved from Google and cached

## Requirements

* [pngcrush](http://pmt.sourceforge.net/pngcrush/)
* [wget](http://www.gnu.org/s/wget/)