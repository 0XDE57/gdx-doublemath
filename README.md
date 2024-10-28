# gdx-doublemath

libGDX's math api is built around floating point. This can lead to Triangulation errors with co-axial points.

This library provides higher precision double math utilities, in a libGDX compatable and API friendly way.
These extensions are just double versions of the existing built in float versions:

* DoubleArray (FloatArray)
* DoubleConvexHull (ConvexHull)
* DoubleDelaunayTriangulator (DalaunayTriangulator)
* DoubbleGeometryUtils (GeometryUtils)
* DoublePolygon (Polygon)
* DoubleShape2D (Shape2D)
