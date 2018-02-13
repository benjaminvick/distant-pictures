# distant-pictures
A simple server that serves webcam pictures to a website.

/*
3. Distant Pictures
The Distant Pictures lab is based on HelloYou, but has a web camera added. We make use of the 'node-webcam' from https://www.npmjs.com/package/node-webcam to add the camera functionality.

Fork the 'distant-picture' example project On your IxE, fork and git clone the distant-picture example project.
pi@ixeXX:~ $ git clone https://github.com/**_YourUserName_**/distant-pictures.git

In the distant-pictures directory, install the basic components for the node server by executing npm install

pi@ixeXX:~ $ cd distant-pictures
pi@ixeXX:~/distant-pictures $ npm install
up to date in 7.778s
We are using the helloYou Arduino circuit and code, so no adjustment is necessary on the Arduino side. Keep it plugged into the USB port of the Pi.
Plug in the web camera to another USB port of the Raspberry Pi.
Try pictureServer with node.js
pi@ixeXX:~/distant-pictures $ node pictureServer.js /dev/ttyUSB0
listening on *:8000
If everything is working, you should see a message in the terminal that the webserver is listening on port 8000.

Just like in the previous section, you can now go to the browser to control the Arduino and webcam.

To shut down the server, type control + C in the terminal.

ledOFF
ledON
^C
pi@ixeXX ~/distant-pictures $
What changed
Compare helloYou/server.js and distant-pictures/pictureServer.js. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called diff that compares files.)

Peephole
Now, edit the pictureServer.js code for a Peephole device. When a person presses the doorbell (here, the button on your Arduino), the application should snap a photo of the person in front of the doorbell, and post it to a remote webpage.

Please submit the code for the Peephole as part of your turn-in.

4. Make it your own
Now, extend the functionality of this basic setup.

Your own distributed camera app
As in the previous lab, modify the template for the lab to make it your own. You can do this just through text, better html and reframing the point of view, or you can incorporate technical improvements from the next part of the assignment...

Try a new node library/package
Find, install, and try out a node-based library and try to incorporate into your lab.

Document your successes and failures (totally okay!) for your Slack lab#2 turn-in. This will help the class community figure out cool new tools and capabilities. A good source for possible library ideas is your assignment #2.

Here is an example of how to try this. Following the directions on the https://www.npmjs.com/package/nyan-cat package, for example:

pi@ixeXX:~/test $ sudo npm install -g nyancat
Some ideas, in case you are stuck:

On Linux, node-webcam uses fswebcam. https://www.npmjs.com/package/node-webcam shows other commands available using node-webcam, and typing man fswebcam describes a variety of image capture options. Try out some modifications, and show us the screen capture of the resulting webpage.

Another package to try: gm. GM is GraphicsMagick and ImageMagick for node. https://www.npmjs.com/package/gm

5. Submit the lab
Upload a video of your version of the camera lab to your personal Slack channel and cross post to #lab2. **Make sure you've included the TAs: David Goedicke and Andrea Cuadra
Include a link to your forked code for the camera lab
Include brief description of what you did and why
Also, if it was separate from your lab project, post a summary of your npm experiment and post to #lab2
*/
