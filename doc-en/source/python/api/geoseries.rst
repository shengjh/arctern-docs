
.. _geoseries:

GeoSeries
=========
.. currentmodule:: arctern

GeoSeries is a Series to store and process geometry data by extending
Pandas Series. It internally store geometry as bytes object.

Constructor
-----------
.. autosummary::
   :toctree: geoseries/
   :template: autosummaryclass.rst

   GeoSeries


Attributes
----------
.. autosummary::
   :toctree: geoseries/

   GeoSeries.is_valid
   GeoSeries.length
   GeoSeries.is_simple
   GeoSeries.area
   GeoSeries.geometry_type
   GeoSeries.centroid
   GeoSeries.convex_hull
   GeoSeries.npoints
   GeoSeries.envelope

Processing Geometry
-------------------
.. autosummary::
   :toctree: geoseries/

   GeoSeries.buffer
   GeoSeries.precision_reduce
   GeoSeries.intersection
   GeoSeries.make_valid
   GeoSeries.simplify_preserve_topology
   GeoSeries.to_crs
   GeoSeries.curve_to_line

Spatial Relationship
--------------------
.. autosummary::
   :toctree: geoseries/

   GeoSeries.geom_equals
   GeoSeries.touches
   GeoSeries.overlaps
   GeoSeries.crosses
   GeoSeries.contains
   GeoSeries.intersects
   GeoSeries.within

Measurement
-----------
.. autosummary::
   :toctree: geoseries/

   GeoSeries.distance_sphere
   GeoSeries.distance
   GeoSeries.hausdorff_distance

Aggregation
-----------
.. autosummary::
   :toctree: geoseries/

   GeoSeries.union_aggr
   GeoSeries.envelope_aggr

