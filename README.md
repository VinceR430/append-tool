import arcpy
jpeg = arcpy.mp.JPEGDocumentOpen((r'D:\COMPCART\1_topology.jpeg'))
jpeg.appendpages(r'D:\COMPCART\2_MapPages.jpeg')
jpeg.saveandClose()
