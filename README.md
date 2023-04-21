# QGIS Plugin for OGC Web Coverage Service 2.X

Receive tiff files from OGC Web Coverage Services (v2.X) based on map view in QGIS. Created to access certain german official geodata, e.g. digital aerial photographs.

## Supports...
- WCS 2.X Core
- KVP Protocol-Binding
- CRS Extenstion
- Geo Tiff

### Api Keys
- Optionally, an api key can be added to the requests for services requiring authentication. The api key is set in the first page of the dialog and it is appended to the requests as a parameter called "api-key". If the key is empty the parameter is left out from the requests. TO DO: a user should have an option to change the name of the parameter in the dialog.
