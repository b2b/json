Cytoscape.js uses an event-driven model with a core API.  The core has several extensions, each of which is notified of events by the core, as needed.  Extensions modify the elements in the graph and notify the core of any changes.

The client application accesses Cytoscape.js solely through the [core](#core).  Clients do not access extensions directly, apart from the case where a client wishes to write his own custom extension.

The following diagram summarises the extensions of Cytoscape.js, which are discussed in further detail [later in this documentation](#extensions).

![The architecture of Cytoscape.js](https://raw.github.com/cytoscape/cytoscape.js/master/ref/arch.png)