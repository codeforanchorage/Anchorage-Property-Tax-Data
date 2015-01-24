# Anchorage-Property-Tax-Data
Compressed files for Anchorage property taxes. 

The muni provides tax assessment data for properties in the muni area every year. Initial assessments just went out for 2015
and home owners are allowed to review and appeal the assesment. 

You can look up the property tax data for any address through this interface: http://www.muni.org/pw/public.html
and the information is publicly available.

We have bulk download data from 2008-2014. There is interesting data included like number of bedrooms, type of heating,
 when the house was constructed and current assessed value. Since there are multiple years we could also see how value and 
 housing configuration changed over time. It would be helpful to geocode the values or map to the Muni parcel
  shapefile via the parcel number.
  
  The data is recorded in fixed length fields of 1200+ characters and the second half of the fields are defined differently 
  depending if the property is commercial or residential.
  
  An initial approach might be to write ETL or code similar to the trails-transcoder to turn the fields into CSV and clean up 
  the data. So that it would be easy to add 2015 data and have it easily converted. 
  
  Possilbe applications would be to show the properties on a map, analyze what areas of Anchorage have had property increases, 
  energy efficiency estimates based on housing stock, mapping parcel information from other open data, visualization of when 
  properties were built. 
