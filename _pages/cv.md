---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Geographic Information Science Certificate, Gainesville State College, 2009
* B.S. Applied Environmental Spatial Analysis, Gainesville State College, 2010
* M.S. Forest Resources, University of Georgia, 2013

Software Skills
======
R, Python, Linux, Bash, SQL, Git, Redmine, Agile, ArcGIS, QGIS, Docker, Nginx

Professional Experience
======
* Water Resource Engineer (Software Engineer), Lynker Technologies, National Water Center, June 2019-Present
  * Develop NOAA’s National Flood Inundation Mapping (FIM) model (<a href="https://github.com/NOAA-OWP/cahaba" target="_blank" rel="noopener"><span style="color:blue">cahaba repo</span></a>)
  * Collaborate in a distributed team environment using Github and Agile software development practices
  * Optimize and scale open-source geospatial model pipelines on Linux - Python/Docker
  * Develop custom solutions, tools, and workflows to debug, test, and evaluate predictive models
  * Collaborate with external development teams
  * Libraries: GDAL/OGR, Pandas/Geopandas, Rasterio, SQLite, Multiprocessing, Arcpy, Numpy


* Hydrologist (Software Developer), ORISE Fellowship - U.S. Environmental Protection Agency, Office of Research and Development, October 2016-June 2019
  * Researched nanomaterial fate and transport in various aquatic ecosystems (see publications)
  * Contributed to the development of Water-quality Analysis Simulation Program (WASP), version 8, Advanced Toxicant module including testing, verification of algorithms, technical guides and user’s manual, training workshops, and multiple peer-reviewed research papers
  * Performed model sensitivity analysis and calibration of fate and transport models
  * Developed hydrologic flow routing algorithms in Python for <a href="https://github.com/quanted/hms" target="_blank" rel="noopener"><span style="color:blue">Hydrologic Micro Services (HMS)</span></a>
  * Developed an R Shiny web <a href="https://github.com/quanted/wq_screen" target="_blank" rel="noopener"><span style="color:blue">application</span></a> to screen water quality samples using criteria based on their location  


* Hydrologist, U.S. Environmental Protection Agency, Office of Research and Development, February 2015-September 2016
  * Tested source code of fate and transport model and verified parameter algorithms
  * Built pipelines to acquire model input data from APIs and convert to organized data structures (R)
  * Modeled fate and transport of sediments, metals, and emerging contaminants
  * Developed open-source pipelines for extracting, evaluating, and visualizing model results (R)


* Mudlogger, Morco Geological Services Inc., November 2013-December 2014
  * Collected and logged lithology samples for formation mapping and hydrocarbon analysis 
  * Analyzed chromatographs and logging/drilling software
  * Prepared technical reports and corresponded with operations geologists


* Independent Contractor, Headwater Science, LLC, August-September 2013
  * Stream habitat assessments; macroinvertebrate identification and analysis
  * Electrofishing and seine net sampling
  
  
* Graduate Research Assistant, Dept. Forestry and Natural Resources & Savannah River National Lab (U.S. Dept. of Energy), University of Georgia, 2010-2013
  * Developed methods for streamflow prediction in ungauged basins using parameter information from calibrated gauged basins with Hydrologic Simulation Program FORTRAN (HSPF)
  * Estimated data and model uncertainty using parameter estimation (PEST) software
  * Applied statistical metrics to quantify streamflow and watershed characteristic similarities
  
  
* GIS Specialist, U.S. Forest Service, University of Georgia, 2012 
  * Created GIS layers, maps, and technical reports following EPA’s DRASTIC protocol 
  * Developed and organized the Ground Water Vulnerability and Risk Assessment for U.S. Forest Service Southern Region lands
  * Collaborated with a team to produce GIS products, procedure manuals, and reports
  
  
* Research Assistant, Institute for Environmental and Spatial Analysis & Georgia Power, Gainesville State College, 2009-2010
  * Assisted in developing and decision support system (DSS) website using HTML and ArcGIS
  * Created GIS layers displaying watershed descriptions and water quality data in an interactive framework
  
  
* Senior Project, Institute for Environmental and Spatial Analysis, Gainesville State College, 2009-2010
  * Developed a land use map of Rocky Creek, GA to identify stream banks lacking riparian buffers
  * Produced a canopy height model from LIDAR data to classify land use with object-based image analysis

Awards
======
* EPA Gold Medal for Scientific Excellence (Gold King Mine Report) - 2017
* EPA Scientific and Technological Achievement Award Nominee - 2021 (Pending Results) 

