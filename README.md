# Social Distancing with Coral PoseNet

A simple example for verifying compliance with social distancing rules.
Instead of relying on camera calibration for 6 ft (3 m), relative size
of the person is used to estimate height. The underlying model,
 PoseNet (https://github.com/google-coral/project-posenet), is used to
 detect people and calculate their size (in pixels).

Models (taken from the PoseNet repo) are provided for both MobileNet and
ResNet50 backbones (only the EdgeTPU versions are provided).
