<div align="center">

# Tartistbz

**Robotics software · UAV telemetry · ROS 2 autonomy · AI-assisted engineering**

</div>

<table>
  <tr>
    <td valign="top" width="220">
      <img src="./assets/first.jpg" width="200" alt="Tartistbz profile avatar" />
    </td>
    <td valign="top">

I build robotics software that turns sensor data, flight logs, and real hardware behavior into inspectable engineering evidence.

My current work connects three practical areas:

- **UAV systems:** PX4 and ArduPilot telemetry, flight-log analysis, diagnostics, and ROS 2 integration.
- **Ground robotics:** ROS 2 mapping, AMCL localization, Nav2 navigation, and mission-level control on a real indoor mobile robot.
- **AI-assisted engineering:** reproducible evaluation and repair workflows for robotics and coding tasks.

    </td>
  </tr>
</table>

## Featured Projects

### [ROS 2 Indoor Patrol](https://github.com/Tartistbz/ros2-indoor-patrol)

Mission-level patrol and exploration overlay for Nav2 on a LEAP_ROS mobile base. I implemented the ROS 2 mission node, YAML waypoint routes, sequential `NavigateToPose` actions, bounded retries, timeout and cancellation behavior, operator services, JSONL event logging, and the experimental SE(2) B-spline controller.

The repository records one reviewed hardware-in-the-loop run: **8/8 indoor waypoints reached, 0 retries, 186.31 s**. The README documents the boundary between my mission-layer work and reused base, vendor bringup, Nav2, AMCL, SLAM, and firmware components.

### [Aero-Analytica](https://github.com/Tartistbz/Aero-Analytica)

A Streamlit-based flight-log analysis workspace for ArduPilot `.bin` and PX4 `.ulg` files. It uses `pymavlink` and `pyulog` to discover the messages, topics, and fields actually present in each log, then aligns selected signals into interactive Plotly time-series views with dual axes, range controls, and flight-mode context.

Users can select fields manually or ask an LLM to recommend relevant signals. Its two-stage `Dispatcher` / `Analyst` workflow generates diagnostic reports from field metadata, statistical summaries, and sampled time-series data, while raw logs remain local.

Recent work adds a RepoPilot evaluation harness, reproducible robotics fixtures, guided code-repair workflows, and Windows portable packaging. The repository also includes architecture documentation and 36 offline unit tests.

### [UAV Insight Toolkit](https://github.com/Tartistbz/UAV-Insight-Toolkit)

Telemetry dashboard for vibration analysis, PID/rate tracking, 3D trajectory visualization, and AI-assisted reports across PX4 and ArduPilot flight logs.

## Open-Source Contributions

As of 2026-08-26, I have **13 PRs targeting external repositories: 5 merged, 7 open, and 1 closed without merge**.

### Merged

- [ArduPilot wiki #7973](https://github.com/ArduPilot/ardupilot_wiki/pull/7973) - archived legacy ODroid companion-computer pages.
- [BossConsole #189](https://github.com/risa-labs-inc/BossConsole/pull/189) - fixed atomic publication of contained crash reports.
- [QGroundControl #14862](https://github.com/mavlink/qgroundcontrol/pull/14862) - added troubleshooting guidance for the missing Actuators tab.
- [ArduPilot wiki #7966](https://github.com/ArduPilot/ardupilot_wiki/pull/7966) - corrected DroneCAN pool defaults.
- [noop #552](https://github.com/ryanbr/noop/pull/552) - added Simplified Chinese Android localization.

### Open

- [PX4-Autopilot #28245](https://github.com/PX4/PX4-Autopilot/pull/28245) - clarified ROS 2 `VehicleCommand` routing.
- [PX4-Autopilot #28338](https://github.com/PX4/PX4-Autopilot/pull/28338) - aligned SITL and hardware UXRCE-DDS namespace conventions.
- [PX4-Autopilot #28339](https://github.com/PX4/PX4-Autopilot/pull/28339) - restored Gazebo fallback targets when dependencies are unavailable.
- [PX4/px4_ros_com #234](https://github.com/PX4/px4_ros_com/pull/234) - fixed `Covariance3d` frame transformation and added regression coverage.
- [DeepSeek-Reasonix #9282](https://github.com/esengine/DeepSeek-Reasonix/pull/9282) - added per-model tool capability configuration.
- [DeepSeek-Reasonix #9283](https://github.com/esengine/DeepSeek-Reasonix/pull/9283) - allowed Git worktree metadata writes in the sandbox.
- [DeepSeek-Reasonix #9284](https://github.com/esengine/DeepSeek-Reasonix/pull/9284) - documented file-grained write paths and added regression coverage.

### Closed, Not Merged

- [PX4-GPSDrivers #227](https://github.com/PX4/PX4-GPSDrivers/pull/227) - converted SBF heading covariance to accuracy.

## Learning

- [Motion Planning Notes](https://github.com/Tartistbz/Motion-Planning-Notes) - search-based, sampling-based, and kinodynamic planning for mobile robots.

## Current Engineering Track

Nav2 controller and costmap tuning, online mapping and frontier exploration, repeated-run evaluation, Raspberry Pi 4B deployment, PX4/ROS 2 integration, and constrained interfaces for agent-assisted robot tasks.

## Tools I Use

`Python` · `C/C++` · `ROS 2` · `Nav2` · `PX4` · `ArduPilot` · `MAVLink` · `micro-ROS` · `pymavlink` · `pyulog` · `Streamlit` · `Plotly` · `Linux` · `Git`

## Contact

For robotics software, UAV tooling, or open-source collaboration, open an issue or reach me through [GitHub](https://github.com/Tartistbz).

## GitHub Stats

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
