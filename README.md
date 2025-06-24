# C.elegans
ImageJ Aggregate Analysis Column Descriptions

Aggr: This column contains the index number for each aggregate, automatically assigned by ImageJ. It is unitless.

Area: Represents the size of each aggregate in square micrometers (µm²), or in pixel² if a scale was not set.

Mean: The average pixel intensity (mean gray value) within the aggregate, expressed in arbitrary units (a.u.) of fluorescence intensity.

Min: The minimum pixel intensity value detected within the aggregate, in arbitrary units (a.u.).

Max: The maximum pixel intensity value detected within the aggregate, in arbitrary units (a.u.).

IntDen: The integrated density, calculated as Area × Mean gray value. This gives the total fluorescence intensity per aggregate, in a.u. × µm² (or a.u. × pixels if unscaled).

RawIntDen: The raw integrated density, representing the sum of all pixel intensity values within the aggregate (∑ of pixel values), reported in arbitrary units (a.u.) without scaling.

Total_worm_area: The total area of the worm from which the aggregate was measured. This value is repeated for each aggregate from the same worm and is used for normalization. Reported in µm².

Worm: A text label identifying the individual worm associated with each aggregate (e.g., "worm1").
