Local Manifests
===============

These should be overlayed with an existing Android checkout.

cd .repo
git cone ${CLONE_URL} local_manifests
cd ..
repo sync

What's here
===========

 - Linaro HW overlays
 - Rob's DRM tress
 - Pixel C hardware stuff

What else needs patching
========================

 - frameworks/base
 -- what is it: keyboard layout hack
 -- commit: f3ec536edbad295303d9a3cf80bd72a4675cf7c7
 - apps/settings
 -- what is it: more keyboard hacks
 -- commit: ?

 - services/surfaceflinger/SuerfaceFlinger.cpp
 -- see https://github.com/robherring/generic_device/wiki/Android-with-DRM-mesa-graphics
