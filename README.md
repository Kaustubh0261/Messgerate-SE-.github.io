**Clone pyDewesoft Module**
Python module to work with Dewesoft files.

!Build Status !License

**Current Capabilities: Dewesoft Files:**
* Reading native Dewesoft files (.d7d, .dxd, .d7z, and .dxz).
* Appending multiple Dewesoft files into a single Python data object.
* Filling time gaps between multiple Dewesoft files to create a continuous time vector (useful when Dewesoft has errors due to data loss).
* Data is stored in a Python object, where each channel is an attribute.
* Time vectors are stored efficiently for each channel. If a time vector is used for multiple channels, it is only stored once.
* Saving the Python object to disk with the highest compression rate.

**Planned Capabilities: '+' Files:**
* Additional features beyond those provided by Dewesoft are planned
* Switching the robot and electro-hydraulic mast ON/OFF
* Controlling the robot's lane-keeping assist function
* Moving the mast up and down
  * From: Starting/retracting height of 1.5 m
  * To: Required maximum extension height of 4.5 m

**Website Theme:**
To enhance the appearance of the website created for this project, consider the following changes:

* Theme Description: The website uses a modern, clean design with a focus on usability and accessibility. The color scheme is based on shades of blue and white, providing a professional look.
* Badges: Add badges for build status, license, and other relevant metrics to make the README more visually appealing.
* Screenshots and Demos: Include screenshots or demo links to showcase the website's design and functionality.
* Consistent Formatting: Ensure consistent use of headers, bullet points, and code blocks for better readability.
* Links to Resources: Provide links to related resources, documentation, and the project's live website.
[Screenshot](https://demos.creative-tim.com/material-dashboard-dark/examples/dashboard.html?_ga=2.83420382.916097632.1743596775-1115477352.1743596775)

For more information, visit the project website.
