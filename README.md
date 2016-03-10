# focus-log-loading_geofence

The purpose of this web service is to determine, if a forest truck is unloading tree logs. Therefore it is checked, if the "loading event" (based on the SensorAppIII vibration indicator) is taking place in predefined geographical area (e.g log area saw mill). 

## How to setup the  web service

**Requirements:**
* Apache Tomcat 8 as web server
* JDK 1.8 
* Latest Eclipse IDE
*

**Get the pre-exported version:**

1. Download the `focusgeofence.war` file from https://github.com/ispaceappengine/focus-log-loading_geofence/tree/master/build
2. Deploy the war file to your Tomcat 8 web server.
3. Access the web service: ..yourDomain.org/**focusgeofence**
4. You should see something like the following
![](http://i.imgur.com/3PRY8o0.png)


**Export your own focusgeofence.war file:**

**1.** Download/pull the code.

**2.** Import project into Eclipse IDE

**3.** Rightclick the project > Export > WAR file > Provide save destination > Finish.

**4.** Deploy the war file to your Tomcat 8 web server.

**5.** Access the web service: ..yourDomain.org/**focusgeofence**


![](http://raw.github.com/wiki/openhab/openhab/images/features.png)

asdfasdfadfasdf
---------------
http://i.imgur.com/qpY0nVd.jpg


Author: Simo Lukic
Contact: office.ispace@researchstudio.at
www.researchstudio.at

The MIT License (MIT)

Copyright (C) 2016 by Studio iSPACE, Researchstudios Austria Forschungsgesellschaft mbH. 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
