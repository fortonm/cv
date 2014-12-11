Setup
-----

Checkout from git

Go to src directory

<pre>npm install -g grunt-cli</pre>
<pre>npm install -g bower</pre>
<pre>npm install</pre>
<pre>bower install</pre>


Start local Development server
------------------------------

<pre>grunt serve</pre>

Local version is available at http://localhost:9000/
All changes are automaticly deployed to your local server (javascript changes may need page refresh)

Build a Production version
--------------------------

<pre>grunt build</pre>

Result is available in dist folder

Deploy production distribution to Github Pages
----------------------------------------------

<pre>grunt buildcontrol:pages</pre>

You can check result on http://fortonm.github.io/cv/
