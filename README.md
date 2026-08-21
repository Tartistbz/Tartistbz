<div align="center">

# Tartistbz

**Robotics software · UAV telemetry · ROS 2 autonomy · open-source engineering**

I build tools and experiments that turn robot data and real hardware behavior into inspectable engineering evidence.

[![GitHub](https://img.shields.io/badge/GitHub-Tartistbz-181717?logo=github)](https://github.com/Tartistbz)
[![PX4](https://img.shields.io/badge/PX4-flight%20software-00A5D6)](https://px4.io/)
[![ROS 2](https://img.shields.io/badge/ROS%202-Humble-22314E?logo=ros)](https://docs.ros.org/en/humble/)

</div>

## Current Direction

My work sits at the intersection of **robotics software, telemetry, and autonomy**.

- **UAV systems:** PX4/ArduPilot flight-log analysis, telemetry visualization, diagnostics, and flight-control workflows.
- **Ground robotics:** ROS 2 mapping, AMCL localization, Nav2 navigation, and mission-level control validated on a real indoor mobile robot.
- **Next:** safety-aware task interfaces and agent-assisted robotics workflows, with clear boundaries between high-level intent and low-level actuation.

I am especially interested in software that can be tested on hardware, explained from its data flow, and improved from recorded evidence.

## Featured Projects

### [ROS 2 Indoor Patrol](https://github.com/Tartistbz/ros2-indoor-patrol)

Mission-level patrol executive for Nav2 on a LEAP_ROS mobile base. I implemented the ROS 2 Python mission node, YAML waypoint route, sequential `NavigateToPose` actions, bounded retries, timeout/cancellation behavior, operator services, and JSONL event logging. I also performed the map/localization integration, waypoint calibration, and real-robot validation.

**Recorded hardware run:** 8/8 indoor waypoints reached, 0 retries, 186.31 s. The repository documents the attribution boundary: the base, ESP32 firmware, vendor bringup, Nav2, AMCL, and GMapping are reused platform/open-source components.

### [Aero-Analytica](https://github.com/Tartistbz/Aero-Analytica)

Streamlit-based explorer for ArduPilot `.bin` and PX4 `.ulg` logs, with dynamic field discovery, interactive time-series plots, and optional LLM-assisted diagnostic reports. Includes architecture documentation and offline tests for the analysis pipeline.

### [UAV Insight Toolkit](https://github.com/Tartistbz/UAV-Insight-Toolkit)

Telemetry dashboard for vibration analysis, PID/rate tracking, 3D trajectory visualization, and AI-assisted reports across PX4 and ArduPilot flight logs.

## Open-Source Contributions

- [QGroundControl #14862](https://github.com/mavlink/qgroundcontrol/pull/14862) — merged documentation update for actuator troubleshooting.
- [ArduPilot wiki #7966](https://github.com/ArduPilot/ardupilot_wiki/pull/7966) — merged correction to DroneCAN pool defaults.
- [PX4 #28245](https://github.com/PX4/PX4-Autopilot/pull/28245) — documentation PR clarifying ROS 2 `VehicleCommand` routing.
- [noop #552](https://github.com/ryanbr/noop/pull/552) — merged Simplified Chinese Android localization.

## Learning and Experiments

- [Motion Planning Notes](https://github.com/Tartistbz/Motion-Planning-Notes) — search-based, sampling-based, and kinodynamic planning notes.
- Current hands-on track: Nav2 costmap/controller tuning, repeated-run evaluation, safety supervision, and moving the ROS 2 host from VMware to Raspberry Pi 4B.

## Tools I Use

`Python` · `C/C++` · `ROS 2` · `Nav2` · `PX4` · `ArduPilot` · `MAVLink` · `micro-ROS` · `pymavlink` · `pyulog` · `Streamlit` · `Plotly` · `Linux` · `Git`

## Contact

For UAV tooling, robotics software, or open-source collaboration, open an issue or reach me through [GitHub](https://github.com/Tartistbz).

<div align="center">

<img src="./profile-summary-card-output/rose_pine/0-profile-details.svg" alt="GitHub profile details" width="100%" />

</div>
