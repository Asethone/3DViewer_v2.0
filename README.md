<h1>DOCUMENTATION 3D_VIEWER</h1>

<p align="center">
    <img width="300" src="misc/images/logo.png">
</p>

<h2>LET'S GO!</h2>
<p>3D_VIEWER - is an application that allows you to view 3D vireframe models in parallel and central projection.
</p>
<h4>BASIC APP FUNCTIONS:</h4>
<ul>
    <li>Window for selecting the name of the .obj file</li>
    <li>Object translate by Ox, Oy, Oz</li>
    <li>Object rotation by Ox, Oy, Oz</li>
    <li>Object approximation by Ox, Oy, Oz</li>
    <li>Model information: number of points and edges</li>
    <li>Editor settings</li>
    <li>Take a screenshot</li>
    <li>Make a GIF</li>
</ul>
<h4>EXAMPLE MODEL:</h4>
<img class="midleImage" src="misc/images/dragon.gif">
<h5>Dragon.obj</h5>
<h4>HOW TO USE:</h4>
<ul>
    <li>To choose a model, you need to add or select it</li>
    <li>For the model to appear on the screen, press the "CHOOSE FILE" button</li>
    <li>To move, rotate and scale the model, you need to enter a value in the box and click on the
        "TRANSLATE", "ROTATE", "SCALE" buttons
    </li>
    <li>To move, rotate and scale the model, you need to move the slider to the desired distance</li>
    <li>To change the settings, you need to click on the button "SETTING"</li>
</ul>
<h4>RECOMENDATION:</h4>
<ul>
    <li>There may be problems with rotation in a circle in the axis, due to the fact that all transformations are
        carried out with matrices.</li>
    <li>Don't use large files. Up to 3 Mb.</li>
    <li>Set correct moving, rotate, and scale values. Example: "10-90-10".</li>
</ul>
<h3>LET'S TALK ABOUT SETTING</h3>
<p>Setting - This is a feature of the editor that allows you to customize it.</p>
<img class="smallImage" src="misc/images/setting.png">
<h4>BASIC SETTING:</h4>
<ul>
    <li>Selecting edge color</li>
    <li>Selecting edge thickness</li>
    <li>Selecting edge type: dotted or solid</li>
    <li>Selecting vertices color</li>
    <li>Selecting vertices size</li>
    <li>Selecting vertices shape</li>
    <li>Selecting projection type: central or parallel</li>
    <li>Selecting background color</li>
    <li>Selecting calculate type models: GPU or CPU</li>
    <li>Choose button RESET TO DEFAULT will return the original settings</li>
    <li>Choose button CANCEL will cansel choose setting</li>
    <li>Choose button APPLY will apply choose setting</li>
</ul>
<h4>TYPES OF PROJECTION:</h4>
<ul>
    <li>"The Parallel projection" - the type of projection that uses parallel projecting rays</li>
    <li>"The Central projection" - of a point is the point of intersection of the projecting line passing
        through the projection center and the projection object (point) with the projection plane</li>
</ul>
<h4>RECOMENDATION:</h4>
<ul>
    <li>Maximum thickness or size values 10</li>
    <li>Don't move the mouse when choosing a value</li>
</ul>
