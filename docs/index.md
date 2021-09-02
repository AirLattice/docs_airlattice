# ROS node list

* /carla_ego_vehicle_ego_vehicle
* /carla_manual_control_ego_vehicle
* /carla_ros_bridge
* /goal_relay
* /initialpose_relay
* /rosout

## Node [/carla_ego_vehicle_ego_vehicle]

Publications
* /rosout [rosgraph_msgs/Log]

Subscriptions
* /carla/ego_vehicle/initialpose [unknown type]
* /clock [rosgraph_msgs/Clock]

Services
* /carla_ego_vehicle_ego_vehicle/get_loggers
* /carla_ego_vehicle_ego_vehicle/set_logger_level

## Node [/carla_manual_control_ego_vehicle]
Publications
* /carla/ego_vehicle/enable_autopilot [std_msgs/Bool]
* /carla/ego_vehicle/vehicle_control_cmd_manual [carla_msgs/CarlaEgoVehicleControl]
* /carla/ego_vehicle/vehicle_control_manual_override [std_msgs/Bool]
* /rosout [rosgraph_msgs/Log]

Subscriptions
* /carla/ego_vehicle/camera/rgb/view/image_color [sensor_msgs/Image]
* /carla/ego_vehicle/collision [unknown type]
* /carla/ego_vehicle/gnss/gnss1/fix [sensor_msgs/NavSatFix]
* /carla/ego_vehicle/lane_invasion [unknown type]
* /carla/ego_vehicle/vehicle_control_manual_override [std_msgs/Bool]
* /carla/ego_vehicle/vehicle_info [carla_msgs/CarlaEgoVehicleInfo]
* /carla/ego_vehicle/vehicle_status [carla_msgs/CarlaEgoVehicleStatus]
* /carla/status [carla_msgs/CarlaStatus]
* /clock [rosgraph_msgs/Clock]
* /tf [tf2_msgs/TFMessage]
* /tf_static [unknown type]

Services
* /carla_manual_control_ego_vehicle/get_loggers
* /carla_manual_control_ego_vehicle/set_logger_level

## Node [/carla_ros_bridge]
Publications
* /carla/actor_list [carla_msgs/CarlaActorList]
* /carla/ego_vehicle/camera/rgb/front/camera_info [sensor_msgs/CameraInfo]
* /carla/ego_vehicle/camera/rgb/front/image_color [sensor_msgs/Image]
* /carla/ego_vehicle/camera/rgb/view/camera_info [sensor_msgs/CameraInfo]
* /carla/ego_vehicle/camera/rgb/view/image_color [sensor_msgs/Image]
* /carla/ego_vehicle/gnss/gnss1/fix [sensor_msgs/NavSatFix]
* /carla/ego_vehicle/imu [sensor_msgs/Imu]
* /carla/ego_vehicle/lidar/lidar1/point_cloud [sensor_msgs/PointCloud2]
* /carla/ego_vehicle/objects [derived_object_msgs/ObjectArray]
* /carla/ego_vehicle/odometry [nav_msgs/Odometry]
* /carla/ego_vehicle/radar/front/radar [ainstein_radar_msgs/RadarTargetArray]
* /carla/ego_vehicle/vehicle_info [carla_msgs/CarlaEgoVehicleInfo]
* /carla/ego_vehicle/vehicle_status [carla_msgs/CarlaEgoVehicleStatus]
* /carla/marker [visualization_msgs/Marker]
* /carla/objects [derived_object_msgs/ObjectArray]
* /carla/status [carla_msgs/CarlaStatus]
* /carla/traffic_lights [carla_msgs/CarlaTrafficLightStatusList]
* /carla/world_info [carla_msgs/CarlaWorldInfo]
* /clock [rosgraph_msgs/Clock]
* /rosout [rosgraph_msgs/Log]
 */tf [tf2_msgs/TFMessage]

Subscriptions
* /carla/debug_marker [unknown type]
* /carla/ego_vehicle/enable_autopilot [std_msgs/Bool]
* /carla/ego_vehicle/twist_cmd [unknown type]
* /carla/ego_vehicle/vehicle_control_cmd [unknown type]
* /carla/ego_vehicle/vehicle_control_cmd_manual [carla_msgs/CarlaEgoVehicleControl]
* /carla/ego_vehicle/vehicle_control_manual_override [std_msgs/Bool]
* /clock [rosgraph_msgs/Clock]

Services
* /carla_ros_bridge/get_loggers
* /carla_ros_bridge/set_logger_level

## Node [/goal_relay]
Publications
* /rosout [rosgraph_msgs/Log]

Subscriptions
* /clock [rosgraph_msgs/Clock]
* /move_base_simple/goal [unknown type]

Services
* /goal_relay/get_loggers
* /goal_relay/set_logger_level

## Node [/initialpose_relay]
Publications
* /rosout [rosgraph_msgs/Log]

Subscriptions
* /clock [rosgraph_msgs/Clock]
* /initialpose [unknown type]

Services
* /initialpose_relay/get_loggers
* /initialpose_relay/set_logger_level

## Node [/rosout]
Publications
* /rosout_agg [rosgraph_msgs/Log]

Subscriptions
* /clock [rosgraph_msgs/Clock]
* /rosout [rosgraph_msgs/Log]

Services
* /rosout/get_loggers
* /rosout/set_logger_level