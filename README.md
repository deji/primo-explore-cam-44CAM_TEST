************************************************************************************************************************

                                    Primo Configuration Package  - Guide

************************************************************************************************************************


The Configuration package is compiled of the following folders:

1. img
   in this folder you can place your localized images for:
	1. The library log - file name should be : library-logo.png
	2. The library favicon - file name should be : favicon.ico
	3. The library customized resource type icons naming convention is:
	     icon_{resource_type}.png
		 for example:
					icon_audio.png
2. css/js: files are automatically generated when you run `gulp run --view 44CAM_TEST`. 
	1. The source files should have been installed with `npm install`. These are npm packages defined in package.json.
