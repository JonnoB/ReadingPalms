# ReadingPalms
Code for detecting change in land use and Identifying Conflict Palms

Land Classification The area class classifier was built using TIFF files from landsat 8, the area in the test is south Kalimantan, specifically the administrative regions of Seruyan and Kotawaringin Timur. The Tiff files are loaded into R along with shape files defining areas of Water, Cloud, Plantation and Forest, a multilevel XGboost model is then trained and tested, before being deployed to classify the entire map. The resulting classifier is then replotted as a map. Once done the map is compared with known plantations and conflict palm identified
