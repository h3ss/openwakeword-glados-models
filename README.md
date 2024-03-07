# openwakeword-glados-models
This repository contains openWakeWord models for the name "GLaDOS" from the Portal 2 franchise.

These models are suitable for use with Home Assistant with the openWakeWord plugin.  Simply use SCP to transfer the .tflite file to your HAOS machine in the `/share/openwakeword/` directory.

There are two versions of the model:

- **GLaDOS**: This responds to the word "GLaDOS" by itself
- **Ok_GLaDOS** _(recommended)_: This responds to "Okay GLaDOS" or "Hey GLaDOS".  Because it is more specific, I find this one seems to be more responsive.
