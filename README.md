# FLOOD-MITIGATION-IN-MUKKAM
Through collecting SENTINEL-1 SARGRD(synthetic aperture radar ground range).Mapping of flood area by comparing images taken before and after a flood event 
Flood events cause heavy rainfall hence cloud cover would be a disturbance whencapturing optical images SAR images is not affected by weather and provides a robust
and reliable way to detect flooded regions.

![Flood kozhikode](https://user-images.githubusercontent.com/90825034/233173634-17258b17-502a-4d09-b948-4811916ccf10.png)
Region defined here is kozhikode which is taken as the region of intrest(geometry)

![b9ae1fea-6725-452e-b9c9-0905a7b4b9ea](https://user-images.githubusercontent.com/90825034/233174602-e8d3a01c-6af8-49bc-89dd-a4ad56a95eb6.jpg)

Flood distribution presence

BEFORE FLOOD

![3ca06e46-a034-471b-92bb-ae230e7eadc8](https://user-images.githubusercontent.com/90825034/233175834-4a584d7c-7145-407c-96b9-90beb027f514.jpg)

![b01914fe-ab2d-44ff-b98e-c5b737219639](https://user-images.githubusercontent.com/90825034/233175860-4b46a452-52ed-4cfd-8693-226b49772fee.jpg)


AFTER FLOOD

![e677b869-cbc0-453e-86ee-4430e3e261fa](https://user-images.githubusercontent.com/90825034/233175738-85312e9b-6142-48bd-b19b-6aaca2900816.jpg)

![292ac2d0-2683-4399-9a05-4401e9eb59ad](https://user-images.githubusercontent.com/90825034/233175766-956bd1e3-e7a8-4dcd-9a94-0cca50c58608.jpg)

![ELEVATION gps OF MUKKAM](https://user-images.githubusercontent.com/90825034/233176011-87611e32-08f9-41c0-93e1-669c3886b984.png)
Cloud points-elevation (Google Earth Pro)
![chennamanagallur -LAT,LOG](https://user-images.githubusercontent.com/90825034/233176243-8015012d-cca1-4d7a-986b-57bac353642d.png)
Detail attribute of cloud points (GPS Visualizer)[.txt]
![GPS- chennamangallor](https://user-images.githubusercontent.com/90825034/233176398-9fa02a53-2557-489e-b216-793234a92888.png)
 QGIS- Imported plaintext [LAT/LON] is read
![IDW interpolation-DEM(CHENNAMANGULLAR)](https://user-images.githubusercontent.com/90825034/233176679-d137a817-3c31-4b2d-b82e-0fb58b30b704.png)
IDW Interpolated DEM - IDW interpolation is a spatial Interpolation, when the value is determined from a location that do not have a specific value but have sample points nearby. Try to interpolate value from known point. Weightages specified frompoint which is nearto the unknown value being determined.
![Interpolated dsm profile tool (horizontal)png](https://user-images.githubusercontent.com/90825034/233176990-5bd0109a-19b4-44c7-96e9-f93a6ead8300.png)
.Profile of slope(%) from the DEM
![profile tool interpolated(vertical)](https://user-images.githubusercontent.com/90825034/233177027-41e65279-4848-4850-a0c7-ef1ffcc37153.png)
Profile ofslope(%) from the DEM[Tabular Format]
![20230131074455-96007-profile](https://user-images.githubusercontent.com/90825034/233177294-7678bcc2-4ec9-483a-b7d0-3b0c6c26b284.png)
Elevation profile [unit=metric]the elevation takes a specific amount of distance. From the given graph at a distance of 30-40km elevation is the highest.
![Marine-geo orgGMRT(chennamangallor-blender)](https://user-images.githubusercontent.com/90825034/233177427-0e080f7c-d96f-4472-9d3d-dbceb22cd633.png)
BLENDER-GIS-3D model(BLENDER-GIS) of a parcel area (chennamangallur OSM) help analyze the terrain and study the relief feature by Open-topography SRTM 90M


