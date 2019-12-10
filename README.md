# linguistic-atlas
This project uses data from the Linguistic Atlas Project (LAP), which as of July 2018 is housed at UK. This data represents the largest systematically carried out survey of US dialects to date. There are hand-drawn maps from the first regional survey, LANE, from the 1930s that represent how people answered the questions asked. This data 'belongs' to the LAP, which is happy to make the data publically available.

Steps taken to create project static map:
  1) scan LANE papr map at high resolution, upload and georeference that map in QGIS
  2) clean up LANE spreadsheet data (normalize for capitalilzation, typos, etc.)
  3) add LANE data as point layer

Steps taken to create project interactive map:
  1) upload dataset into Carto
  2) create legend, popup boxes
  
This project is my attempt to marry the old and the new, to intersect legacy (or 'heritage') data with contemporary mapping techniques. Making mid-century modern, one step at a time. =)
