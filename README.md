# ROS2 GDB

This package demonstrates the usage of gdb in ROS2.

## Steps

- Ensure you compile with `colcon build --cmake-args -DCMAKE_BUILD_TYPE=RelWithDebInfo`
- Update your node with `prefix=['gdbserver localhost:3000'],` or `prefix=["xterm -fa 'Monospace' -fs 14 -e gdb -ex run --args"],`

## Reference
- https://juraph.com/miscellaneous/ros2_and_gdb/
