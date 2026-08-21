<div align="center">

# Tartistbz

**Robotics software · UAV telemetry · ROS 2 autonomy · open-source engineering**

</div>

<table>
  <tr>
    <td valign="top" width="220">
      <img src="./assets/first.jpg" width="200" alt="Tartistbz profile avatar" />
    </td>
    <td valign="top">

I build robotics software that turns sensor data, flight logs, and real hardware behavior into inspectable engineering evidence.

My current path connects three areas:

- **UAV systems:** PX4/ArduPilot telemetry, flight-log analysis, diagnostics, and flight-control workflows.
- **Ground robotics:** ROS 2 mapping, AMCL localization, Nav2 navigation, and mission-level control on a real indoor mobile robot.
- **Agent infrastructure:** practical operator tools and future task interfaces with a clear boundary between high-level intent and low-level actuation.

    </td>
  </tr>
</table>

## Featured Projects

### [ROS 2 Indoor Patrol](https://github.com/Tartistbz/ros2-indoor-patrol)

Mission-level patrol executive for Nav2 on a LEAP_ROS mobile base. I implemented the ROS 2 Python mission node, YAML waypoint routes, sequential `NavigateToPose` actions, bounded retries, timeout/cancellation behavior, operator services, and JSONL event logging. I also performed mapping/localization integration, waypoint calibration, and real-robot validation.

**Recorded hardware run:** 8/8 indoor waypoints reached, 0 retries, 186.31 s. The repository clearly separates my mission-layer work from the reused base, ESP32 firmware, vendor bringup, Nav2, AMCL, and GMapping components.

### [Aero-Analytica](https://github.com/Tartistbz/Aero-Analytica)

Streamlit-based explorer for ArduPilot `.bin` and PX4 `.ulg` logs, with dynamic field discovery, interactive time-series plots, and optional LLM-assisted diagnostic reports. Includes architecture documentation and offline tests for the analysis pipeline.

### [UAV Insight Toolkit](https://github.com/Tartistbz/UAV-Insight-Toolkit)

Telemetry dashboard for vibration analysis, PID/rate tracking, 3D trajectory visualization, and AI-assisted reports across PX4 and ArduPilot flight logs.

### [BossConsole](https://github.com/risa-labs-inc/BossConsole)

An open-source, multi-platform operator console for AI coding agents. My contribution fixed a crash path by publishing contained reports atomically: [PR #189](https://github.com/risa-labs-inc/BossConsole/pull/189) was merged.

## Open-Source Contributions

I currently have **8 upstream contribution PRs represented on GitHub: 5 merged, 2 open, and 1 closed without merge**.

### Merged

- [ArduPilot wiki #7973](https://github.com/ArduPilot/ardupilot_wiki/pull/7973) — archived legacy ODroid companion-computer pages.
- [BossConsole #189](https://github.com/risa-labs-inc/BossConsole/pull/189) — fixed atomic publication of contained crash reports.
- [QGroundControl #14862](https://github.com/mavlink/qgroundcontrol/pull/14862) — added troubleshooting guidance for the missing Actuators tab.
- [ArduPilot wiki #7966](https://github.com/ArduPilot/ardupilot_wiki/pull/7966) — corrected DroneCAN pool defaults.
- [noop #552](https://github.com/ryanbr/noop/pull/552) — added Simplified Chinese Android localization.

### Open

- [PX4/px4_ros_com #234](https://github.com/PX4/px4_ros_com/pull/234) — fix `Covariance3d` frame transformation.
- [PX4-Autopilot #28245](https://github.com/PX4/PX4-Autopilot/pull/28245) — clarify ROS 2 `VehicleCommand` routing.

### Closed, Not Merged

- [PX4-GPSDrivers #227](https://github.com/PX4/PX4-GPSDrivers/pull/227) — convert SBF heading covariance to accuracy.

## Repositories and Learning

- [Motion Planning Notes](https://github.com/Tartistbz/Motion-Planning-Notes) — search-based, sampling-based, and kinodynamic planning for mobile robots.
- [PX4-GPSDrivers](https://github.com/Tartistbz/PX4-GPSDrivers) — contribution workspace for platform-independent GPS drivers.
- [px4_ros_com](https://github.com/Tartistbz/px4_ros_com) — PX4 and ROS 2 integration work.
- [PX4-Autopilot](https://github.com/Tartistbz/PX4-Autopilot) and [ArduPilot wiki](https://github.com/Tartistbz/ardupilot_wiki) — upstream contribution workspaces.

## Current Engineering Track

Nav2 costmap and controller tuning, repeated-run evaluation, safety supervision, onboard deployment on Raspberry Pi 4B, and constrained agent interfaces for robot tasks.

## Tools I Use

`Python` · `C/C++` · `ROS 2` · `Nav2` · `PX4` · `ArduPilot` · `MAVLink` · `micro-ROS` · `pymavlink` · `pyulog` · `Streamlit` · `Plotly` · `Linux` · `Git`

## Contact

For UAV tooling, robotics software, or open-source collaboration, open an issue or reach me through [GitHub](https://github.com/Tartistbz).

<div align="center">

<img src="./profile-summary-card-output/rose_pine/0-profile-details.svg" alt="GitHub profile details" width="100%" />

</div>

<table align="center">
  <tr>
    <td width="50%">
      <img src="./profile-summary-card-output/rose_pine/1-repos-per-language.svg" alt="Top languages by repository" width="100%" />
    </td>
    <td width="50%">
      <img src="./profile-summary-card-output/rose_pine/2-most-commit-language.svg" alt="Top languages by commit" width="100%" />
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="./profile-summary-card-output/rose_pine/3-stats.svg" alt="GitHub statistics" width="100%" />
    </td>
    <td width="50%">
      <img src="./profile-summary-card-output/rose_pine/4-productive-time.svg" alt="Productive time" width="100%" />
    </td>
  </tr>
</table>
