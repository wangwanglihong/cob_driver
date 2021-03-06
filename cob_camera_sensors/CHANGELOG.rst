^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cob_camera_sensors
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.6.13 (2019-03-14)
-------------------

0.6.12 (2018-07-21)
-------------------

0.6.11 (2018-01-07)
-------------------
* Merge remote-tracking branch 'origin/indigo_release_candidate' into indigo_dev
* Merge pull request `#341 <https://github.com/ipa320/cob_driver/issues/341>`_ from ipa-fxm/APACHE_license
  use license apache 2.0
* use license apache 2.0
* Merge branch 'indigo_dev' of github.com:ipa320/cob_driver into feature/mimic_sim
* Merge pull request `#351 <https://github.com/ipa320/cob_driver/issues/351>`_ from mikaelarguedas/add_tinyxml_dependency
  add tinyxml to package.xml
* add tinyxml to package.xml
* Merge pull request `#349 <https://github.com/ipa320/cob_driver/issues/349>`_ from ipa320/ipa-rmb-patch-1
  Changed Maintainer
* Changed Maintainer
* Contributors: Benjamin Maidel, Felix Messmer, Mikael Arguedas, Richard Bormann, ipa-fxm, ipa-uhr-mk

0.6.10 (2017-07-24)
-------------------

0.6.9 (2017-07-18)
------------------
* manually fix changelog
* Contributors: ipa-fxm

0.6.8 (2016-10-10)
------------------

0.6.7 (2016-04-02)
------------------

0.6.6 (2016-04-01)
------------------

0.6.5 (2015-08-31)
------------------

0.6.4 (2015-08-25)
------------------
* boost revision
* explicit dependency to boost
* more cleanup
* remove obsolete autogenerated mainpage.dox files
* remove trailing whitespaces
* migrate to package format 2
* sort dependencies
* critically review dependencies
* Contributors: ipa-fxm

0.6.3 (2015-06-17)
------------------

0.6.2 (2014-12-15)
------------------

0.6.1 (2014-09-17)
------------------

0.6.0 (2014-09-09)
------------------

0.5.7 (2014-08-26)
------------------
* Merge pull request `#163 <https://github.com/ipa320/cob_driver/issues/163>`_ from ipa320/hydro_dev
  updates from hydro_dev
* 0.5.6
* update changelog
* Cleaned up cob_driver with reduced deps to compile on indigo
* Contributors: Alexander Bubeck, Florian Weisshardt

0.5.6 (2014-08-26)
------------------
* Merge pull request `#163 <https://github.com/ipa320/cob_driver/issues/163>`_ from ipa320/hydro_dev
  updates from hydro_dev
* Cleaned up cob_driver with reduced deps to compile on indigo
* Contributors: Alexander Bubeck, Florian Weisshardt

0.5.3 (2014-03-31)
------------------
* removed obsolete files
* install tags
* Contributors: ipa-fxm

0.5.2 (2014-03-20)
------------------

