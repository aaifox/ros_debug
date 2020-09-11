## Debug ROS using `VScode`

### Prerequisites
  - [VScode](https://code.visualstudio.com/)
  - [GDB](https://www.gnu.org/software/gdb/) 
  - [C/C++ extension from Microsoft for VSCode](https://github.com/microsoft/vscode-cpptools)
    * <img src="media/ros_extension.png" alt="ros_extension" width="500"/>
  - [ROS extension from Microsoft for VSCode](https://marketplace.visualstudio.com/items?itemName=ms-iot.vscode-ros)
    * <img src="media/cpp_extension.png" alt="cpp_extension" width="500"/>
  - Launch file for ROS node
 
### Create a launch.json
  1. Open workplace roobt folder in VSCode
  2. Switch to ROS Extension page
 
*  <img src="media/ros_extension_page.png" alt="ros_extension_page" width="500"/>

  3. Click the Button on the left side bar and click `create a launch.json file` under `Run and Debug`
  
*  <img src="media/create_launch_json.png" alt="create_launch_json" width="200"/>
    
  4. Select `ROS`
  
*  <img src="media/ros.png" alt="ros" width="400"/>
  
  5. Select `ROS:Launch`
    
*  <img src="media/ros_launch.png" alt="ros_launch" width="400"/>

  6. Select package for example `ipid_control`
    
*  <img src="media/ros_package.png" alt="ros_package" width="400"/>    
  
  7. Select launch file, for example `ipid_control_launch`
    
*  <img src="media/ros_launch_file.png" alt="ros_launch_file" width="400"/>
  
  8. A `launch.json` will be generated
    
*  <img src="media/launch_json.png" alt="launch_json" width="400"/>
    
### Debug


### Annex

Use the [editor on GitHub](https://github.com/aaifox/ros_debug/edit/gh-pages/index.md) to maintain and preview the content for website in Markdown files.

View on [GitHub Page](https://aaifox.github.io/ros_debug/)
