# Size-Invariant-Ship-Detection-from-SAR-Images

	1. Processing geo tiff files in python:

			- Read and write geo tiff files
		
	2. Remove Speckle noise using NDSAR filter.


	3. Generate Superpixels using fast-slic.


	4. Use K-means to cluster the superpixels.


	5. Identify and remove the land-superpixels.


	6. Use GSHHG data to remove the landmass overlooked by Superpixel-merging.


	7. Train VGG16 faster RCNN model for SHIP DETECTION.


	8. Return the count of Ships.


	9. Estimate Ship size using Haversine formula.


	10. Output a Vector file with:

			- Location(XY - Latitude and Longitude).
			- Ship Count.
			- Ship Size.

	11. Create a platform independent application for all the functional aspects to converge.
			
			-Currently looking into electron.js
