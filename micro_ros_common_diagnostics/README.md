General information about this repository, including legal information, build instructions and known issues/limitations, can be found in the [README](../README.md) of the repository root.

# The micro-ROS common diagnostics package

micro-ROS diagnostic updater is a [ROS 2](http://www.ros2.org/) package that provides common microcontroller-specific diagnostic functions and monitors for micro-ROS.

## Purpose of the Project

This software is not ready for production use. It has neither been developed nor
tested for a specific use case. However, the license conditions of the
applicable Open Source licenses allow you to adapt the software to your needs.
Before using it in a safety relevant setting, make sure that the software
fulfills your requirements and adjust it according to any applicable safety
standards, e.g., ISO 26262.

## How to Build, Test, Install, and Use

After you cloned this repository into your ROS 2 workspace folder, you may build and install it using colcon:
$ `colcon build --packages-select micro_ros_common_diagnostics`

## License

The micro-ROS diagnostics framework packages are open-sourced under the Apache-2.0 license. See the [../LICENSE](LICENSE) file for details.

For a list of other open-source components included in ROS 2 micro_ros_diagnostics,
see the file [../3rd-party-licenses.txt](3rd-party-licenses.txt).

## Acknowledgments

This activity has received funding from the European Research Council (ERC) under the European Union's Horizon 2020 research and innovation programme (grant agreement n° 780785).
