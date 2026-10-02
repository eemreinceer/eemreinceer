<div align="center">

# Hi, I'm Emre İnceer 👋

### Mechatronics Engineering Student · Robotics · Embedded Systems · Computer Vision

📍 Izmir, Türkiye

</div>

I build end-to-end robotics and embedded systems spanning **mechanics, electronics, firmware, ROS 2, perception and safety**. I care not only whether a system works, but also whether its behavior is measurable, its limitations are explicit and its results are reproducible.

My main areas of interest are ROS 2-based robotics, embedded firmware, motor and sensor integration, computer vision, Edge AI and electronic system development.

---

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/eemreinceer/Robot_Arm">Robot Arm</a></h3>

<p align="center"><strong>ROS 2, vision and embedded control integration</strong></p>

An integrated robotics project built around ROS 2 Jazzy, MoveIt 2, Gazebo Harmonic and OpenCV, combining motion planning, perception, calibration and low-level control.

<strong>System scope</strong>
<ul>
<li>5-axis manipulator + 1-DOF gripper</li>
<li>MoveIt 2 motion planning and IK comparisons</li>
<li>YOLO-based object detection and camera calibration</li>
<li>Bounded UART communication through <code>ros2_control</code></li>
<li>ESP32/STM32 servo firmware and watchdog tests</li>
<li>Raspberry Pi 5 deployment and Gazebo simulation</li>
</ul>

<strong>Engineering perspective:</strong> Simulation results, commanded state and physical feedback are treated as distinct evidence classes. Measurements and known limitations are documented explicitly in the repository.

<p align="center"><a href="https://github.com/eemreinceer/Robot_Arm"><strong>Explore the project →</strong></a></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/eemreinceer/Smart_Safe">SmartSafe</a></h3>

<p align="center"><strong>Embedded access control and IoT system prototype</strong></p>

An end-to-end mechatronics project combining an ESP32-CAM, RC522 reader and solenoid lock with Firebase event synchronization, a web dashboard, a custom PCB and mechanical design.

<strong>System scope</strong>
<ul>
<li>FreeRTOS tasks and a non-blocking state machine</li>
<li>Local RFID allowlist authorization</li>
<li>Fail-closed credential and TLS configuration checks</li>
<li>Offline event queue and Firebase RTDB synchronization</li>
<li>HTML/CSS/JavaScript dashboard and role-separated database rules</li>
<li>KiCad PCB and Fusion 360 enclosure sources</li>
</ul>

<strong>Engineering perspective:</strong> The access decision is made locally on the device; the cloud layer cannot directly unlock the safe. The project is presented as an engineering prototype, not as a production-grade security product.

<p align="center"><a href="https://github.com/eemreinceer/Smart_Safe"><strong>Explore the project →</strong></a></p>

</td>
</tr>
</table>

---

## Technical focus

| Layer | Technologies and topics |
| --- | --- |
| **Robotics** | ROS 2 Jazzy, MoveIt 2, Gazebo Harmonic, `ros2_control`, TF, kinematics, calibration |
| **Embedded** | C/C++, ESP32, STM32, FreeRTOS, PlatformIO, watchdog, state machines |
| **Perception & Edge AI** | OpenCV, YOLO, camera calibration, TensorRT, Python |
| **Communication** | UART, I2C, SPI, bounded transactions, device–host protocols |
| **Electronics & Design** | KiCad, PCB design, motor/actuator interfaces, Fusion 360, SolidWorks |
| **Cloud & Web** | Firebase RTDB, JavaScript, HTML/CSS, event logging and dashboard integration |
| **Development** | Ubuntu 24.04, Git/GitHub, Bash, CI, testing and technical documentation |

---

## How I work

- I decompose systems into mechanical, power, low-level control, sensing, communication, high-level control, perception and safety layers.
- I distinguish simulation results, configuration values and physical measurements from one another.
- I retain failed experiments and document the reasoning, trade-offs and remaining risks behind engineering decisions.
- I treat timeouts, watchdogs, limits and fail-safe behavior as part of the design whenever commands reach physical hardware.
- I do not present a working prototype as a production-ready or safety-certified system.

---

## Contact

- **LinkedIn:** [linkedin.com/in/eemreinceer](https://linkedin.com/in/eemreinceer)
- **Email:** [emreinceer.dev@gmail.com](mailto:emreinceer.dev@gmail.com)
- **GitHub:** [github.com/eemreinceer](https://github.com/eemreinceer)

> I am open to internship, part-time and early-career opportunities in embedded systems, robotics and Edge AI. I would be glad to connect with R&D teams in the Izmir area.
