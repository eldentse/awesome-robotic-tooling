# Awesome Robotic Tooling ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

Just a bunch of powerful robotic resources and tools for professional robotic development with ROS in C++ and Python.

**ONLY Packages that are still maintained!**

* [Example Format](#example-format)
* [Development Environment](#development-environment)
  * [Backbone](#backbone)
  * [Docker](#docker)
* [Dataprocessing](#data-processing)
  * [Image Processing](#image-processing)
  * [Point Cloud Processing](#point-cloud-processing)
* [Middleware](#package-managers)
  * [Timeline](#timeline)
  * [Spreadsheet](#spreadsheet)
* [Security](#security)
* [Safety](#safety)
* [Documentation](#documentation)
* [Commandline]
* [Robotic Functions]
  * [Localisation]
  * [Detection]
  * [Planning]
  * [Decision]
----


## Coordination and Communication
* [Taiga](https://github.com/benhutchins/docker-taiga) - Agile Projectmanagment Tool
* [Kanboard](https://github.com/kanboard/kanboard) - Minimalistic Kanban Board
* [Gitlab](https://github.com/sameersbn/docker-gitlab) - Simple Selfhosted Gitlab Server with Docker
* [Gitflow](https://github.com/nvie/gitflow) - Makes parallel development very easy, by isolating new development from finished work
* [Gogs](https://github.com/gogs/gogs) - Aims to build a simple, stable and extensible self-hosted Git service that can be setup in the most painless way
* [Woost](https://woost.space/) - Workflow Automatisation
* [Wekan](https://github.com/wekan/wekan) - Meteor based Kanban Board
* [JIRA API](https://github.com/pycontribs/jira) - Python Library for REST API of Jira
* [Taiga API](https://github.com/nephila/python-taiga) - Python Library for REST API of Taiga
* [Agile Development](https://agilemanifesto.org/) - Manifesto for Agile Software Development
* [Chronos - Timetracker](https://github.com/web-pal/chronos-timetracker)  - Desktop client for JIRA. Track time, upload worklogs without a hassle
* [Grge](https://gitlab.com/ApexAI/grge) - Grge is a daemon and command line utility augmenting GitLab
* [Issue Gitlab Good Practice](https://docs.gitlab.com/ee/development/contributing/issue_workflow.html) - Gitlabs Issue triage policies
* [Git-repo](https://gerrit.googlesource.com/git-repo/) - Git-Repo helps manage many Git repositories, does the uploads to revision control systems, and automates parts of the development workflow
* [Helpy](https://github.com/helpyio/helpy) - is a modern, open source helpdesk customer support application

## Documentation and Presentation
* [Typora](https://typora.io/) - A Minimalist Markdown Editor
* [Markor](https://github.com/gsantner/markor) - A Simple Markdown Editor for your Android Device
* [Pandoc](https://github.com/jgm/pandoc) - Universal markup converter
* [Yaspeller](https://github.com/hcodes/yaspeller) - Command line tool for spell checking
* [Doxygen](https://github.com/doxygen/doxygen) - Doxygen is the de facto standard tool for generating documentation from annotated C++ sources
* [Word-to-Markdown](https://github.com/benbalter/word-to-markdown) - A ruby gem to liberate content from Microsoft Word document
* [DeepL](https://deepl.com) - Translate complete documents better than most humans
* [ASCIIMATICS](https://github.com/peterbrittain/asciimatics) - Create a GIF for your command line examples
* [Reveal-Hugo](https://github.com/dzello/reveal-hugo) - A Hugo theme for Reveal.js that makes authoring and customization a breeze. With it, you can turn any properly-formatted Hugo content into a HTML presentation.
* [Hugo-Webslides]https://github.com/RCJacH/hugo-webslides) - This is a Hugo template to create WebSlides presentation using markdown.
* [pydocstyle](https://github.com/PyCQA/pydocstyle)pydocstyle is a static analysis tool for checking compliance with Python docstring conventions


## Architecture and Design
* [yed](https://www.yworks.com/products/yed) - yEd is a powerful desktop application that can be used to quickly and effectively generate high-quality diagrams
* [yed_py](https://github.com/true-grue/yed_py) - Generates graphML that can be opened in yEd
* [Plantuml](https://github.com/plantuml/plantuml-server) - Web application to generate UML diagrams on-the-fly in your live documentation	
* [rqt_graph](https://wiki.ros.org/rqt_graph) - rqt_graph provides a GUI plugin for visualizing the ROS computation graph
* [rqt_launchtree](https://github.com/pschillinger/rqt_launchtree) - An RQT plugin for hierarchical launchfile configuration introspection.
* [cpp-dependencies](https://github.com/tomtom-international/cpp-dependencies) - Tool to check C++ #include dependencies (dependency graphs created in .dot format)


## Framework
* [ROS](https://github.com/ros) - ROS (Robot Operating System) provides libraries and tools to help software developers create robot applications
* [ROS2](https://github.com/ros2/ros2) - ROS2 is the next generation robot operating system, and is actively being developed to fully replace ROS1 in the near future
* [OpenPilot](https://github.com/commaai/openpilot) - Open Source Aaptive Cruise Control (ACC) and Lane Keeping Assist System (LKAS) 
* [Apollo](https://github.com/ApolloAuto/apollo) - High performance, flexible architecture which accelerates the development, testing, and deployment of Autonomous Vehicles.
* [Autoware.ai](https://gitlab.com/autowarefoundation/autoware.ai) - Autoware.AI is the world's first "All-in-One" open-source software for autonomous driving technology
* [AutowareAuto](https://autowareauto.gitlab.io/AutowareAuto/) - It is a clean slate rewrite of Autoware. Autoware.Auto applies best-in-class software engineering.
* [Stanford Self Driving Car Code](https://github.com/emmjaykay/stanford_self_driving_car_code) - Stanford Code From Cars That Entered DARPA Grand Challenges

## Development Environment
### Template
* [ROS](https://github.com/leggedrobotics/ros_best_practices/tree/master/ros_package_template) - Template for ROS node standardization in C++ 
* [Launch](https://wiki.ros.org/roslaunch/Tutorials/Roslaunch%20tips%20for%20larger%20projects) Templates on how to create launch files for larger projects
* [Bash](https://github.com/ralish/bash-script-template) - A bash scripting template incorporating best practices & several useful functions
* [URDF](https://wiki.ros.org/urdf/Examples) - Examples on how to create Unified Robot Description Format (URDF) for different kinds of robots
* [Python](http://wiki.ros.org/PyStyleGuide) - Style guide to be followed in writing Python code for ROS

### Code and Run
[Vim-ros](https://github.com/taketwo/vim-ros) - Vim plugin for ROS development
[vccode](https://github.com/Microsoft/vscode) - Code editor with for edit-build-debug cycle.
[atom](https://github.com/atom/atom) - Hackable text editor for the 21st century
[Sublime](https://www.sublimetext.com/) - A sophisticated text editor for code, markup and prose
[ade-cli](https://gitlab.com/ApexAI/ade-cli) - The ADE Development Environment (ADE) uses docker and gitlab to manage environments of per project development tools and optional volume images
[Jupyter ROS](https://github.com/RoboStack/jupyter-ros) - Jupyter widget helpers for ROS, the Robot Operating System
[ros_rqt_plugin](https://github.com/ros-industrial/ros_qtc_plugin) - The ROS Qt Creator Plug-in 	
[ROS IDEs](http://wiki.ros.org/IDEs) - This page collects experience and advice on using integrated development environments (IDEs) with ROS.
[TabNine](https://github.com/zxqfl/TabNine) - The all-language autocompleter
[kite](https://kite.com/) - Use machine learning to give you 
 useful code completions for Python
[jedi](https://github.com/davidhalter/jedi) - Autocompletion and static analysis library for python
[roslibpy](https://github.com/gramaziokohler/roslibpy) - Python ROS Bridge library allows to use Python and IronPython to interact with ROS, the open-source robotic middleware. 

### Build and Deploy
[bloom](https://github.com/ros-infrastructure/bloom) - A release automation tool which makes releasing catkin packages easier
[catkin_tools](https://github.com/catkin/catkin_tools) - Command line tools for working with catkin
[industrial_ci](https://github.com/ros-industrial/industrial_ci) - Easy continuous integration repository for ROS repositories
[gitlab-runner](https://gitlab.com/gitlab-org/gitlab-runner) -  runs tests and sends the results to GitLab
[colcon-core](https://github.com/colcon/colcon-core) - command line tool to improve the workflow of building, testing and using multiple software packages
[gitlab-release](https://gitlab.com/alelec/gitlab-release) - Simple python3 script to upload files (from ci) to the current projects release (tag)
[clang](https://github.com/llvm-mirror/clang) -  This is a compiler front-end for the C family of languages
(C, C++, Objective-C, and Objective-C++) which is built as part of the LLVM
compiler infrastructure project

### Unit and Integration Test
[UnitTesting](https://wiki.ros.org/Quality/Tutorials/UnitTesting) - This page lays out the rationale, best practices, and policies for writing and running unit tests and integration tests for ROS.
[googletest](https://github.com/google/googletest) - Google's C++ test framework
[pytest](https://github.com/pytest-dev/pytest/) - The pytest framework makes it easy to write small tests, yet scales to support complex functional testing 

### Lint and Format
[cppcheck](https://github.com/danmar/cppcheck) - Static analysis of C/C++ code
[shellcheck](https://github.com/koalaman/shellcheck) - a static analysis tool for shell scripts 
[catkin_lint](https://github.com/fkie/catkin_lint) - catkin_lint checks package configurations for the catkin build system of ROS.
[pylint](https://github.com/PyCQA/pylint/) - Pylint is a Python static code analysis tool which looks for programming errors, helps enforcing a coding standard, sniffs for code smells and offers simple refactoring suggestions.
[black](https://github.com/psf/black) - The uncompromising Python code formatter 

### Version Control
[meld](https://github.com/kaiw/meld) - Meld is a visual diff and merge tool that helps you compare files, directories, and version controlled projects
[tig](https://github.com/jonas/tig) - Text-mode interface for git 
[gitg](https://github.com/GNOME/gitg) - is a graphical user interface for git
[python-gitlab](https://github.com/python-gitlab/python-gitlab) - is a Python package providing access to the GitLab server API.
[bfg-repo-cleaner](https://github.com/rtyley/bfg-repo-cleaner) - Removes large or troublesome blobs like git-filter-branch does, but faster.

## Hardware
* [HRIM](https://github.com/AcutronicRobotics/HRIM) - An information model for robot hardware
* [URDF](https://github.com/ros/urdf) - Repository forUnified Robot Description Format (URDF) parsing code
* [urdf-viz](https://github.com/OTL/urdf-viz) - Visualize URDF/XACRO file, URDF Viewer works on Windows/MacOS/Linux
* [solidworks_urdf_exporter](https://github.com/ros/solidworks_urdf_exporter) - SolidWorks to URDF Exporter
* [FreeCAD](https://github.com/FreeCAD/FreeCAD) - Your own 3D parametric modeler

### Calibration
* [lidar_align](https://github.com/ethz-asl/lidar_align) - A simple method for finding the extrinsic calibration between a 3D lidar and a 6-dof pose sensor
* [kalibr](https://github.com/ethz-asl/kalibr) - The Kalibr visual-inertial calibration toolbox
* [Calibnet](https://github.com/epiception/CalibNet) - Self-Supervised Extrinsic Calibration using 3D Spatial Transformer Networks
* [lidar_camera_calibration](https://github.com/ankitdhall/lidar_camera_calibration) - ROS package to find a rigid-body transformation between a LiDAR and a camera
* [easy_handeye](https://github.com/IFL-CAMP/easy_handeye) - Simple, straighforward ROS library for hand-eye calibration
* [imu_utils](https://github.com/gaowenliang/imu_utils) - A ROS package tool to analyze the IMU performance
* [kalibr_allan]https://github.com/rpng/kalibr_allan - IMU Allan standard deviation charts for use with Kalibr and inertial kalman filters

## Simulation
* [lgsv](https://github.com/lgsvl/simulator) - LG Electronics America R&D Center has developed an HDRP Unity-based multi-robot simulator for autonomous vehicle developers.
* [carla](https://github.com/carla-simulator/carla) - Open-source simulator for autonomous driving research
* [deepdive](https://github.com/deepdrive/deepdrive) - End-to-end simulation for self-driving cars 
* [uuv_simulator](https://github.com/uuvsimulator/uuv_simulator) - Gazebo/ROS packages for underwater robotics simulation
* [AirSim](https://github.com/microsoft/AirSim) - Open source simulator for autonomous vehicles built on Unreal Engine 
* [self-driving-car-sim](https://github.com/udacity/self-driving-car-sim) - A self-driving car simulator built with Unity
* [ROSIntegration](https://github.com/code-iai/ROSIntegration) - Unreal Engine Plugin to enable ROS Support
* [gym-gazebo](https://github.com/erlerobot/gym-gazebo) - An OpenAI gym extension for using Gazebo known as gym-gazebo
* [highway-env](https://github.com/eleurent/highway-env)	- A collection of environments for autonomous driving and tactical decision-making tasks

## Robotic Functions
### Localization
* [evo](https://github.com/MichaelGrupp/evo) - Python package for the evaluation of odometry and SLAM
* [robot_localization](https://github.com/cra-ros-pkg/robot_localization) - is a package of nonlinear state estimation nodes
* [fuse](https://github.com/locusrobotics/fuse) - General architecture for performing sensor fusion live on a 
robot.
* [rep-105](https://www.ros.org/reps/rep-0105.html) - Naming conventions and semantic meaning for
coordinate frames of mobile platforms used with ROS.
* [GeographicLib](https://github.com/Sciumo/GeographicLib) - A C++ library for geographic projections.
* [ntripbrowser](https://github.com/emlid/ntripbrowser) - A Python API for browsing NTRIP (Networked Transport of RTCM via Internet Protocol).

### Sensor Processing
#### Machine Learning
* [DLIB](https://github.com/davisking/dlib) - A toolkit for making real world machine learning and data analysis applications in C++
* [fastai](https://github.com/fastai/fastai) - The fastai library simplifies training fast and accurate neural nets using modern best practices.
* [tpot](https://github.com/EpistasisLab/tpot) - A Python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming
* [deap](https://github.com/DEAP/deap) - Distributed Evolutionary Algorithms in Python
* [gym](https://github.com/openai/gym) - A toolkit for developing and comparing reinforcement learning algorithms.

#### Image Processing
* [visp](https://github.com/lagadic/visp) - Open Source Visual Servoing Platform
* [deep_object_pose](https://github.com/NVlabs/Deep_Object_Pose) - Deep Object Pose Estimation
* [DetectAndTrack](https://github.com/facebookresearch/DetectAndTrack) - Detect-and-Track: Efficient Pose
* [SfMLearner](https://github.com/tinghuiz/SfMLearner) - An unsupervised learning framework for depth and ego-motion estimation
* [imgaug](https://github.com/aleju/imgaug) - Image augmentation for machine learning experiments
https://github.com/ros-perception/vision_opencv - Packages for interfacing ROS with OpenCV, a library of programming functions for real time computer vision.

#### Point Cloud Processing
* [cilantro](https://github.com/kzampog/cilantro) - A lean C++ library for working with point cloud data
* [open3d](https://github.com/intel-isl/Open3D) - Open3D: A Modern Library for 3D Data Processing
* [SqueezeSeg](https://github.com/BichenWuUCB/SqueezeSeg) - Implementation of SqueezeSeg, convolutional neural networks for LiDAR point clout segmentation
* [point_cloud_io](https://github.com/ANYbotics/point_cloud_io) - ROS nodes to read and write point clouds from and to files (e.g. ply, vtk).
* [python-pcl](https://github.com/strawlab/python-pcl) - Python bindings to the pointcloud library
* [libpointmatcher](https://github.com/ethz-asl/libpointmatcher) - An "Iterative Closest Point" library for 2-D/3-D mapping in Robotics
* [depth_clustering](https://github.com/PRBonn/depth_clustering) - Fast and robust clustering of point clouds generated with a Velodyne sensor. 
* [lidar-bonnetal](https://github.com/PRBonn/lidar-bonnetal) - Semantic and Instance Segmentation of LiDAR point clouds for autonomous driving
* [CSF](https://github.com/jianboqi/CSF) - LiDAR point cloud ground filtering / segmentation (bare earth extraction) method based on cloth simulation


#### SLAM
##### Lidar
* [loam_velodyne](https://github.com/laboshinl/loam_velodyne) - Laser Odometry and Mapping (Loam) is a realtime method for state estimation and mapping using a 3D lidar.
* [lio-mapping](https://github.com/hyye/lio-mapping) - Implementation of Tightly Coupled 3D Lidar Inertial Odometry and Mapping (LIO-mapping)
* [A-LOAM](https://github.com/HKUST-Aerial-Robotics/A-LOAM) - Advanced implementation of LOAM
* [cartographer_ros](https://github.com/googlecartographer/cartographer_ros) - Provides ROS integration for Cartographer
* [loam_livox](https://github.com/hku-mars/loam_livox) - A robust LiDAR Odometry and Mapping (LOAM) package for Livox-LiDAR

#### Camera
* [dso](https://github.com/JakobEngel/dso/) - Direct Sparse Odometry
* [viso2](https://github.com/srv/viso2) - A ROS wrapper for libviso2, a library for visual odometry
* [xivo](https://github.com/ucla-vision/xivo) - X Inertial-aided Visual Odometry

#### Static Maps
* [StaticMapping](https://github.com/EdwardLiuyc/StaticMapping) - Use LiDAR to map the static world
* [MapsModelsImporter](https://github.com/eliemichel/MapsModelsImporter) - A Blender add-on to import models from google maps
* [Lanelet2](https://github.com/fzi-forschungszentrum-informatik/Lanelet2) - Map handling framework for automated driving
* [barefoot](https://github.com/bmwcarit/barefoot) -  Online and Offline map matching that can be used stand-alone and in the cloud
* [iD](https://github.com/openstreetmap/iD) - The easy-to-use OpenStreetMap editor in JavaScript
https://github.com/ethz-asl/segmap - A map representation based on 3D segments 

* [Mapbox](https://github.com/mapbox/mapbox-gl-jsMapbox) is a JavaScript library for interactive, customizable vector maps on the web

* [osrm-backend](https://github.com/Project-OSRM/osrm-backend) - Open Source Routing Machine - C++ backend


### Behavior and Decision
* [BehaviorTree.CPP](https://github.com/BehaviorTree/BehaviorTree.CPP) - Behavior Trees Library in C++
* [RAFCON](https://github.com/DLR-RM/RAFCON) - Uses hierarchical state machines, featuring concurrent state execution, to represent robot programs

### Planning and Control
* [rrt](https://github.com/RoboJackets/rrt) - C++ RRT (Rapidly-exploring Random Tree) implementation
* [HypridAStarTrailer](https://github.com/AtsushiSakai/HybridAStarTrailer) - A path planning algorithm based on Hybrid A* for trailer truck.
* [path_planner](https://github.com/karlkurzer/path_planner) - Hybrid A* Path Planner for the KTH Research Concept Vehicle
* [open_street_map](https://github.com/ros-geographic-info/open_street_map) - ROS packages for working with Open Street Map geographic information.

## Developer Interaction
### Graphical User Interface
[dynamic_reconfigure](https://wiki.ros.org/dynamic_reconfigure) - The focus of dynamic_reconfigure is on providing a standard way to expose a subset of a node's parameters to external reconfiguration
[mir](https://github.com/MirServer/mir) - Mir is set of libraries for building Wayland based shells
[qtpy](https://github.com/spyder-ide/qtpy) - Provides an uniform layer to support PyQt5, PySide2, PyQt4 and PySide with a single codebase
[rqt](https://wiki.ros.org/rqt) - rqt is a Qt-based framework for GUI development for ROS. It consists of three parts/metapackages
[cage](https://github.com/Hjdskes/cage) This is Cage, a Wayland kiosk. A kiosk runs a single, maximized application.
[chilipie](https://github.com/futurice/chilipie-kiosk) - Easy-to-use Raspberry Pi image for booting directly into full-screen Chrome

### Command Line
https://github.com/cornerman/dotfiles - Powerful zsh and vim dotfiles
https://github.com/cornerman/prompt-hjem - A beautiful zsh prompt
https://github.com/ggreer/the_silver_searcher - A code-searching tool similar to ack, but faster.
https://github.com/junegunn/fzf - A command-line fuzzy finder
https://github.com/orhun/pkgtop - Interactive package manager and resource monitor designed for the GNU/Linux.
https://github.com/jroimartin/gocui - Minimalist Go package aimed at creating Console User Interfaces.
https://github.com/stefanhaustein/TerminalImageViewer - Small C++ program to display images in a (modern) terminal using RGB ANSI codes and unicode block graphics characters
https://github.com/dheera/rosshow - Visualize ROS topics inside a terminal with Unicode/ASCII art
https://github.com/prompt-toolkit/python-prompt-toolkit - Library for building powerful interactive command line applications in Python
https://github.com/ralish/bash-script-template - A best practices Bash script template with several useful functions
https://github.com/Guake/guake - Drop-down terminal for GNOME
https://github.com/zolrath/wemux - Multi-User Tmux Made Easy
https://github.com/tmux-python/tmuxp -  tmux session manager. built on libtmux
https://github.com/rastapasta/mapscii - World map renderer for your console
https://launchpad.net/terminator - The goal of this project is to produce a useful tool for arranging terminals

### Storage
https://github.com/borgbackup/borg - Deduplicating archiver with compression and authenticated encryption
https://github.com/swri-robotics/bag-database - A server that catalogs bag files and provides a web-based UI for accessing them
https://gitlab.com/ternaris/marv-robotics - MARV Robotics is a powerful and extensible data management platform
https://github.com/nextcloud/server - Nextcloud is a suite of client-server software for creating and using file hosting services.

### High Performance Computing 
https://github.com/kubeflow/kubeflow - Machine Learning Toolkit for Kubernetes
https://github.com/AliyunContainerService/log-pilot - Collect logs for docker containers
https://github.com/containous/traefik - The Cloud Native Edge Router 
https://github.com/Graylog2/graylog2-server - Free and open source log management
https://github.com/ansible/ansible - Ansible is a radically simple IT automation platform that makes your applications and systems easier to deplo
https://github.com/docker/docker-py - A Python library for the Docker Engine API 
https://github.com/novnc/noVNC - VNC client using HTML5
https://github.com/SchedMD/slurm - Slurm: A Highly Scalable Workload Manager
https://github.com/jupyterhub/jupyterhub - Multi-user server for Jupyter notebooks
https://github.com/portainer/portainer	 - Making Docker management easy

#### Parallel Processing
[dask](https://github.com/dask/dask) - Parallel computing with task scheduling for Python
[cupy](https://github.com/cupy/cupy) - NumPy-like API accelerated with CUDA
[thrust](https://github.com/thrust/thrust) - Thrust is a C++ parallel programming library which resembles the C++ Standard Library.
[Array]Firehttps://github.com/arrayfire/arrayfire - ArrayFire: a general purpose GPU library.

### Annotation
https://github.com/RMonica/rviz_cloud_annotation - Point cloud annotation tool based on RViz
https://github.com/abreheret/PixelAnnotationTool - Annotate quickly images
https://github.com/tzutalin/labelImg - LabelImg is a graphical image annotation tool and label object bounding boxes in images

### Visualization
https://github.com/cruise-automation/webviz - web-based visualization libraries like rviz
https://github.com/plotly/plotly.py - An open-source, interactive graphing library for Python
https://github.com/facontidavide/PlotJuggler - The timeseries visualization tool that you deserve 
https://github.com/bokeh/bokeh - Interactive Data Visualization in the browser, from Python
https://github.com/voila-dashboards/voila - From Jupyter notebooks to standalone web applications and dashboards
https://github.com/stevenlovegrove/Pangolin - Pangolin is a lightweight portable rapid development library for managing OpenGL display / interaction and abstracting video input.
https://github.com/thebjorn/pydeps - Python Module Dependency graphs

#### Point Clouds
https://github.com/CloudCompare/CloudCompare - CloudCompare is a 3D point cloud (and triangular mesh) processing software.
https://github.com/potree/potree - WebGL point cloud viewer for large datasets 
https://github.com/googlecartographer/point_cloud_viewer - makes viewing massive point clouds easy and convenient
https://github.com/Kitware/ParaView - VTK-based Data Analysis and Visualization Application

#### RVIZ 
https://github.com/swri-robotics/mapviz - Modular ROS visualization tool for 2D data.
https://github.com/AIS-Bonn/rviz_cinematographer - Easy to use tools to create and edit trajectories for the rviz camera.
https://github.com/gareth-cross/rviz_satellite - Display internet satellite imagery in RViz
https://github.com/PickNikRobotics/rviz_visual_tools - C++ API wrapper for displaying shapes and meshes in Rviz
https://github.com/PickNikRobotics/tf_keyboard_cal - Allows manual control of a TF through the keyboard or interactive markers

## System
https://github.com/hishamhm/htop
https://github.com/Atoptool/atop
https://github.com/giampaolo/psutil
https://github.com/anderskm/gputil
https://github.com/wookayin/gpustat
https://github.com/Syllo/nvtop

## Operation System
* [Yocto](https://git.yoctoproject.org/) - Produce tools and processes that enable the creation of Linux distributions for embedded software that are independent of the underlying architecture of the embedded hardware
* [Automotive Graded Linux](https://www.automotivelinux.org/software) - is a collaborative open source project that is bringing together automakers, suppliers and technology companies to build a Linux-based, open software platform for automotive applications that can serve as the de facto industry standard
* [robot_upstart](https://github.com/clearpathrobotics/robot_upstart) - presents a suite of scripts to assist with launching background ROS processes on Ubuntu Linux PCs
* [bitbake](https://github.com/openembedded/bitbake) - is a generic task execution engine that allows shell and Python tasks to be run efficiently and in parallel while working within complex inter-task dependency constraints.
* [Jailhouse](https://github.com/siemens/jailhouse) - Jailhouse is a partitioning Hypervisor based on Linux
* [Xen](https://wiki.debian.org/Xen) - is an open-source (GPL) type-1 or baremetal hypervisor
* [QEMU](https://www.qemu.org/) - is a generic and open source machine emulator and virtualizer

### Network 
https://github.com/KimiNewt/pyshark - Python wrapper for tshark, allowing python packet parsing using wireshark dissectors
https://github.com/laixintao/pingtop - Ping multiple servers and show results in a top-like terminal UI
https://github.com/gcla/termshark - A terminal UI for tshark, inspired by Wireshark
https://github.com/raboof/nethogs - It groups bandwidth by process
https://github.com/ebroecker/canmatrix - Converting CAN Database Formats .arxml .dbc .dbf .kcd
https://github.com/osxfuse/sshfs - File system based on the SSH File Transfer Protocol
https://github.com/ApexAI/performance_test - Tool to test the performance of pub/sub based communication frameworks.
https://github.com/appneta/tcpreplay - Pcap editing and replay tools
https://github.com/esnet/iperf - A TCP, UDP, and SCTP network bandwidth measurement tool
https://github.com/linux-can/can-utils - Linux-CAN / SocketCAN user space applications
https://github.com/ros-industrial/ros_canopen - CANopen driver framework for ROS 
https://github.com/JWhitleyAStuff/decanstructor - The definitive ROS CAN analysis tool.

### Debugging and Tracing
https://github.com/khamidou/lptrace
https://github.com/facebook/pyre-check
https://github.com/brendangregg/FlameGraph
https://github.com/mikesart/gpuvis
https://github.com/google/sanitizers
https://github.com/andreasfertig/cppinsights

### Security
https://github.com/rfjakob/gocryptfs - Encrypted overlay filesystem written in Go
https://github.com/imthenachoman/How-To-Secure-A-Linux-Server - An evolving how-to guide for securing a Linux server.
https://github.com/CISOfy/lynis - Lynis - Security auditing tool for Linux, macOS, and UNIX-based systems. Assists with compliance testing (HIPAA/ISO27001/PCI DSS) and system hardening
https://github.com/WireGuard/WireGuard - WireGuard is a novel VPN that runs inside the Linux Kernel and utilizes state-of-the-art cryptography
https://github.com/ncsa/ssh-auditor - Scans for weak ssh passwords on your network
https://github.com/scipag/vulscan - Advanced vulnerability scanning with Nmap NSE
https://github.com/vulnersCom/nmap-vulners - NSE script based on Vulners.com API
https://github.com/x90skysn3k/brutespray - Automatically attempts default creds on found services.
https://github.com/fail2ban/fail2ban - Daemon to ban hosts that cause multiple authentication errors 
https://github.com/lirantal/is-website-vulnerable - Finds publicly known security vulnerabilities in a website's frontend JavaScript libraries
https://github.com/jeremylong/DependencyCheck - is a software composition analysis utility that detects publicly disclosed vulnerabilities in application dependencies
https://github.com/thebjorn/pydeps - Python Module Dependency graphs

### Safety
https://github.com/voyage/open-autonomous-safety - OAS is a fully open-source library of Voyage’s safety processes and testing procedures, designed to supplement existing safety programs at self-driving car startups across the world.
https://github.com/udacity/CarND-Functional-Safety-Project - create functional safety documents udacity project
https://github.com/stanislaw/awesome-safety-critical - List of resources about programming practices for writing safety-critical software.
https://www.automotivelinux.org/ - Automotive Grade Linux is a collaborative open source project that is bringing together automakers, suppliers and technology companies to accelerate the development and adoption of a fully open software stack for the connected car
https://github.com/boostorg/safe_numerics - Replacements to standard numeric types which throw exceptions on errors

### Real Time
https://elinux.org/Realtime_Testing_Best_Practices - This page is intended to serve as a collecting point for presentations, documents, results, links and descriptions about testing Realtime performance of Linux systems. In the first section, please upload or place links to presentations or documentsion on the subject of RT testing for linux.
https://elisa.tech/ -  Project is to make it easier for companies to build and certify Linux-based safety-critical applications – systems whose failure could result in loss of human life, significant property damage or environmental damage
https://wiki.linuxfoundation.org/realtime/documentation/start - Aim of the PREEMPT_RT kernel patch is to minimize the amount of kernel code that is non-preemptible.
https://github.com/eProsima/Fast-RTPS -  protocol, which provides publisher-subscriber communications over unreliable transports such as UDP, as defined and maintained by the Object Management Group (OMG) consortium
[spdlog](https://github.com/gabime/spdlog) - Very fast, header-only/compiled, C++ logging library
