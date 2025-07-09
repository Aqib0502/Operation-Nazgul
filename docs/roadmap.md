# Drone Autonomy & Robotics Project Roadmap with Cost Estimates

This roadmap outlines the key milestones and learning goals aligned with building a PX4 + ROS2 autonomous drone, including budget estimates for hardware and software components.

---

## Phase 0: Skill Building (Weeks 1-8)

**Goal:** Complete foundational programming courses to prepare for firmware and autonomy development.

- Courses:
  - C Programming (Basics + Embedded)  
  - C++ Fundamentals + OOP Concepts  
  - Python OOP & ROS2 Basics  
- Schedule: ~2 hours/day, 6 days/week → ~115 hours total  
- Leeway: 1-2 weeks for review and practice  
- Outcome: Write basic drone control algorithms in C/C++ and Python  
- **Cost:** Udemy courses (~$100 total) or free alternatives  

---

## Phase 1: Project Setup & Hardware (Weeks 9-11)

**Goal:** Assemble hardware and prepare software environment.

- Hardware:  
  - Tarot 680 Pro frame (carbon fiber) - ~$200  
  - T-Motor 2216 900KV motors (x4) - ~$300  
  - Pixhawk 6X flight controller - ~$400  
  - Raspberry Pi 4B 8GB + accessories - ~$100  
  - RTK GPS module - ~$350  
  - LiDAR sensor (e.g., RPLidar A1 or similar) - ~$100-$150  
  - ESCs (30A) and battery (4S 5000mAh LiPo) - ~$200  
  - Miscellaneous (cables, connectors, mounts) - ~$50  
- Software: PX4, ROS2 (free/open-source)  
- Outcome: Ready-to-fly drone hardware and dev environment  
- **Estimated Hardware Cost:** ~$1,700  

---

## Phase 2: Firmware & Basic Autonomy (Weeks 12-16)

**Goal:** Implement PX4 configuration and basic autonomous control.

- Tasks:  
  - Flash and configure PX4 on Pixhawk  
  - Tune PID controllers for stability  
  - Develop ROS2 nodes for waypoint navigation in Python/C++  
  - PX4 SITL + Gazebo simulation setup  
- Tools: Linux PC or Raspberry Pi (already included)  
- Outcome: Drone performs autonomous missions in simulation  
- **Cost:** Mostly time/software, no extra hardware cost  

---

## Phase 3: Advanced Autonomy & Sensing (Weeks 17-21)

**Goal:** Add obstacle avoidance and computer vision.

- Tasks:  
  - Integrate LiDAR with ROS2 octomap for obstacle avoidance  
  - Develop computer vision node (OpenCV)  
  - Implement GPS-denial fallback (SLAM)  
  - Test in Gazebo + indoor flights  
- Possible additional cost:  
  - Higher-end LiDAR or camera upgrades - ~$200 (optional)  
- Outcome: Safe autonomous navigation with obstacle avoidance  

---

## Phase 4: Field Testing & Iteration (Weeks 22-26)

**Goal:** Outdoor flight tests and optimization.

- Tasks:  
  - Manual and autonomous flight testing  
  - Battery endurance and failsafe tuning  
  - Data logging and analysis  
- Possible replacements/repairs: batteries, props - ~$100  
- Outcome: Reliable outdoor autonomous flights  

---

## Phase 5: Documentation & Portfolio (Weeks 27-28)

**Goal:** Finalize project documentation and portfolio.

- Tasks:  
  - Complete README, logs, and presentations  
  - Record video demos  
- Cost: Minimal, possible video editing software (~$0-$50)  

---

## Summary of Estimated Costs

| Phase                | Estimated Cost (USD)     |
|----------------------|-------------------------|
| 0: Skill Building    | $100 (courses)           |
| 1: Hardware Setup    | $1,700                   |
| 2: Firmware Dev      | $0                       |
| 3: Advanced Sensors  | $200 (optional upgrades) |
| 4: Field Testing     | $100 (consumables)       |
| 5: Documentation     | $0-$50                   |
| **Total Estimated**  | **~$2,100 - $2,150**     |

---

## Future Work Ideas

- Swarm coordination with ROS2  
- Hydrogen fuel cells for longer flight times  
- Autonomous charging dock integration  

---

*Estimated total duration: ~6-7 months balancing study and practical build.*

