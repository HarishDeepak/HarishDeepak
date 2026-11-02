# Harish Deepak

M.Sc. student in Information & Communication Engineering at TU Darmstadt. I work on robot perception and manipulation: getting a real arm to see an object, plan a grasp and carry it out.

- **Now:** joining PEARL Lab (TU Darmstadt) as a student research assistant; volunteering on the ROS 2 software team of DARE Robotics Darmstadt
- **Just finished:** a test bench for camera-based driver monitoring (Euro NCAP warning timing), and a PragmaBot reproduction on a Franka FR3
- **Based in:** Darmstadt, Germany. English (professional), German (B1)
- **Contact:** [LinkedIn](https://linkedin.com/in/harish-deepak) · [Portfolio](https://harishdeepak.github.io/portfolio/) · harish.deepak@stud.tu-darmstadt.de

## Projects

**[driver-attention-bench](https://github.com/HarishDeepak/driver-attention-bench)**: tests a camera-based driver monitor the way a validation team would. Euro NCAP SD-202 warning timing on real (DMD) and synthetic drivers, a comparison of DINOv2/CLIP probes and hosted VLMs against simple eye-closure signals, and a CARLA demo that escalates to a minimal-risk manoeuvre. Small datasets and simplified physics, and the README says so.

**[irm2pragmabot](https://github.com/HarishDeepak/irm2pragmabot)**: PragmaBot (IEEE RA-L 2026) reproduced on a real Franka FR3. Grounded-SAM-2 with stereo depth and GraspGen for grasping, hand-eye calibration, and a ROS 2 / MoveIt 2 skill layer. PEARL Lab, TU Darmstadt.

**[irobman_project](https://github.com/HarishDeepak/irobman_project)**: closed-loop cube stacking on a real Franka Panda. SAM2 and FoundationPose for 6D pose, a state machine for the task, MoveIt with TRAC-IK for motion. Built in Gazebo, run on the robot.

**[IRM-ROS2-Port](https://github.com/HarishDeepak/IRM-ROS2-Port)**: the same stack moved from ROS 1 Noetic to ROS 2 Humble (ros2_control, MoveIt 2, Docker). Seven integration problems written up with their fixes.

**[Diffusion_Policy_Fine-Tuning_with_LoRA](https://github.com/HarishDeepak/Diffusion_Policy_Fine-Tuning_with_LoRA)**: LeRobot diffusion policy on PushT: a 10-seed evaluation harness, a normalization bug and a >100 GB memory leak fixed, LoRA fine-tuning working end to end. Success rate stayed at 5/10 after LoRA, and the README reports that as it is.

**[cyclist-painpoints](https://github.com/HarishDeepak/cyclist-painpoints)**: finds road segments with fast, unprotected traffic from OpenStreetMap data only, ranked by a rule-based score and checked in QGIS.

## Also

- Selected for the RIMA Summer School on walking robots (FZI Karlsruhe, Aug 2026): behaviour trees, navigation and perception on Spot and Go2 in simulation
- 1st place, House of Developers Hackathon (GDSC VIT, data science track, 2022)
- Preprint: *Image-based character recognition to decode temple inscriptions*, [arXiv:2405.17449](https://arxiv.org/abs/2405.17449)

**Tools:** Python, C++, PyTorch, OpenCV, ROS 1 / ROS 2, MoveIt, Gazebo, Docker, Git, Linux
