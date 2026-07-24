<div align="center">

# 温俊勇 | Embedded Systems & Robotics

### 嵌入式软件 · 机器人控制 · Linux 设备端 · AIoT

把感知、通信、控制与执行机构连接成可运行、可联调、可验证的完整系统。

[![GitHub](https://img.shields.io/badge/GitHub-wenjunyong666-181717?style=for-the-badge&logo=github)](https://github.com/wenjunyong666)
[![Portfolio](https://img.shields.io/badge/在线作品集-查看项目-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](http://106.55.62.122/site/)
[![Email](https://img.shields.io/badge/Email-3245056131%40qq.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:3245056131@qq.com)

</div>

---

## About Me

- 广东工业大学电子信息专业本科生，目标岗位为嵌入式软件、机器人控制、Linux 设备端与 AIoT 实习生。
- 关注真实设备上的完整工程闭环：传感器输入、通信协议、任务调度、控制算法、执行机构与上位机可视化。
- 熟悉 STM32、ESP32、PSoC、FreeRTOS、ROS2、Linux 设备端以及 CAN / UART / MQTT 等链路联调。
- 善于借助 Codex、Claude Code 等 AI 工具进行架构梳理、代码实现、测试验证和工程文档沉淀。

## Featured Projects

<div align="center">

[![医疗康复机械臂](https://img.shields.io/badge/01-医疗康复机械臂-0B7285?style=for-the-badge)](https://github.com/HalloYang06/PSOC_E84_robot)
[![工创物流小车](https://img.shields.io/badge/02-工创物流小车-2F9E44?style=for-the-badge)](https://github.com/wenjunyong666/wuliuxiaoche)
[![AI 合作平台](https://img.shields.io/badge/03-AI_合作平台-7048E8?style=for-the-badge)](https://github.com/wenjunyong666/ai-)

[![电赛自动瞄准](https://img.shields.io/badge/04-电赛自动瞄准-E8590C?style=for-the-badge)](https://github.com/wenjunyong666/25diansai)
[![智能加湿器](https://img.shields.io/badge/05-物联网智能加湿器-1971C2?style=for-the-badge)](https://github.com/wenjunyong666/humidifier_freertos)
[![全景会议摄像头](https://img.shields.io/badge/06-全景会议摄像头-C2255C?style=for-the-badge)](https://github.com/wenjunyong666/quanjinhuiyishexiangtou)

</div>

| 项目 | 核心技术 | 我的工作 |
|---|---|---|
| [具身智能医疗康复机械臂及外骨骼](https://github.com/HalloYang06/PSOC_E84_robot) | ROS2、CAN、PSoC、NanoPi、MuJoCo、VLA | 参与分层系统架构设计，梳理 `JointTrajectory -> NanoPi -> M33 -> Motor` 真实运动安全链路；建设 shadow simulation、状态桥接和上层指令门控。 |
| [工创物流小车](https://github.com/wenjunyong666/wuliuxiaoche) | STM32F750、FreeRTOS、Jetson Nano、OpenCV、IMU、UART/DMA | 负责整车控制与联调；实现麦克纳姆轮运动解算、IMU yaw PID 修正、升降与舵机机构控制，以及视觉坐标到小车对位动作的闭环。 |
| [AI 合作平台](https://github.com/wenjunyong666/ai-) | 多 Agent、任务编排、Runner、Web 平台、服务器部署 | 独立设计面向个人与小团队的 AI 工程协作平台；构建“项目 -> 工位 -> NPC -> 线程 -> Runner”模型、工作台页面、日志回执和安全执行边界。 |
| [2025 电赛 E 题自动瞄准装置](https://github.com/wenjunyong666/25diansai) | MSPM0、MaixCam、PID、IMU、编码器、VOFA+ | 担任运动控制负责人；完成视觉坐标到二维舵机云台的双轴 PID、小车多环控制、远程调参与现场联调，获广东省二等奖。 |
| [物联网智能加湿器](https://github.com/wenjunyong666/humidifier_freertos) | ESP32-S3、FreeRTOS、MQTTS、OneNet、OLED | 负责设备端与云端链路；组织双核任务，实现物模型上报与控制下发、自动/手动模式、目标湿度回差控制及本地交互。 |
| [全景会议摄像头](https://github.com/wenjunyong666/quanjinhuiyishexiangtou) | TangMega 138K Pro、OV5640、UDP-RGMII、OpenCV、SIFT | 负责多摄像头畸变校准、视角对齐与拼接融合；参与 FPGA 图传联调并完成 PC 端三路画面重建、处理与显示验证。 |

## Engineering Focus

```text
Sensor / Vision
      |
      v
Communication  --->  Task Scheduling  --->  Closed-loop Control  --->  Actuator
CAN · UART · MQTT     FreeRTOS · ROS2       PID · State Machine       Motor · Servo
```

- **嵌入式控制：** 外设驱动、FreeRTOS 任务组织、状态机、闭环控制与执行机构联调
- **机器人系统：** ROS2、CAN 电机链路、底盘运动、机械臂安全边界与仿真验证
- **视觉与图像：** OpenCV、YOLO、SIFT、相机标定、畸变校准、多摄像头拼接
- **设备与云端：** Linux 设备端、TCP / UDP、MQTT、OneNet、远程状态监控
- **工程协作：** Git、测试验证、架构文档、AI 辅助开发与多 Agent 工作流

## Tech Stack

<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-8A2BE2?style=flat-square)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-2C3E50?style=flat-square)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

## Honors

- 2025 睿抗机器人开发者大赛视觉创新赛道全国一等奖，第二负责人
- 2025 全国大学生电子设计大赛广东省二等奖，队长
- 2026 大唐杯广东省三等奖

## GitHub Activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=wenjunyong666&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=transparent)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=wenjunyong666&layout=compact&hide_border=true&theme=transparent&langs_count=8)

</div>

> GitHub 语言统计只反映公开仓库的代码占比，并不代表实际熟练程度。

## Contact

- GitHub: [github.com/wenjunyong666](https://github.com/wenjunyong666)
- 在线作品集: [106.55.62.122/site](http://106.55.62.122/site/)
- Email: [3245056131@qq.com](mailto:3245056131@qq.com)

<div align="center">

从需求拆解到设备联调，从控制闭环到可视化交付。

</div>
