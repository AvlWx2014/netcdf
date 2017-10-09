Wraps many of the netcdf4-python API calls needed to write netCDF files in to
one single class with what I think are easy to use methods. Of course, there's
a limit to how much repetition I can remove from the process of writing netCDF
files with my class. But I've at least tried to consolidate some of the functionality.

CF-1.7_ conventions are used by default for latitude and longitude variables and I plan
to further incorporate CF conventions for building netCDF files for climate and weather
data as I expand functionality.

.. _CF-1.7: http://cfconventions.org/Data/cf-conventions/cf-conventions-1.7/cf-conventions.html

