Inventory Protocol for URI Street Trees

1. Identify start and end dates for mobile data collection sprint
1. Backup existing tree database
	1. If you do not have the github repository installed on your computer, follow protocol 'Installing URI Street Trees respository'
	1. Visit the ArcGIS Online page for the feature service backing the shared mobile map
		1. TODO: add link!
	1. Use Export menu to download layer from ArcGIS Online as FGDB (File Geodatabase)
	1. Verify an uncorrupted download
		1. Unzip URI_Street_Trees.zip
		1. Load URI_Street_Trees.gdb into ArcGIS or QGIS
		1. You should see many points load on the map
	1. QA Data
		1. TODO: Describe spot checks of new/updated datapoints
	1. Commit the updated zip file to remote version tracking
		1. Overwrite URI_Street_Trees.zip in URI Street Trees github repository directory on your computer
		1. Open GitHub for mac
			1. Windows protocol can also be provided
		1. Make sure you are in the 'uri-street-trees' repository (left side of screen)
		1. Enter Summary and Description (center bottom), use appropriately descriptive text.  File is auto-timestamped
		1. Click 'Commit to Master' (center bottom)
		1. Click Sync (upper right corner)
	1. Your file is now backed up, return to ArcGIS Online
1. Navigate to the map layer(s) you will be sharing for edit capability
	1. Note that map layers are not the same as feature service layers
	1. Current map layers for URI Street Trees are
		1.  TODO: link
		1.	TODO: link
1. Enable group permissions of your choice to allow access as needed
1. Mobile data collection may now begin
1. Mobile data collection is complete on the end date
1. Modify group permissions to limit access if needed 
1. Backup tree database to git, with appropriate descriptive text
	1. As Above
1. Copy Zip File into server archival locations
	1. TODO: Server location provided by Collean
1. Load Street Trees layer into Yale ArcGIS Server (TODO: May Be Optional)
	1. NOTE: this process creates feature layers for each collection period, may be unnecessary.
	1. TODO: define 
	1. Connect to server using Microsoft Remote Desktop
	1. Load file to remote Desktop using shared folder
		1. TODO: configuration instructioins
	1. Open ArcCatalog
	1. Open Current Database Connection
	1. Input feature class: click folder icon (browse), select the gdb file you sent to the remote desktop, select 'trees' feature layer
	1. Output feature class: uri_trees_{month - alphabetic}_{day}_{year 4 digit}
	1. Click OK
	1. When processing completes, the feature layer is now stored in ArcGIS Server