0.5.1 (2014-03-20)
------------------
* cob_camera_sensors: add missing dependency to message_generation/message_runtime
* cleaned up CMakeLists and added install directives
* compiling but still some linker errors
* get frame id
* Second catkinization push
* First catkinization, still need to update some CMakeLists.txt
* fixed namespace, removed obsolete lines from manifest
* removed throttle node to perception common
* moved to cob_cam3d_throttle in cob_perception_common
* set queue size to 1
* remove launch file from driver stack
* added additional topics, added launch file for testing
* Merge branch 'master' of github.com:ipa320/cob_driver
* add subscription management
* fixed nodelet name
* add nodelet plugin file
* added cam3d throttle
* remove deprecated deps of cob_camera_sensors
* moved kinect image flip from cob_camera_sensors to cob_image_flip
* moved kinect image flip from cob_camera_sensors to cob_image_flip
* removed deprecated debs
* Merge branch 'release_fuerte'
* fuerte rosdep migration
* changes for fuerte compatibility
* fix lib directory
* removed deprecated launch files
* using tinyxml from system dependency
* merge
* using kinect driver without nodelet
* small changes
* Merge branch 'master' of github.com:ipa-fmw/cob_driver
* add voxelgrid filter
* set frrequency of cameras to 10
* deactivate test for cam3d
* using env ROBOT
* small changes
* fix test for camera_sensors
* merge with 320
* merge
* Removed kinect stuff. To be replaced by rmb version
* added dummy depth calibration to kinect driver
* adapted cob_camera_sensors to new kinect driver in electric
* camera_sensors test
* fixed includes
* added rostest
* Updated camera calibration for cob3-3
* PCH LINUX
* PCH
* PCH
* StdAFx
* merge
* Merge branch 'review-rmb'
* moved vision message and service files
* moved services to camera_sensors
* merge
* changed topic names
* enlarged wait_time
* added wait time for hztest_camera_left
* added wait_time
* adapted test files
* switched master/slave settings for cob3-2 since they are mounted the other way around
* updated timestamp in flipped images from kinect (because of rosbag play problem)
* changed the topic names again to the last change before they were overwritten by fmw
* sensor fusion finally working
* merg
* merge
* adjust camera parameter
* image flip
* uplaod param file
* merge
* new calibration for kinect
* higher resolution for cob3-1 cameras
* now saves the transxformation to head_axis_link
* calib script for cob3-3
* adapted tof test parameters
* test configuration
* changed test topic of tof
* changed frame names
* corrected the swissranger topics to the unified naming scheme
* merge
* more comments added to yaml generator script
* added Matlab script for generating yaml files
* correct camera startup order in all_cameras.launch
* added new camera properties to the driver and config files (auto exposure maximal duration)
* new auto exposure settings in yaml file
* renamed all_cameras.launch in demo-cell folder
* new link names for kinect sensors
* new links for kinect
* new link names for the prosilica cameras
* renamed the camera sensors launch files
* renamed topics for people detection
* Merge branch 'master' of github.com:ipa-rmb/cob_driver
* added camera parameter paket_size
* configuration files now correct
* fixed position of rosparam in launch file
* added trigger_mode parameter to yaml files and corrected their values
* added settings for cob3-3 prosilica cameras
* merge
* cob_camera_sensor's launch files reorganized. almost done.
* kinect flip outputting image head over reverted (no bug, was already correct)
* kinect flip outputting image head over fixed
* merge
* prosilica can load intrinsic parameters from calibration automatically in cob_camera_sensors
* reorganizing launch files in cob_camera_sensors
* reorganizing launch files in cob_camera_sensors
* added script for loading camera parameters
* Merge branch 'master' of github.com:ipa-rmb/cob_driver
* rearranging cob_camera_sensors launch files
* reorganizing launch files in cob_camera_sensors
* rearranging cob_camera_sensors launch files
* cam3d for cob3-1
* rearranging cob_camera_sensors launch files
* reorganizing cob_camera_sensors launch files
* reorganizing cob_camera_sensors launch files
* kinect and prosilica calibration added for cob3-3
* camera and kinect calibration
* Merge branch 'review-320'
* Merge branch 'review-goa-aa'
* added missing nodelet_plugins.xml file for kinect flip
* camera image flip with respect to camera pose on head finished and tested
* added a nodelet for rotating the kinect image when the robots watches backwards
* added test for full_cloud2
* Merged Pointer for PMDCamCube and PMDCamBoard to PMDCam
* Merge branch 'review-320'
* undid last changes
* fixed typo
* testing other parameters
* Added encoding ro image message
* bugfix in VirtualRangeCam
* updates for cob_classifier_training
* updates because of cameraDataViewer adaptation to kinect
* updates because of cameraDataViewer adaptation to kinect
* Added CamBoard to AbstractRangeImagingSensor.h
* changed test duration to 10s
* added camera calibration files from matlab calibration
* camera settings added for head
* undo previous merge + commits
* merge with review-sven
* removed kinect form all cameras
* added kinect to all_cameras.launch
* added kinect to all_cameras.launch
* typo fixed
* modified parameters
* rostest file for tof camera
* deleted rostest file integration
* included rostest file
* included rostest file
* included rostest
* included rostest file
* cameras working and calibrated
* renamed camera topics
* Git adaptions
* def LINUX
* fixed libusb bug
* change back to cturtle
* merge
* merge
* starting kinect with cob_bringup
* removed mesa swissranger form the cob_bringup
* added dependency to prosilica driver
* fixed topics for camera test
* added camera tests
* now compatible to diamondback, does not compile anynmore with cturtle
* chenged manifest
* uncommented line
* made cameras working
* node for undistorting tof data
* removed libmesa in rosdep.yaml
* changed tof defaults
* set fps to 15
* cleanup in cob_driver
* launch file for all cameras with ros driver
* ros driver now working, add calibration data
* calibration files for cameras
* changes related to dc1394 ros driver
* added launch file for left camera, modified parameters
* launch file for camera1394
* ros/src/all_camera_viewer.cpp
  some changes
