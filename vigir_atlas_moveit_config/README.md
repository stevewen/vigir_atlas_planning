This provides a Semantic Robot Description Format (SRDF) model for the Atlas
robot as used by Team ViGIR.

As combinations of different Atlas models and hands could be used, the SRDF
model is generated at launch time based on environment variables using the
[xacro](http://wiki.ros.org/xacro) mechanism.

[vigir_atlas.srdf.xacro](https://github.com/team-vigir/vigir_atlas_planning/blob/master/vigir_atlas_moveit_config/config/vigir_atlas.srdf.xacro)
is the main macro file that is expanded to generate the SRDF model.