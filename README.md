GDAL - Geospatial Data Abstraction Library
====

GDAL is an open source X/MIT licensed translator library for raster and vector geospatial data formats. This is a mirror of the GDAL Subversion repository.

* Main site: http://www.gdal.org - Developer and user docs, links to other resources
* SVN repository: http://svn.osgeo.org/gdal
* Download: ftp://ftp.remotesensing.org/gdal, http://download.osgeo.org/gdal
* Wiki: http://trac.osgeo.org/gdal - Bug tracking, various user and developer contributed documentation and hints
* Mailing list: http://lists.osgeo.org/mailman/listinfo/gdal-dev

GDAL 1.11.x modifications for Visual Studio 2015
====
GDAL 1.11.x does not compile under Visual Studio 2015 out of the box. 
This fork includes changes to fix that, namely:

 * Disabling of a conflicting preprocessor macro (`snprintf`).
 * Inclusion of `legacy_stdio_definitions.lib` for ODBC support.
