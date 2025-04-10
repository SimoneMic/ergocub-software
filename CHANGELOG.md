# Changelog

> [!warning]
> This file documents notable changes to this project done before December 2024. 
For changes after that date, please refer to the release notes of each release at https://github.com/icub-tech-iit/ergocub-software/releases.


The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.7.6] - 2024-12-06
- Add nice looking meshes for both SN000 and SN0001/2 ergocub models (https://github.com/icub-tech-iit/ergocub-software/pull/266)
- Fixed `waist_imu_0` position (https://github.com/icub-tech-iit/ergocub-software/pull/267)

## [0.7.5] - 2024-09-03
- Fix alljoints inertials to work also on gz-sim (https://github.com/icub-tech-iit/ergocub-software/pull/250)
- ergoCub1_0: fix mass and inertia of the head (https://github.com/icub-tech-iit/ergocub-software/pull/249)
- Add angry emotion and not fullscreem mode to ergoCubEmotions (https://github.com/icub-tech-iit/ergocub-software/pull/258)

## [0.7.4] - 2024-05-27

- Refactor YAMLs for using the includes creo2urdf parameter(https://github.com/icub-tech-iit/ergocub-software/pull/240)
- Add ergoCubSN002/V1_2 (https://github.com/icub-tech-iit/ergocub-software/pull/242)

## [0.7.3] - 2024-04-10

- Added xml files for running the publish of physical joints quantities (https://github.com/icub-tech-iit/ergocub-software/pull/227)
- ergoCubSN001/ergoCubGazeboV1_1*: fix orientation of inertias (https://github.com/icub-tech-iit/ergocub-software/pull/226)
- Added `gz-sim` support (https://github.com/icub-tech-iit/ergocub-software/pull/230)

## [0.7.2] - 2024-03-11

## [0.7.1] - 2024-02-29

- ergoCubV1_1*: fix feet imus placement (https://github.com/icub-tech-iit/ergocub-software/pull/222)

## [0.7.0] - 2024-02-28

- Expose imu of the ft sensors in the feet(https://github.com/icub-tech-iit/ergocub-software/pull/217)
- `ergoCubEmotions` now consume less cpu (https://github.com/icub-tech-iit/ergocub-software/issues/213)
- ergoCubV1: fixed the names r/l_upperarm with r/l_upper_arm(https://github.com/icub-tech-iit/ergocub-software/issues/197)
- Fixed HF when resetting the world when using DART as PE(https://github.com/icub-tech-iit/ergocub-software/issues/190)
- Added `couplingXCubHandMk5` device

## [0.6.0] - 2023-11-15

### urdf
- Fixed location of `l/r_sole` frames(https://github.com/icub-tech-iit/ergocub-software/issues/186)
- Fixed alignment of depth to the RGB frame(https://github.com/icub-tech-iit/ergocub-software/issues/183)

## [0.5.0] - 2023-10-26

### urdf
- Fixed wobbling of the models after moving feet link frames

## [0.4.0] - 2023-09-04

### urdf
- Added ergoCubGazeboV1_1/_minContacs ergoCubSN001
- Repository refactored for using creo2urdf

## [0.3.4] - 2023-08-28

### urdf
- ergoCubGazeboV1: reenabled `torso_pitch` (https://github.com/icub-tech-iit/ergocub-software/issues/152)
- ergoCubGazeboV1: "center" feet csys w/ ft csys (https://github.com/icub-tech-iit/ergocub-software/issues/146)

## [0.3.3] - 2023-07-07

- Fixed concurrency in `ergoCubEmotions`(https://github.com/icub-tech-iit/ergocub-software/issues/138)

## [0.3.2] - 2023-06-16

### urdf
- Fixed lidar frame (https://github.com/icub-tech-iit/ergocub-software/pull/134)

## [0.3.0] - 2023-06-05

### urdf

- Changed the way the FT are published, now are divided per parts (https://github.com/icub-tech-iit/ergocub-software/pull/123)
- Added imu in the waist (https://github.com/icub-tech-iit/ergocub-software/pull/99)
- Locked `torso_pitch` to 10 deg (https://github.com/icub-tech-iit/ergocub-software/issues/102)
- Fixed pinkie taxels exportation (https://github.com/icub-tech-iit/ergocub-software/issues/79)
- Added the model `ergoCubGazeboV1_minContacts`

### ergoCubEmotions
- Added first draft of `ergoCubEmotions`

## [0.2.0] - 2023-03-07

### urdf
- Removed hip ft sensors from `ergoCubSN000` model.
- Aligned joint names of the hands with the real robot.
- Fixed left arm small inertia problems (https://github.com/icub-tech-iit/ergocub-software/issues/60)

## [0.1.0] - 2023-01-24

### urdf
- Add first complete version of urdf of `ergoCub`.
