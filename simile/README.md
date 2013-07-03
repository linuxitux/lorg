### How to visualize detection results with SIMILE-widgets?

[SIMILE-Widgets](http://www.simile-widgets.org) are a great way for data visualization. LORG currently supports the *Exhibit* (filterable wordlmap) and *Timeline* widgets.

For an experimental **map view** of the results:

* use JSON output mode (`-o json`)
* if summerization enabled (default)
  * move output file to `./exhibit/summary/results.json`
  * open `./exhibit/summary/results.hmtl` in your favorite web browser
* else, if summerization disabled (`-n`)
  * move output file to `./exhibit/details/results.json`
  * open `./exhibit/details/results.hmtl` in your favorite web browser


For an experimental **timline view** of the results:

* use XML output mode (`-o xml`)
* move output file to `./timeline/results.xml`
* open `./timeline/results.hmtl` in your favorite web browser