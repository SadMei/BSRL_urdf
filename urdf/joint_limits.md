# Humanoid Robot Joint Limits

| 对称部位 (Symmetric Part) | 关节名称 (Joint Name) | 关节类型 (Type) | 下限位 (Lower, °) | 上限位 (Upper, °) | (参考原弧度 rad) |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **Hip Yaw<br>(髋关节 偏航)** | `joint_left_hip_yaw` <br> `joint_right_hip_yaw` | revolute <br> revolute | `-34.38°` <br> `-11.46°` | `11.46°` <br> `34.38°` | (-0.6 ~ 0.2) <br> (-0.2 ~ 0.6) |
| **Hip Roll<br>(髋关节 侧倾)** | `joint_left_hip_roll` <br> `joint_right_hip_roll` | revolute <br> revolute | `-17.81°` <br> `-17.81°` | `17.81°` <br> `17.81°` | (-0.3108 ~ 0.3108) <br> (-0.3108 ~ 0.3108) |
| **Hip Pitch<br>(髋关节 俯仰)** | `joint_left_hip_pitch` <br> `joint_right_hip_pitch` | revolute <br> revolute | `-10.00°` <br> `-10.00°` | `85.94°` <br> `85.94°` | (-0.1745 ~ 1.5) <br> (-0.1745 ~ 1.5) |
| **Knee Pitch<br>(膝关节 俯仰)** | `joint_left_knee_pitch` <br> `joint_right_knee_pitch` | revolute <br> revolute | `-149.94°` <br> `0.00°` | `0.00°` <br> `149.94°` | (-2.617 ~ 0) <br> (0 ~ 2.617) |
| **Ankle Pitch<br>(踝关节 俯仰)** | `joint_left_ankle_pitch` <br> `joint_right_ankle_pitch`| revolute <br> revolute | `-40.00°` <br> `-40.00°` | `40.00°` <br> `40.00°` | (-0.6981 ~ 0.6981) <br> (-0.6981 ~ 0.6981) |
| **Ankle Roll<br>(踝关节 侧倾)** | `joint_left_ankle_roll` <br> `joint_right_ankle_roll` | revolute <br> revolute | `-30.00°` <br> `-30.00°` | `30.00°` <br> `30.00°` | (-0.5236 ~ 0.5236) <br> (-0.5236 ~ 0.5236) |
