# robosoccer_firmware
Sensor interfacing: Reads IMU, force sensors, encoders

### Publishes
* `PoseStamped`: `/robot_pose`: Position of robot

### Subscribes to
* `PoseStamped`: `/ball_pose`: Position of ball
* `Imu`: `/imu/data`: IMU reading from robot