The goal is to create a STAC catalog/endpoint of (accessible) STAC endpoints/catalogs, in such a fashion that ideally queries can be pushed through to identify all relevant datasets within the whole aggregated collection.
A good starting point is the community work on STAC extensions

https://github.com/stac-api-extensions/stac-api-extensions.github.io[https://github.com/stac-api-extensions/stac-api-extensions.github.io]

and specifically

https://github.com/StacLabs/multi-tenant-catalogs[https://github.com/StacLabs/multi-tenant-catalogs]


in terms of visualization and hosting it also make sense to look at the CLOUD-NES repo[https://github.com/CLOUD-NES/ahn-stac] forinfrastructure solutions

Update 05-10
There seems to be additional existing work in this direction. Specifically

https://github.com/Spatialnode/superstac[https://github.com/Spatialnode/superstac]

and the accompanying blog post

https://www.spatialnode.net/articles/introducing-superstac-many-catalogs-one-search2a5e11[https://www.spatialnode.net/articles/introducing-superstac-many-catalogs-one-search2a5e11]

and references therein.

In particular 
https://github.com/developmentseed/stac-fastapi-collection-discovery[https://github.com/developmentseed/stac-fastapi-collection-discovery]
and 
https://github.com/developmentseed/stac-collection-discovery[https://github.com/developmentseed/stac-collection-discovery]

also provide a library and accompanying web app for collection discovery. NOTE: this stops at the collection level and does not extend to assets.
