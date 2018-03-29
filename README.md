# Cordova: photo,vibration and volume detection.

<h3> About the project: </h3>

With this application we make use of the camera of the mobile phone we use the vibration and detect when the user presses the volume up or down button.


<h3>Plugins:</h3>

The necessary plugins are:
<p>cordova plugin add add cordova-plugin-camera</p>
<p>cordova plugin add add cordova-plugin-vibration</p>


<h3>How to view it in your browser:</h3>

To view the application in the browser we must:
<p>1.launch the application in the desired emulator</p>
<p>2.go to browser >inspect>more tools>remote devices>select emulator>inspect 
with this we will see everything that happens in the application in our browser.</p>

<h3>Run it in the emulator:</h3>

To launch the application in the emulator we must launch the following commands:

<p> cordova platform add android</p>
<p>cordova build android</p>
<p>cordova emulate android</p>

If you want to use it in IOS change android for ios 

<h3>Install application on your mobile:</h3>
<p>cordova run android || cordova run ios</p>

<h3>Documentation:</h3>
<p><a href="http://cordova.apache.org/docs/en/7.x/reference/cordova-plugin-camera/index.html">Camera</a></p>
<p><a href="https://www.adictosaltrabajo.com/tutoriales/acceso-camara-phonegap/">Camera</a></p>
<p><a href="http://cordova.apache.org/docs/en/7.x/reference/cordova-plugin-vibration/index.html">Vibration</a></p>
<p><a href="https://cordova.apache.org/docs/en/1.5.0/phonegap/events/events.volumeupbutton.html">Volume</a></p>