* bugfix
* bugfix
* JSF: Bugfix
* JSF: Bugfixes
* JSF: Added filtering for calibrating with noisy tof greyscale images
* disabled sw trigger
* adapted topic names
* inserted frame_id to all camera topics
* removed unused channels from PointCloud2
* bugfix
* added params to toggle publishing
* added params to toggle publishing
* added params to toggle publishing
* tof now publishes also PointCloud
* add tf information
* tof now publishes also PointCloud2
* added feature mask
* update documentation and deleted tf broadcaster
* bug fixes
* launch files now independent of cob number
* launch files for color cameras on cob3-2
* launch file for all cameras
* removed blacklist
* restructured launch files for camera sensors
* JSF: Did not much
* adapted to new param names
* added support for virtual cameras
* Merge branch 'master' of github.com:ipa-goa/care-o-bot
* added virtual camera support
* JSF: Removed dependency to libwm4
* JSF: Added filtering function for isolated points in point cloud
* JSF
* add ROS_BUILD_BLACKLIST
* JSF: Integrated image acquisition method for all cameras to calibrate
* JSF: Added image capture program to enable convenient calibration
* fixed assertion condition
* added filter functions to vision_utils
* JSF: refactoring
* JSF: refactored
* JSF: refactoring
* JSF: refactoring
* JSF: refactoring
* JSF: Refactoring
* parallel service and topic
* service mode changes
* service mode changes
* service mode changes
* service mode changes
* JSF
* JSF: Bugfix for Pike camera for proper closing
* added image service to tof node
* added filtering of tear-off edges and amplitudes for TOF cameras
* Merge branch 'master' of github.com:ipa320/care-o-bot into ipa320
* JSF: Fixed memory leaks
* cleanup in cob_driver
* changed CAM_VIRTUAL to CAM_SWISSRANGER
* Merge branch 'master' of git@github.com:ipa-goa/care-o-bot
* changed distortion parameters
* launch file for all cameras on cob3-2
* JSF: Modified VirtualRangeCamera to acquire amplitude images instead of z images
* Merge branch 'review'
  Conflicts:
  cob_driver/cob_camera_sensors/ros/launch/cob3-2_tof.launch
* Merge branch 'master' of git@github.com:ipa-goa/care-o-bot
* changed directory for virtual cam
* JSF: Bugfix
* JSF: Bugfix
* JSF: Added intrinsics to topic
* JSF: Added intrinsics to topic
* JSF: Added readme file
* JSF: Added tutorial for camera sensors
* JSF
* JSF: Conflicts resolving
* JSF: Bugfixes
* JSF: Bugfix
* launch file for cob3-2 tof
* removed range depth image from Virtual Range Camera
* JSF: Implemented support of different intrinsic matrices
* JSF: Adapted intrinsic matrix handling
* JSF: Added intrinsic adaption to tof_viewer
* JSF: Added possibility to have several intrinsics
* switched intrinsics
* added camera paramters for hand-eye-calibration
* launch file for tof on cob3-2
* Merge branch 'master' into review
  Conflicts:
  cob_driver/cob_camera_sensors/ros/src/tof_camera_viewer.cpp
* added delay in grey image callback to improve quality
* new calibration data
* removed wrong number
* merge
* bugfixes and remap adaptions
* JSF: Adapted service parameters
* removed ros target libraries
* JSF: adapted namespaces
* JSF: Namespace adaptions
* Merge branch 'master' of git@github.com:ipa320/care-o-bot into review
* JSF: Adapted namespaces
* merged conflict
* save commit
* removed dependencies
* removed 3D support from tof viewer because of dependency issues
* camera config file for cob3-2
* GOA: added 3D viewer
* GOA: renamed message in GetColoredPointCloud service
* GOA: changes in config files
* GOA: changed point cloud service
* merge with ipa320
* JSF
* JSF: Cleaned up cob_camera_sensors
* JSF: Adapted size of remap matrix for undistortion to be adaptive to swissranger and PMD sensor
* launch file for camera synchronizer
* GOA: grey images can be saved in tof_camera_viewer now
  added camera_synchronizer node
* bugfix
* bug fix
* GOA: added launch file for prosilica cameras
* JSF : Implemented all_cameras node to open all connected cameras at once. This enables triggereing of all cameras
* JSF: Added node to open all cameras at once
* JSF: Added node to open all cameras at once
* JSF
* JSF: Merged conflicted files
* JSF: Adapted ROS Makefiles
* JSF: Adapted include paths
* JSF: Merged conflicts
* JSF: Adapted include paths
* JSF: Extended vision utils by two files two remove dependecy of cob_sensor_fusion from cob_camera_sensors
* JSF: Added short documentation for camera drivers
* JSF: Fixed problem with ToF viewer, added support for both color cameras
* link libdc1394 to cob_camera_sensors library
* renamed to general cob packages
* record changes
* modified play file, added kinect parameters
* modified launch files
* record acripts for kinect data
* merge
* changed name
* calib position update
* Merge branch 'review-320'
* changed to PointXYZ
* Contributors: Alexander Bubeck, COB3-Navigation, Georg, Georg Arbeiter, Jan Fischer, Richard Bormann, abubeck, b-it-bots, cob, cob3-1-pc2, cpc-pk, fmw-jk, goa, goa-uq, ipa-cob3-3, ipa-fmw, ipa-goa, ipa-goa-aa, ipa-jsf, ipa-mig, ipa-rmb, ipa-taj, ipa-uhr-fm, ipa320, unknown
