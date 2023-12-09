# Project
Select a dataset for your project that you and your group find interesting. 
The dataset should be large enough in scope to ensure that you will be able to create several charts. It is suggested to have some geospatial component to your data so that you can include a map in your final presentation/report. Including a temporal element will allow you to show changes over time, which would also be a good idea. Prior approval of your selected dataset is required. Emphasis should be paced on “good” data visualization and you should allow the data to tell the Story.  Your Story should make use of the Pre-attentive Visual Properties including: Colour, Form, Motion and Spatial Positioning

Using Python
This repo contains the datawrangling, datacleaning, to_csv and visualizations

using the significant earthquakes dataset from kaggle
https://www.kaggle.com/datasets/warcoder/earthquake-dataset](https://www.kaggle.com/datasets/usamabuttar/significant-earthquakes/

Here's an explanation of each column in the USGS earthquake data:

time: The time of the earthquake, reported as the number of milliseconds since the Unix epoch (January 1, 1970, 00:00:00 UTC).
latitude: The latitude of the earthquake's epicenter, reported in decimal degrees.
longitude: The longitude of the earthquake's epicenter, reported in decimal degrees.
depth: The depth of the earthquake, reported in kilometers.
mag: The magnitude of the earthquake, reported on various magnitude scales (see magType column below).
magType: The magnitude type used to report the earthquake magnitude (e.g. "mb", "ml", "mw").
nst: The total number of seismic stations used to calculate the earthquake location and magnitude.
gap: The largest azimuthal gap between azimuthally adjacent stations (in degrees).
dmin: The distance to the nearest station in degrees.
rms: The root-mean-square of the residuals of the earthquake's hypocenter location.
net: The ID of the seismic network used to locate the earthquake.
id: A unique identifier for the earthquake event.
updated: The time when the earthquake event was most recently updated in the catalog, reported as the number of milliseconds since the Unix epoch.
place: A human-readable description of the earthquake's location.
type: The type of seismic event (e.g. "earthquake", "quarry blast", "explosion").
horizontalError: The horizontal error, in kilometers, of the location reported in the latitude and longitude columns.
depthError: The depth error, in kilometers, of the depth column.
magError: The estimated standard error of the reported earthquake magnitude.
magNst: The number of seismic stations used to calculate the earthquake magnitude.
status: The status of the earthquake event in the USGS earthquake catalog (e.g. "reviewed", "automatic").
locationSource: The ID of the agency or network that provided the earthquake location.
magSource: The ID of the agency or network that provided the earthquake magnitude.

kaggle datasets download -d usamabuttar/significant-earthquakes <<--- included as a commented out cell 
