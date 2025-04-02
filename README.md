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
* Additional features beyond those provided by Dewesoft are planned.
* Switching the robot and electro-hydraulic mast ON/OFF.
* Controlling the robot's lane-keeping assist function.
* Moving the mast up and down.
  * From: Starting/retracting height of 1.5 m.
  * To: Required maximum extension height of 4.5 m.
