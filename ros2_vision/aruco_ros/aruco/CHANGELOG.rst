^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package aruco
^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.0 (2019-09-27)
------------------
* Fix shadowed variables
* Add SYSTEN to include dirs
* Merge pull request `#68 <https://github.com/pal-robotics/aruco_ros//issues/68>`_ from aPonza/ros_format
  Autoformatting as per CppStyleGuide
* removed using namespace declarations
* autoformatting as per CppStyleGuide
* Migration to aruco 3.0.4
* Merge branch 'indigo-devel' into kinetic-devel
* Completely remove debug print
* Merge pull request `#37 <https://github.com/pal-robotics/aruco_ros//issues/37>`_ from pal-robotics/remove-debug-print
  Remove debug log msg
* Remove debug log msg
* Merge pull request `#29 <https://github.com/pal-robotics/aruco_ros//issues/29>`_ from cehberlin/kinetic-devel
  forcing opencv3 build for kinetic
* forcing opencv3 build for kinetic
* Contributors: Andrea Ponza, Bence Magyar, Christopher Hrabia, Jordi Pages, Victor Lopez

5.0.5 (2024-05-09)
------------------

5.0.4 (2023-11-14)
------------------

5.0.3 (2023-10-03)
------------------
* Added correctFisheye parameter, not the default one (false)
* Contributors: sergiomoyano

5.0.2 (2023-03-20)
------------------

5.0.1 (2023-03-06)
------------------
* remove compile options for warnings
* Contributors: Noel Jimenez

5.0.0 (2023-02-08)
------------------
* fixed cornerUpsample slicing bug issue
* disable tests for package aruco
* added missing ament exports in CMakeLists.txt
* added ament_lint test to the packages aruco and aruco_msgs
* added minor fix in aruco CMakeLists.txt
* added the ament configuration to build with colcon
* Contributors: Noel Jimenez, Sai Kishor Kothakota, josegarcia

3.1.2 (2022-11-10)
------------------
* disable the shadow compilation flag
* Contributors: Sai Kishor Kothakota

3.1.1 (2022-11-08)
------------------
* Merge branch 'fix/remove-markerlabelers' into 'gallium-devel'
  removed markerlabelers folder
  See merge request ros-overlays/aruco_ros!6
* removed markerlabelers folder
* Contributors: josecarlos, saikishor

3.1.0 (2022-11-07)
------------------
* Merge branch 'feat/aruco-3.1.5-migration-gallium' into 'gallium-devel'
  ArUCO 3.1.5 migration gallium
  See merge request ros-overlays/aruco_ros!5
* replace disable_pal_flags() with set DISABLE_PAL_FLAGS
* clang formatting
* add support for extrinsics with stereo cameras
* Add correct fisheye distortion functionality
* migrate to 3.1.5
* Contributors: josecarlos, josegarcia, saikishor

3.0.3 (2022-05-16)
------------------

3.0.2 (2022-04-05)
------------------
* Merge pull request #103 from bmagyar/make-sai-maintainer
  Make Sai maintainer of all aruco_ros packages
* Make Sai maintainer of all
* Update license tags in the package.xml
* Contributors: Bence Magyar, Sai Kishor Kothakota

3.0.1 (2022-02-10)
------------------

3.0.0 (2021-07-16)
------------------
* fixes pal-robotics/aruco_ros/#89
* Contributors: 444lhc

2.1.1 (2020-09-17)
------------------

2.1.0 (2020-01-21)
------------------
* Add param to correct fisheye distortion with special CV functions
* Add support for camera extrinsics when dealing with stereo cameras
* Contributors: Victor Lopez

2.0.2 (2019-11-09)
------------------

2.0.1 (2019-09-27)
------------------
* Fix dependency
* Contributors: Victor Lopez

0.2.2 (2017-07-25)
------------------

0.2.1 (2017-07-21)
------------------

0.2.0 (2016-10-19)
------------------
* Fix compilation error in Ubuntu 16.04
  With this change, aruco_ros compiles properly in Ubuntu 16.04, ROS kinetic.
* Contributors: Francisco

0.1.0 (2015-08-10)
------------------
* Depend on libopencv-dev directly
* Replace opencv2 dependency with cv_bridge
* Update changelogs and maintainer email
* Add aruco marker generator and opencv dependency
* Remove duplicated images
* Remove old launch files
* Contributors: Bence Magyar

0.0.1 (2015-05-20)
------------------
* Initial release
* Contributors: Bence Magyar
