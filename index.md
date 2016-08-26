---
layout: default
---

## OsmSharp is a C# library to work with OpenStreetMap (OSM) data.

_If you are here for route planning, check [Itinero](http://www.itinero.tech/)!_

### What can I do with OsmSharp?

OsmSharp enables you to work directly with OSM-data in .NET. Most important features are:

- Read/Write OSM-XML.
- Read/Write OSM-PBF.
- Streamed architecture, minimal memory footprint.
- Convert a stream of native OSM objects to 'complete' OSM objects: Ways with all their actual nodes, Relations with all members instantiated.
- Convert OSM objects to geometries.

For more information visit the [repository on github](https://github.com/OsmSharp/core) or start reading the [documentation](https://github.com/OsmSharp/core/wiki) (yes, that's right there is documentation and even some [samples](https://github.com/OsmSharp/core/tree/develop/samples)!)

### Some history

OsmSharp used to do everything on top of what it does today, including routing and rendering geo data. This was too much and the name _OsmSharp_ didn't make sense anymore. Now the old functionality has been replaced by several seperate projects:

- [OsmSharp](https://github.com/OsmSharp/core): Working with OSM-data, filtering, transforming.
- [Itinero](http://www.itinero.tech/): The routing project is now maintained under the name **Itinero**.
- UI: This UI and rendering project has not been replaced. Instead we recommend using [Mapsui](https://github.com/pauldendulk/Mapsui).

### Contact

We can always help you with projects using OsmSharp, Itinero or Mapsui. Email ben - at - osmsharp.com for more information.
