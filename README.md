<div align="center">

# Merhaba, ben Emre İnceer 👋

### Mekatronik Mühendisliği Öğrencisi · Robotics · Embedded Systems · Computer Vision

📍 İzmir, Türkiye

</div>

Robotik ve gömülü sistemlerde; **mekanik, elektronik, firmware, ROS 2, algılama ve güvenlik** katmanlarını birlikte ele alan uçtan uca projeler geliştiriyorum. Bir sistemin yalnızca çalışmasına değil, davranışının ölçülebilir, sınırlarının açık ve sonuçlarının tekrar üretilebilir olmasına odaklanıyorum.

Başlıca çalışma alanlarım; ROS 2 tabanlı robotik sistemler, embedded firmware, motor ve sensör entegrasyonu, computer vision, Edge AI ve elektronik sistem geliştirme.

---

## Öne çıkan projeler

<table>
<tr>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/eemreinceer/Robot_Arm">Robot Arm</a></h3>

<p align="center"><strong>ROS 2, vision ve embedded control entegrasyonu</strong></p>

ROS 2 Jazzy, MoveIt 2, Gazebo Harmonic ve OpenCV üzerine kurulu; planlama, perception, calibration ve low-level control katmanlarını bir araya getiren robotik sistem projesi.

<strong>Sistem kapsamı</strong>
<ul>
<li>5-axis manipulator + 1-DOF gripper</li>
<li>MoveIt 2 motion planning ve IK karşılaştırmaları</li>
<li>YOLO tabanlı object detection ve camera calibration</li>
<li><code>ros2_control</code> üzerinden bounded UART communication</li>
<li>ESP32/STM32 servo firmware ve watchdog testleri</li>
<li>Raspberry Pi 5 deployment ve Gazebo simulation</li>
</ul>

<strong>Mühendislik yaklaşımı:</strong> Simulation, command state ve physical feedback aynı kanıt sınıfı olarak değerlendirilmez; ölçümler ve mevcut limitler repoda açıkça belgelenir.

<p align="center"><a href="https://github.com/eemreinceer/Robot_Arm"><strong>Projeyi incele →</strong></a></p>

</td>
<td width="50%" valign="top">

<h3 align="center"><a href="https://github.com/eemreinceer/Smart_Safe">SmartSafe</a></h3>

<p align="center"><strong>Embedded access control ve IoT sistem prototipi</strong></p>

ESP32-CAM, RC522 ve solenoid lock altyapısını; Firebase tabanlı event synchronization, web dashboard, custom PCB ve mekanik tasarımla birleştiren uçtan uca mekatronik projesi.

<strong>Sistem kapsamı</strong>
<ul>
<li>FreeRTOS görevleri ve non-blocking state machine</li>
<li>Local RFID allowlist authorization</li>
<li>Fail-closed credential ve TLS configuration kontrolleri</li>
<li>Offline event queue ve Firebase RTDB synchronization</li>
<li>HTML/CSS/JavaScript dashboard ve role-separated database rules</li>
<li>KiCad PCB ve Fusion 360 enclosure kaynakları</li>
</ul>

<strong>Mühendislik yaklaşımı:</strong> Unlock kararı cihaz üzerinde yerel olarak verilir; cloud katmanı kilidi doğrudan açmaz. Proje bir engineering prototype olarak sunulur, production security ürünü olarak değil.

<p align="center"><a href="https://github.com/eemreinceer/Smart_Safe"><strong>Projeyi incele →</strong></a></p>

</td>
</tr>
</table>

---

## Teknik odak

| Katman | Kullandığım teknolojiler ve konular |
| --- | --- |
| **Robotics** | ROS 2 Jazzy, MoveIt 2, Gazebo Harmonic, `ros2_control`, TF, kinematics, calibration |
| **Embedded** | C/C++, ESP32, STM32, FreeRTOS, PlatformIO, watchdog, state machines |
| **Perception & Edge AI** | OpenCV, YOLO, camera calibration, TensorRT, Python |
| **Communication** | UART, I2C, SPI, bounded transactions, device–host protocols |
| **Electronics & Design** | KiCad, PCB design, motor/actuator interfaces, Fusion 360, SolidWorks |
| **Cloud & Web** | Firebase RTDB, JavaScript, HTML/CSS, event logging ve dashboard integration |
| **Development** | Ubuntu 24.04, Git/GitHub, Bash, CI, test ve teknik dokümantasyon |

---

## Nasıl çalışıyorum?

- Sistemi mekanik, güç, low-level control, sensing, communication, high-level control, perception ve safety katmanlarına ayırırım.
- Simulation sonucu, configuration değeri ve fiziksel ölçümü birbirinden ayırırım.
- Başarısız denemeleri saklar; kararların nedenlerini, trade-off'ları ve kalan riskleri belgelerim.
- Donanıma giden komutlarda timeout, watchdog, limit ve fail-safe davranışlarını tasarımın parçası olarak ele alırım.
- Çalışan prototipi production-ready veya safety-certified bir sistem gibi sunmam.

---

## İletişim

- **LinkedIn:** [linkedin.com/in/eemreinceer](https://linkedin.com/in/eemreinceer)
- **Email:** [emreinceer.dev@gmail.com](mailto:emreinceer.dev@gmail.com)
- **GitHub:** [github.com/eemreinceer](https://github.com/eemreinceer)

> Gömülü sistemler, robotik ve Edge AI alanlarında staj, aday mühendislik ve part-time fırsatlara açığım. İzmir bölgesindeki Ar-Ge ekipleriyle iletişime geçmekten memnuniyet duyarım.
