<!--
  ============================================================
  GITHUB PROFILE README — Harish Deepak
  ============================================================
  This file goes in a repo named EXACTLY:  HarishDeepak/HarishDeepak
  (repo name must match your username), set to PUBLIC, with the file
  named README.md in the root. GitHub then renders it as a banner
  on github.com/HarishDeepak.

  All content below is sourced from cv_master.md status:verified
  entries only. Nothing invented. Edit freely before publishing.
  ============================================================
-->

# Hi, I'm Harish 👋

**M.Sc. Information & Communication Engineering @ TU Darmstadt** · Robotics perception & manipulation

I build robots that can see, understand, and act. Currently at PEARL Lab working on vision-based manipulation with a real Franka Panda arm — and building toward humanoid robotics.

- 🔭 **Now:** VLM-based memory for robot task planning (ROS2, real Franka) @ PEARL Lab
- 🦾 **Recently:** migrated a full manipulation stack from ROS1 → ROS2 Humble, solo
- 🎓 **Aug 2026:** selected (from 450 applicants) for the RIMA Summer School on walking robots @ FZI Karlsruhe
- 🌱 **Learning:** humanoid/legged robotics, VLA models, C++ for robotics
- 📫 **Reach me:** harish.deepak@stud.tu-darmstadt.de · [LinkedIn](https://linkedin.com/in/harish-deepak)

---

### 🛠️ Tech Stack

**Robotics:** ROS1 (Noetic) · ROS2 (Humble) · ros2_control · MoveIt / MoveIt2 · TRAC-IK · Gazebo · RViz · Open3D
**Languages:** Python · C++ · Embedded C · MATLAB · SQL
**ML & Vision:** PyTorch · TensorFlow · OpenCV · SAM2 · FoundationPose · CLIP · DINOv2 · LoRA/PEFT · ViT
**Tools:** Git · Linux · Docker · colcon

---

### 🤖 Featured Projects

**[IRM-ROS2-Port](https://github.com/HarishDeepak/IRM-ROS2-Port)** — ROS1 → ROS2 Humble migration of a Franka Panda manipulation pipeline
Solo migration in Docker; resolved 7 hard integration issues (URDF constraints, controller-manager timing, plugin ordering). Tuned JointTrajectoryController + MoveIt2 planning.

**[irobman_project](https://github.com/HarishDeepak/irobman_project)** — Sim-to-Real Vision-Based Manipulation (PEARL Lab)
Closed-loop grasp-and-stack on a real 7-DoF Franka Panda. SAM2 + FoundationPose for 6D pose, an FSM for task orchestration, MoveIt + TRAC-IK for motion planning. Validated in Gazebo, transferred to hardware.

**[Diffusion_Policy_Fine-Tuning_with_LoRA](https://github.com/HarishDeepak/Diffusion_Policy_Fine-Tuning_with_LoRA)** — LeRobot Diffusion Policy evaluation + LoRA fine-tuning
Ran a pretrained visuomotor policy on PushT, fixed a normalization bug and a >100GB pipeline memory leak, built a 10-seed quantified eval harness, fine-tuned LoRA adapters.

**[VC](https://github.com/HarishDeepak/VC)** — RG-GeoPrompt-PEFT: open-vocabulary remote-sensing segmentation
Parameter-efficient (1.35% trainable) DINOv2+LoRA + CLIP model; 84.9% mIoU on ISPRS Potsdam with zero-shot transfer to unlabeled Darmstadt aerial imagery.

**[cyclist-painpoints](https://github.com/HarishDeepak/cyclist-painpoints)** — Cycling infrastructure gap analysis
Python/OSMnx/GeoPandas pipeline flagging roads lacking cycling infrastructure, ranked by a rule-based score, validated in QGIS.

---

### 📄 Publication

**Image-based character recognition to decode temple inscriptions** — *arXiv preprint, 2024* · [arxiv.org/abs/2405.17449](https://arxiv.org/abs/2405.17449)

---

<!--
  OPTIONAL STATS WIDGETS — uncomment to add. These are third-party
  services (github-readme-stats by anuraghazra). They render live
  cards. Replace nothing — username is already set to HarishDeepak.
  Some recruiters like them; some find them noisy. Your call.
-->

<!--
![Harish's GitHub stats](https://github-readme-stats.vercel.app/api?username=HarishDeepak&show_icons=true&theme=default)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=HarishDeepak&layout=compact)
-->
