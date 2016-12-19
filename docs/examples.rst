Examples
========


Holland default
---------------

1D, surfbeat, random normal incident waves.Aim: Dune erosion

This test simulates dune erosion on the standard Holland profile (DUROS) under normative conditions. Simple exampe with minimal input.   

model data: https://svn.oss.deltares.nl/repos/xbeach/skillbed/input/holland_default/

Field experiment: DELILAH
-------------------------

2D, surfbeat, directional spreading. Aim: comparison field data hydrodynamics

In order to verify the 2DH hydrodynamics of XBeach when forced by directionally-spread
short waves, a simulation is set up to compare model results to field measurements. In this
case the DELILAH field experiment at Duck, North Carolina is selected as a suitable test
location. The period that is modeled is October 13th 1990, which was a stormy day, between
16:00 and 17:00 hours.
For more info, check: http://oss.deltares.nl/web/xbeach/skillbed

model data: https://svn.oss.deltares.nl/repos/xbeach/skillbed/input/Delilah_199010131000/

Longcrested Refraction
----------------------

2D, surfbeat, random long crested incident waves, hydrodynamics only. Aim: simulation of refraction

Longcrested waves are supported in XBeach by using a value s larger than 1,000. This test shows the numerical directional diffusion in the comparison of a few runs where the angle of wave incidence and the number of directional bins vary. The bathymetry is a linear sloping beach and no morphological change is computed in these runs.

model data: https://svn.oss.deltares.nl/repos/xbeach/skillbed/input/longcrested_refraction/

Hurricane Sandy
---------------

2D, surfbeat, nested in SWAN simulation. Aim: beach and dune erosion

This model setup is used as a tool to model the impact of Hurricane Sandy on the New Jersey coast. Hurricane Sandy caused wide-spread erosion of the coastal system as well as barrier island breaching at several spots. The model focusses on the area of Camp Osborne, Brick, NJ where a condominium resulted in 32% additional erosion in adjacent locations.

model data: https://github.com/openearth/xbeach-docs/tree/master/docs/tutorials/sandy/files/Model
tutorial: http://xbeach.readthedocs.io/en/latest/tutorials/sandy/index.html
