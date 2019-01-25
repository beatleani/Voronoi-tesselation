# Voronoi-tesselation
This repository entails a code that generate digital microstructures by "Constructing a Periodic set of Voronoi vertices for implication of a periodic microstructure"

The algorithm is to first create a 2D RVE ( Representative Volume Element ). I then construct a set which implicitly contains periodic boundary conditions

All tesselations can be easily periodized by copying the point seed S around the unit cell as
illustrated in the report submitted. In this way, I cover all the points and the
virtual points thereby not having to implement explicit periodic boundary conditions.
