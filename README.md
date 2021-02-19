# Debug ROS using `VScode`

## Prerequisites
  - [VScode](https://code.visualstudio.com/)
  - [GDB](https://www.gnu.org/software/gdb/) 
  - [C/C++ extension from Microsoft for VSCode](https://github.com/microsoft/vscode-cpptools)

.     <img src="media/ros_extension.png" alt="ros_extension" width="500"/>

  - [ROS extension from Microsoft for VSCode](https://marketplace.visualstudio.com/items?itemName=ms-iot.vscode-ros)

.     <img src="media/cpp_extension.png" alt="cpp_extension" width="500"/>

  - Launch file for ROS node
 
## Create a launch.json

  - Open workplace roobt folder in VSCode 
  - Switch to ROS Extension page 

.   <img src="media/ros_extension_page.png" alt="ros_extension_page" width="500"/>

  - Click the Button on the left side bar and click `create a launch.json file` under `Run and Debug` 

.   <img src="media/create_launch_json.png" alt="create_launch_json" width="200"/>

  - Select `ROS` 

.   <img src="media/ros.png" alt="ros" width="400"/>

  - Select `ROS:Launch` 

.   <img src="media/ros_launch.png" alt="ros_launch" width="400"/>

  - Select package, for example `ipid_control` 

.   <img src="media/ros_package.png" alt="ros_package" width="400"/>   

  - Select launch file, for example `ipid_control_launch` 

.   <img src="media/ros_launch_file.png" alt="ros_launch_file" width="400"/>

  - A `launch.json` will be generated 

.   <img src="media/launch_json.png" alt="launch_json" width="600"/>

   
## Debug

### Compile
Compile the package with

```catkin_make -DCMAKE_BUILD_TYPE=Debug ```

This will set `-g` for debugging.

### A `roscore` need to be launched first. 
  - `roscore` not running
  
.   <img src="media/ros_master_not_running.png" alt="ros_master_not_running" width="500"/>

  - `roscore` is running
  
.   <img src="media/ros_master_running.png" alt="ros_master_running" width="500"/>

### Start Debuging

.   <img src="media/start_debuging.png" alt="start_debuging" width="500"/>


## Annex

Use the [editor on GitHub](https://github.com/aaifox/ros_debug/edit/gh-pages/index.md) to maintain and preview the content for website in Markdown files.

View on [GitHub Page](https://aaifox.github.io/ros_debug/)
