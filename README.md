# test_ex

for use\n
~/*/test_ex$colcon build
~/*/test_ex$source ~/*/test_ex/install/testup.bash
$ros2 launch test_ex example.launch.py example:='gripper_control' use_sim_time:='true'
