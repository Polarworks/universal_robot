# Polarworks Fork of `universal_robot` repo - `melodic-devel-staging` branch 

## Changes

This doesn't actually need changes to BUILD on windows, which is good news, but

`melodic-devel-staging` branch now depends on https://github.com/ros-industrial/ur_msgs

This should be added to the catkin workspace before trying to build.

I made a fork of `ur_msgs` which I can't delete, but this is not needed. Clone

https://github.com/ros-industrial/ur_msgs 

into `src` with this package to build (trying with `melodic-devel` branch)

We may still need `melodic-devel-staging-win` branch to support Dan on Windows, but I think the changes will be small changes in launch files, etc, if any.

