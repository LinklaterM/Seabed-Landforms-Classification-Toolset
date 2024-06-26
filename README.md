# Seabed Landforms Classification Toolset
 ArcGIS Toolbox to classify seabed landforms on continental and island shelves

The Seabed Landform Classification Toolset is a GIS toolbox designed to classify seabed landforms on continental and island shelf settings. The user is guided through a series of classification steps within an ArcGIS toolbox to classify prominent seabed features termed ‘seabed landforms’, which characterise the morphology of the seabed surface. Seabed landforms include reefs/banks, peaks, plains, scarps, channels and depressions. Plain areas can additionally be classified into high and low features at localised and broad scales to capture features within plain surfaces. Common variables for seabed classification are utilised, including slope, bathymetric position index and ruggedness, and a series of procedures are applied to identify reef outcrops and minimise noise. The classification approach applies a whole-seascape classification which is aimed to offer a flexible and user-friendly approach to extract key seabed features from high-resolution shelf bathymetry data.

This toolset was developed using ESRI ArcGIS Desktop 10.8 and requires an Advanced licence with Spatial Analyst and 3D Analyst extensions. It utilises scripts within the Benthic Terrain Modeler toolset (Walbridge et al. 2018) and Geomorphometry and Gradients Metrics Toolbox (Evans et al., 2014). 

Please read the User Guide and supporting documentation for information on how to run the toolset. A web explainer is available at: https://arcg.is/1Tqmv50

The Seabed Landform Classification Toolset is also available for download on the NSW Government SEED environmental data portal: https://datasets.seed.nsw.gov.au/dataset/seabed-landforms-classification-toolset

The toolset was developed by the Coastal and Marine Team, New South Wales Department of Climate Change, Energy, the Environment and Water, Australia. Funding was provided by New South Wales Climate Change Fund through the Coastal Management Funding Package and the Marine Estate Management Authority.

Please cite this toolset as:
Linklater, M, Morris, B.D. and Hanslow, D.J. (2023) Classification of seabed landforms on continental and island shelves. Frontiers of Marine Science, 10, https://doi.org/10.3389/fmars.2023.1258556.

Other toolsets utilised by the Seabed Landform Classification Toolset include:
Benthic Terrain Modeler: Walbridge, S., Slocum, N., Pobuda, M., and Wright, D. J. (2018). Unified geomorphological analysis workflows with Benthic Terrain Modeler. Geosciences 8, 94.
Geomorphometry and Gradients Metrics Toolbox: Evans, J., Oakleaf, J., and Cushman, S. (2014). An ArcGIS Toolbox for Surface Gradient and Geomorphometric Modeling, Version 2.0-0. https://github.com/jeffreyevans/GradientMetrics.

Update 28/04/2024 - Updated script 'NOISE_Elim.py' to replace 'LAND_2' field with 'PrelimLand' field. Previous version of 'NOISE_Elim.py' script eliminated 'Noise' polygons using 'LAND_2' field labels rather than 'PrelimLand' field labels which may have been edited by the user. Sample datasets also updated.  
Update 01/03/2014 - User Guide and Quick Reference Guide updated. No changes to toolbox.
Update 25/02/2024 - Updated "PrelimLandforms.lyr" symbology file. Colour scheme was previously applied to the "LAND_2" field. New update applies colour scheme to "Prelim_Land" field as this is the correct field for editing. Updated NSW Government department name from "NSW Department of Planning and Environment" to "NSW Department of Climate Change, Energy, the Environment and Water" to reflect department changes.
Update 25/11/2023 - Added citation of Linklater et al.(2023) to documentation
