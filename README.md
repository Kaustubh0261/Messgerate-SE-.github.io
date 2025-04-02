# clone pyDewesoft module

Python module to work with Dewesoft'+' files. 

Current capabilities: Dewesoft files
* Reading native Dewesoft files (.d7d, .dxd, .d7z and .dxz)
* Appending multiple Dewesoft files in a single Python data object.
* Filling time gaps between multiple Dewesoft files, to create a continues time vector (useful when Dewesoft has error due to data lost)
* Data is stored in a Python object, where each channel is an attribute
* Time vectors are stored effectively for each channel. If a time vector is used for multiple channels it is only stored once.
* Saving to disk of the Python object is done with the highest compression rate

Planned capabilities: '+' files
* Otherthan the existing capabilities already provided by Dewesoft, some other extras are planned.
* AN/AUS schalten von Roboter und Elektrohydraulischer Mast. (Switching the robot and electro-hydraulic mast ON/OFF.)
* Steuerung der Spurhalteassistentfunktion des Roboters.(Controlling the robot's lane-keeping assist function.)
* Auf- und Abbewegung des Mastes.(Moving the mast up and down.)
(Von: Start-/Einfahrhöhe von 1,5 m.)- (From: Starting/retracting height of 1.5 m.)
(Bis: Erforderliche maximale Ausfahrhöhe von 4,5 m.)- (To: Required maximum extension height of 4.5 m.)