Journal Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Reports and Proceedings Papers
======
* Sitterson, J., C.D. Knightes, B. Avant. (2018). Flow Routing Techniques for Environmental Modeling. U.S. Environmental Protection Agency, Washington, DC, <a href="https://cfpub.epa.gov/si/si_public_record_Report.cfm?dirEntryId=342907&Lab=NERL" target="_blank" rel="noopener"><span style="color:blue">EPA/600/B-18/256</span></a>. <a href="https://cfpub.epa.gov/si/si_public_file_download.cfm?p_download_id=537222&Lab=NERL"><img src="/images/pdf.jpg" style="width: 20px; height: 20px; margin-left: 1px;">
* Sitterson, J., C.D. Knightes, R. Parmar, K. Wolfe, M. Muche, B. Avant. (2017). An Overview of Rainfall-Runoff Model Types. U.S. Environmental Protection Agency, Washington, DC, <a href="https://cfpub.epa.gov/si/si_public_record_report.cfm?dirEntryId=339328&Lab=NERL" target="_blank" rel="noopener"><span style="color:blue">EPA/600/R-17/482</span></a>. <a href="https://cfpub.epa.gov/si/si_public_file_download.cfm?p_download_id=533906&Lab=NERL"><img src="/images/pdf.jpg" style="width: 20px; height: 20px; margin-left: 1px;">
* Sitterson, J., C.D. Knightes, R. Parmar, K. Wolfe, B. Avant, A. Ignatius, D. Smith. (2017). A Survey of Precipitation Data for Environmental Modeling. U.S. Environmental Protection Agency, Washington, DC, <a href="https://cfpub.epa.gov/si/si_public_record_report.cfm?Lab=NERL&dirEntryId=339606" target="_blank" rel="noopener"><span style="color:blue">EPA/600/R-17/441</span></a>. <a href="https://cfpub.epa.gov/si/si_public_file_download.cfm?p_download_id=534513&Lab=NERL"><img src="/images/pdf.jpg" style="width: 20px; height: 20px; margin-left: 1px;">
* Ambrose, B., B. Avant, Y. Han, C.D. Knightes, T. Wool. (2017). Water Quality Assessment Simulation Program (WASP8): Upgrades to the Advanced Toxicant Module for Simulating Dissolved Chemicals, Nanomaterials, and Solids. U.S. Environmental Protection Agency, Washington, DC, <a href="https://cfpub.epa.gov/si/si_public_record_report.cfm?Lab=NERL&dirEntryId=338180" target="_blank" rel="noopener"><span style="color:blue">EPA/600/R-17/326</span></a>. <a href="https://cfpub.epa.gov/si/si_public_file_download.cfm?p_download_id=535418&Lab=NERL"><img src="/images/pdf.jpg" style="width: 20px; height: 20px; margin-left: 1px;">
* Avant, B., Knightes, C., Bouchard, D., Chang, X., Henderson, M., Zepp, R. (2017). Modeling Engineered Nanomaterials (ENMs) Fate and Transport in Aquatic Ecosystems. <a href="http://gwri.gatech.edu/GWRC2017" target="_blank" rel="noopener"><span style="color:blue">Proceedings of the 2017 Georgia Water Resources Conference</span></a>. Athens, GA, April. <a href="http://gwri.gatech.edu/sites/default/files/files/docs/2017/avantknightesbouchardchanghendersonzeppgwrc2017.pdf"><img src="/images/pdf.jpg" style="width: 20px; height: 20px; margin-left: 1px;">
* US EPA. (2017). Analysis of the Transport and Fate of Metals Released from the Gold King Mine in the Animas and San Juan Rivers. Office of Research and Development. Athens, GA. <a href="https://cfpub.epa.gov/si/si_public_record_report.cfm?Lab=NERL&dirEntryID=325950" target="_blank" rel="noopener"><span style="color:blue">EPA Report</span></a>. <a href="https://cfpub.epa.gov/si/si_public_file_download.cfm?p_download_id=530074&Lab=NERL"><img src="/images/pdf.jpg" style="width: 20px; height: 20px; margin-left: 1px;">
* Avant, B., (2013). Comparison of Input Precipitation Sources in Streamflow Forecasting. Master’s Thesis. Daniel B. Warnell School of Forestry and Natural Resources. University of Georgia, United States. <a href="https://getd.libs.uga.edu/pdfs/avant_brian_k_201312_ms.pdf"><img src="/images/pdf.jpg" style="width: 20px; height: 20px; margin-left: 1px;">
* Avant, B., A. Ignatius, T. Rasmussen, A. Grundstein, T. Mote, J. Shepherd. (2011). Coupling Tritium Release Data with Remotely Sensed Precipitation Data to Assess Model Uncertainties. <a href="http://hdl.handle.net/1853/46461" target="_blank" rel="noopener"><span style="color:blue">Proceedings of the 2011 Georgia Water Resources Conference</span></a>. Athens, GA, April. <a href="https://smartech.gatech.edu/bitstream/handle/1853/46461/Poster7.01121Avant.pdf?sequence=1&isAllowed=y"><img src="/images/pdf.jpg" style="width: 20px; height: 20px; margin-left: 1px;">
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

