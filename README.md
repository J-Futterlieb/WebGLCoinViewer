# WebGLCoinViewer

![Alt text](/Preview.png?raw=true "Preview")

WebGL-based visualization of digitized coins. The light direction can be interactively modified
to explore the unique features of a coin (text, marks, ...).

## License
See LICENSE file for license information.

## SingleViewerFileSample
The folder "SingleViewerFileSample" contains the web application in a single file, where
the documented javascript code for the viewer and the image data of the coin is embedded into the file.
The image data is stored in the variable "embeddedCoinData" as json format, the object "albedo" and
"normal" contains the image data as Base64-encoded png file. The html file can easily be opened by a
webbrowser to start the web application.

## ViewerWithExternalDataSample
The folder "ViewerWithExternalDataSample" contains the web application with separate javascript code
for the viewer (coin.js) and the image data (coinData.json). The html file demonstrates the simple
integration into an existing website.
Note for opening the html file from a local filesystem with a browser: Due to 
CORS (Cross-Origin Resource Sharing) this web application may not start with your browser settings. Search
the web for alternative solutions.

## Browser support
The web applications were tested successfully with Chrome 89.0.4389.82, Firefox 78.8.0 and Edge 89.0.774.45.

