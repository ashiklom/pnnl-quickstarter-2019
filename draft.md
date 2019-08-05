*Proposal title*

Remote sensing simulation and surface property retrieval system

*Need*

/What is the important customer or market need? How did you discover the need? What is the pain point for customer or what would delight the customer?/

The ideal remote sensing instrument would observe the entire world, multiple times a day, at very fine spatial resolution, and with hundreds of small wavelength bands across a wide range of the electromagnetic spectrum.
However, the combination of technological limitations and budgetary concerns mean that remote sensing instrument and mission design necessarily involves trade-offs between these various criteria.
For example, NOAA's Deep Space Climate Observatory (DSCOVR) satellite provides imagery of the entire Earth as frequently as every hour, but because the orbit required to achieve this is so far from the Earth, the satellite's effective spatial resolution is relatively poor -- around 24 x 24 square kilometers [1].
Meanwhile, the much lower orbit of the NASA MODIS-Terra satellite allows it to achieve a spatial resolution as low as 250 x 250 square meters, but with only a daily revisit.
The NASA/USGS Landsat satellite has the same orbit as MODIS-Terra but a much narrower field of view, so its spatial resolution is even finer -- 30 x 30 square meters -- but the same location is only imaged every 16 days [2].

The relative importance of these instrument criteria varies depending on the research question.


[1]: https://epic.gsfc.nasa.gov/about/epic
[2]: https://landsat.gsfc.nasa.gov/landsat-data-continuity-mission/

*Approach*

/What is your approach for solving this need? How will your specific approach address what the customer cares about? What makes your approach compelling? Note that the first 150 characters of the approach field will appear in your "discover projects" list entry, so make them count!/

I will create a standardized protocol for simulating satellite observations associated with different land surface and atmospheric characteristics, and for retrieving these characteristics from real or simulated satellite observations.
Fundamentally, the remote sensing problem consists of the relationship between the following variables:
(1) At-sensor radiance (the actual satellite measurement);
(2) top-of-atmosphere reflectance;
(3) atmospheric composition and physical properties;
(4) surface reflectance; and
(5) surface characteristics.
This work will first define standard formats for all of these variables.

Fundamentally, this protocol divides the remote sensing problem into three distinct steps:
(1) Converting from surface characteristics (e.g. plant structure and biochemistry; snow moisture content; mineral composition) to surface reflectance (hemispherical and directional reflectance);
(2) converting from surface reflectance to top-of-atmosphere reflectance; and
(3) converting from top-of-atmosphere reflectance to remote sensing observations.


The protocol will define a small, standard set of formats for spectral data,

*Benefit*

/What are the benefits to the customer, the investor, the enterprise, or the partners? What does it cost them in terms of money, time, and conversion efforts to use your approach? What about the ecosystem: would it support or work against your solution?/

*Competition* (optional)

/Who are your competitors by name? How is your approach superior to their solutions to the customer’s needs? Remember that the customer always has the option of doing nothing. Demonstrate how your approach is compelling to those who might not want a solution./

*Success criteria*


*R&D Proposal DOE Mission Alignment Statement*
