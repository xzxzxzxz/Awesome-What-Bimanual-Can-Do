<h2 align="center">
  Awesome-What-Bimanual-Can-Do
</h2>

<p align="center">
  <img src="assets/img/wbcd_logo_wide.png" alt="WBCD Logo" width="100%">
</p>

<h5 align="center">

[![arXiv](https://img.shields.io/badge/arXiv-coming_soon-b31b1b.svg?logo=arXiv)](https://arxiv.org/) 
[![Home Page](https://img.shields.io/badge/Home-Website-green.svg)](https://wbcdcompetition.github.io/)
[![LIVE](https://img.shields.io/badge/LIVE-Website-orange.svg)](https://www.wbcd.live/)
[![X](https://img.shields.io/badge/@WBCDCompetition-black?logo=X)](https://x.com/WBCDCompetition) 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=xzxzxzxz.wbcd)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) 
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
<!-- [![GitHub license](https://badgen.net/github/license/Naereen/Strapdown.js)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE) -->

<strong>Media Coverage (CN): <a href="https://mp.weixin.qq.com/s/SqlE_TpMyzCj3Us1R3L4NA">甲子光年</a> | <a href="https://mp.weixin.qq.com/s/GwJiwAKvZb0K-uHy2_rzBQ">36氪</a> | <a href="https://mp.weixin.qq.com/s/H26K-brCRXqNVZ-BScoC-g">机器之心</a> | <a href="https://mp.weixin.qq.com/s/Y-9wZm2Rwr_gLEelUgV39A">量子位</a></strong>

<strong>Hardware Sponser's Highlight: <a href="https://galaxea-ai.com/cn">Galaxea 星海图</a>(Track#1) | <a href="https://global.agilex.ai/">AgileX 松灵机器人</a>(Track#2) | <a href="https://www.arx-x.com/">ARX 方舟无限</a>(Track#3)</strong>

</h5>

<p align="center"> </p>

> 😎 A curated list of research, news, datasets, benchmarks, hardware systems, challenges/competitions and real-world applications in **Bimanual Manipulation and Learning from Demonstrations** — affiliated with the ICRA 2025 What Bimanual Teleoperation and Learning from Demonstration Can Do (WBCD) Today Competition, founded by [Dr. Zhuo Xu](https://drzhuoxu.github.io/). Stay tuned as this list evolves alongside the upcoming technical survey, which will include taxonomy, insights, and contributions within recent 5 years and our lessons learned from WBCD competition.

> 📣 **Disclaimer:** The paper release timestamps and acceptance status are primarily based on the comment section on arXiv. We will continue to verify and update this information. If you are the author of a paper, feel free to open an issue to help us keep things up to date! 

> 📣 **Call of PRs!** Think we missed your awesome paper or work? You're very welcome to open a pull request with the title and link — we'll review and update after checking the scope!

<h3>Table of Contents</h3>

<ul>
  <li><a href="#vision">0. Our Vision</a></li>
  <li><a href="#news">1. News</a></li>
  <li><a href="#events">2. Events</a></li>
  <li><a href="#related-surveys">3. Related Surveys</a></li>
  <li><a href="#wbcd-technical">4. WBCD - Technical Paper List</a><br/></li>
  <li><a href="#wbcd-datasetbenchmark">5. WBCD - Dataset & Benchmark</a><br/></li>
  <li><a href="#wbcd-simulator">6. WBCD - Simulator</a><br/></li>
  <li><a href="#wbcd-hardware">7. WBCD - Hardware</a><br/></li>
  <li><a href="#wbcd-datacollection">8. WBCD - Data Collection Solution</a><br/></li></ul>

<hr/>

<h2 id="vision">😶‍🌫️ 0. Our Vision</h2>
<p>
In recent years, the field of bimanual teleoperation and learning from demonstration (LfD) has witnessed remarkable progress, driven by innovations in human sensing technologies and diverse robotic embodiments. Systems like ALOHA, Mobile ALOHA, DexCap, Open-TeleVision, HATO, GELLO, AirExo, and UMI have demonstrated the potential of combining intuitive control interfaces with data-driven learning techniques to enable dexterous, human-like robot manipulation.

However, much of the existing research has been conducted in isolated settings, with researchers designing their own tasks and evaluating their own systems. Key industrial concerns such as motion efficiency, system robustness, cost-effectiveness, and the ease of learning deployable policies—have often been overlooked in academic benchmarks.

To bridge this gap between research and real-world impact, we launched the ICRA 2025 WBCD Competition. The competition aimed to create a shared platform where the community could evaluate technologies on a common set of challenging, practical, and industry-relevant tasks, using diverse human-sensing and teleoperation methods (e.g., VR, puppeteering, exoskeletons, hand-held grippers, gloves and more).

This awesome list is a continuation of that effort. Our vision is to curate, consolidate, and continuously update the most impactful work in the field from the past five years—covering algorithms, datasets, simulators, and hardware systems—and to foster collaboration across academia and industry toward building practical, generalizable bimanual manipulation.
</p>

<hr/>

<h2 id="events">🎟️ 1. Events</h2>
<ul>
  <li>
    <strong><a href="https://2025.ieee-icra.org/competitions/#wbcd">The 1st What Bimanual Teleoperation and Learning from Demonstration Can Do (WBCD)</a></strong><br/>
    <code><em>🏆 Challenge</em></code> <code><em>ICRA 2025, Atlanta, USA</em></code> | <a href="https://wbcdcompetition.github.io/">Website</a><br/>
  </li>
  <li>
    <strong><a href="https://">The 1st What Bimanual Teleoperation and Learning from Demonstration Can Do (WBCD)</a></strong><br/>
    <code><em>🥂 Workshop</em></code> <code><em>TBD 2025</em></code> | <a href="https://wbcdcompetition.github.io/">Website</a><br/>
  </li>
  <li>
    <strong><a href="https://">The 2nd What Bimanual Teleoperation and Learning from Demonstration Can Do (WBCD)</a></strong><br/>
    <code><em>🏆 Challenge</em></code> <code><em>TBD 2026</em></code> | <a href="https://wbcdcompetition.github.io/">Website</a><br/>
  </li>
</ul>

<hr/>

<h2 id="related-surveys">🗃 2. Related Surveys</h2>
<ul>
  <li>
    <a href="https://arxiv.org/abs/2505.04769">Vision-Language-Action Models: Concepts, Progress, Applications and Challenges</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code><br/>
  </li> 
  <li>
    <a href="https://arxiv.org/abs/2504.03515">Dexterous Manipulation through Imitation Learning: A Survey</a><br/>
    <code><em>arXiv</em></code> <code><em>04/2025</em></code><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2504.04939">A Taxonomy of Self-Handover</a><br/>
    <code><em>arXiv</em></code> <code><em>04/2025</em></code><br/>
  </li>
  <li>
    <a href="https://ieeexplore.ieee.org/document/9849068">A Bimanual Manipulation Taxonomy</a><br/>
    <code><em>IEEE Robotics and Automation Letters</em></code> <code><em>08/2022</em></code><br/>
  </li>
  <li>
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S092188901200108X">Dual arm manipulation—A survey</a><br/>
    <code><em>Robotics and Autonomous Systems</em></code> <code><em>10/2012</em></code><br/>
  </li>
</ul>

<hr/>

<h2 id="wbcd-technical">📑 3. WBCD - Technical Paper List</h2>
<p>
  Includes accepted and arXiv technical papers on bimanual manipulation.<br/>
  <strong>🚧 TODO:</strong> Currently listed in reverse chronological order by year; further categorization by <strong>algorithmic approach</strong> and <strong>end-effector</strong> type is in progress.
</p>

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;">2025</summary>
<ul>
  <li>
    <a href="https://arxiv.org/abs/2507.00833">HumanoidGen: Data Generation for Bimanual Dexterous Manipulation via LLM Reasoning</a><br/>
    <code><em>arXiv</em></code> <code><em>07/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2507.00435">RoboEval: Where Robotic Manipulation Meets Structured and Scalable Evaluation</a><br/>
    <code><em>arXiv</em></code> <code><em>07/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2506.19842">ManiGaussian++: General Robotic Bimanual Manipulation with Hierarchical Gaussian World Model</a><br/>
    <code><em>arXiv</em></code> <code><em>06/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2506.18825">SViP: Sequencing Bimanual Visuomotor Policies with Object-Centric Motion Primitives</a><br/>
    <code><em>arXiv</em></code> <code><em>06/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2506.15666">Vision in Action: Learning Active Perception from Human Demonstrations</a><br/>
    <code><em>arXiv</em></code> <code><em>06/2025</em></code> | <a href="https://vision-in-action.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2506.18088">RoboTwin 2.0: A Scalable Data Generator and Benchmark with Strong Domain Randomization for Robust Bimanual Robotic Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>06/2025</em></code> | <a href="https://robotwin-platform.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2506.07339">Real-Time Execution of Action Chunking Flow Policies</a><br/>
    <code><em>Physical Intelligence</em></code> <code><em>06/2025</em></code> | <a href="https://www.pi.website/research/real_time_chunking">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2506.06221">BiAssemble: Learning Collaborative Affordance for Bimanual Geometric Assembly</a><br/>
    <code><em>ICML 2025</em></code> <code><em>06/2025</em></code> | <a href="https://biassemble.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2506.06196">Bridging Perception and Action: Spatially-Grounded Mid-Level Representations for Robot Generalization</a><br/>
    <code><em>RSS 2025</em></code> <code><em>06/2025</em></code> | <a href="https://iliad.stanford.edu/publications/">Website</a><br/>
  </li>
  <li>
    <a href="https://openreview.net/forum?id=qQZUkpAYKX">MoMaGen: Generating Demonstrations under Soft and Hard Constraints for Multi-Step Bimanual Mobile Manipulation</a><br/>
    <code><em>RSS WS 2025</em></code> <code><em>06/2025</em></code> | <a href="https://momagen.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2506.04147">SLAC: Simulation-Pretrained Latent Action Space for Whole-Body Real-World RL</a><br/>
    <code><em>arXiv</em></code> <code><em>06/2025</em></code> | <a href="https://robo-rl.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.23705">Knowledge Insulating Vision-Language-Action Models: Train Fast, Run Fast, Generalize Better</a><br/>
    <code><em>Physical Intelligence</em></code> <code><em>05/2025</em></code> | <a href="https://www.physicalintelligence.company/research/knowledge_insulation">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.07813">DexWild: Dexterous Human Interactions for In-the-Wild Robot Policies</a><br/>
    <code><em>RSS 2025</em></code> <code><em>05/2025</em></code> | <a href="https://dexwild.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.24853">DexMachina: Functional Retargeting for Bimanual Dexterous Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://project-dexmachina.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.24819">Bi-Manual Joint Camera Calibration and Scene Representation</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.24156">Towards a Generalizable Bimanual Foundation Policy via Flow-based Video Prediction</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.13667">Adaptive Diffusion Constrained Sampling for Bimanual Robot Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
    <li>
    <a href="https://arxiv.org/abs/2505.02291">Dexterous Contact-Rich Manipulation via the Contact Trust Region</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://ctr.theaiinstitute.com/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.13441">GraspMolmo: Generalizable Task-Oriented Grasping via Large-Scale Synthetic Data Generation</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://abhaybd.github.io/GraspMolmo/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.12748">TeleOpBench: A Simulator-Centric Benchmark for Dual-Arm Dexterous Teleoperation</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.11032">DexGarmentLab: Dexterous Garment Manipulation Environment with Generalizable Policy</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://wayrise.github.io/DexGarmentLab/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.07819">H3DP: Triply-Hierarchical Diffusion Policy for Visuomotor Learning</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.05287">Morphologically Symmetric Reinforcement Learning for Ambidextrous Bimanual Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.04860">D-CODA: Diffusion for Coordinated Dual-Arm Data Augmentation</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2505.06111">UniVLA: Learning to Act Anywhere with Task-centric Latent Actions</a><br/>
    <code><em>RSS 2025</em></code> <code><em>05/2025</em></code> | <a href="https://github.com/OpenDriveLab/UniVLA">Website</a><br/>
  </li>
  <li>
    <a href="https://www.pi.website/blog/pi05">π-0.5: a Vision-Language-Action Model with Open-World Generalization</a><br/>
    <code><em>Physical Intelligence</em></code> <code><em>04/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2504.18904">ROBOVERSE: Towards a Unified Platform, Dataset and Benchmark for Scalable and Generalizable Robot Learning</a><br/>
    <code><em>RSS 2025</em></code> <code><em>04/2025</em></code> | <a href="https://roboverseorg.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2504.17784">Gripper Keypose and Object Pointflow as Interfaces for Bimanual Robotic Manipulation</a><br/>
    <code><em>RSS 2025</em></code> <code><em>04/2025</em></code> | <a href="https://yuyinyang3y.github.io/PPI/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2504.13059">RoboTwin: Dual-Arm Robot Benchmark with Generative Digital Twins</a><br/>
    <code><em>CVPR 2025</em></code> <code><em>04/2025</em></code> | <a href="https://robotwin-benchmark.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2411.18913">Planning Shorter Paths in Graphs of Convex Sets by Undistorting Parametrized Configuration Spaces</a><br/>
    <code><em>RAL 2025</em></code> <code><em>04/2025</em></code> | <a href="https://shrutigarg914.github.io/pgd-gcs-results/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2504.20359">PRISM-DP: Spatial Pose-based Observations for Diffusion-Policies via Segmentation, Mesh Generation, and Pose Tracking</a><br/>
    <code><em>arXiv</em></code> <code><em>04/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.20020">Gemini Robotics: Bringing AI into the Physical World</a><br/>
    <code><em>Google Deepmind</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.15368v1">Online Imitation Learning for Manipulation via Decaying Relative Correction through Teleoperation</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2025</em></code> | <a href="https://www.youtube.com/watch?v=EkNgnSwrXFY">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.03707">Curating Demonstrations using Online Experience</a><br/>
    <code><em>RSS 2025</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.08558">Can We Detect Failures Without Failure Data? Uncertainty-Aware Runtime Failure Detection for Imitation Learning Policies</a><br/>
    <code><em>RSS 2025</em></code> <code><em>03/2025</em></code> | <a href="https://cxu-tri.github.io/FAIL-Detect-Website/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.24361">Sim-and-Real Co-Training: A Simple Recipe for Vision-Based Robotic Manipulation</a><br/>
    <code><em>RSS 2025</em></code> <code><em>03/2025</em></code> | <a href="https://co-training.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.02881">Reactive Diffusion Policy: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation</a><br/>
    <code><em>RSS 2025</em></code> <code><em>03/2025</em></code> | <a href="https://reactive-diffusion-policy.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.10966v4">Is Your Imitation Learning Policy Better than Mine? Policy Comparison with Near-Optimal Stopping</a><br/>
    <code><em>RSS 2025</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.23271">Learning Coordinated Bimanual Manipulation Policies using State Diffusion and Inverse Dynamics Models</a><br/>
    <code><em>ICRA 2025</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.21860">ManipTrans: Efficient Dexterous Bimanual Manipulation Transfer via Residual Learning</a><br/>
    <code><em>CVPR 2025</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.12466">Modality-Composable Diffusion Policy via Inference-Time Distribution-level Composition</a><br/>
    <code><em>ICLR 2025 WS</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.10631">HybridVLA: Collaborative Diffusion and Autoregression in a Unified Vision-Language-Action Model</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2025</em></code> | <a href="https://hybrid-vla.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.09186">Rethinking Bimanual Robotic Manipulation: Learning with Decoupled Interaction Framework</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.14734">GR00T N1: An Open Foundation Model for Generalist Humanoid Robots</a><br/>
    <code><em>NVIDIA</em></code> <code><em>03/2025</em></code> | <a href="https://developer.nvidia.com/isaac/gr00t">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.13916">Learning Bimanual Manipulation via Action Chunking and Inter-Arm Coordination with Transformers</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://ieeexplore.ieee.org/abstract/document/10907314">A Bimanual Teleoperation System of Humanoid Robots for Dexterous Manipulation</a><br/>
    <code><em>ROBIO 2025</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.12725">Humanoids in Hospitals: A Technical Study of Humanoid Surrogates for Dexterous Medical Interventions</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.10743">Spatial-Temporal Graph Diffusion Policy with Kinematic Modeling for Bimanual Robotic Manipulation</a><br/>
    <code><em>CVPR 2025</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.10070">AhaRobot: A Low-Cost Open-Source Bimanual Mobile Manipulator for Embodied AI</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.09186">Rethinking Bimanual Robotic Manipulation: Learning with Decoupled Interaction Framework</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.07963">Hierarchical Contact-Rich Trajectory Optimization for Multi-Modal Manipulation using Tight Convex Relaxations</a><br/>
    <code><em>ICRA 2025</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.05817">GraphGarment: Learning Garment Dynamics for Bimanual Cloth Manipulation Tasks</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2503.05652">BEHAVIOR Robot Suite: Streamlining Real-World Whole-Body Manipulation for Everyday Household Activities</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2502.20382">Physics-Driven Data Generation for Contact-Rich Manipulation via Trajectory Optimization</a><br/>
    <code><em>RSS 2025</em></code> <code><em>02/2025</em></code> | <a href="https://lujieyang.github.io/physicsgen/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2502.03822">Dynamic Rank Adjustment in Diffusion Policies for Efficient and Flexible Training</a><br/>
    <code><em>RSS 2025</em></code> <code><em>02/2025</em></code> | <a href="https://apollo-lab-yale.github.io/25-RSS-DRIFT-website/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2502.16932">DemoGen: Synthetic Demonstration Generation for Data-Efficient Visuomotor Policy Learning</a><br/>
    <code><em>RSS 2025</em></code> <code><em>02/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2502.17432">FACTR: Force-Attending Curriculum Training for Contact-Rich Policy Learning</a><br/>
    <code><em>RSS 2025</em></code> <code><em>02/2025</em></code> | <a href="https://jasonjzliu.com/factr/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2502.16908">A low-cost and lightweight 6 DoF bimanual arm for dynamic and contact-rich manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>02/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2502.19645">Fine-tuning vision-language-action models: Optimizing speed and success</a><br/>
    <code><em>RSS 2025</em></code> <code><em>02/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2502.19417">Hi Robot: Open-Ended Instruction Following with Hierarchical Vision-Language-Action Models </a><br/>
    <code><em>Physical Intelligence</em></code> <code><em>02/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2501.14208">You Only Teach Once: Learn One-Shot Bimanual Robotic Manipulation from Video Demonstrations</a><br/>
    <code><em>RSS 2025</em></code> <code><em>01/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2501.09747">FAST: Efficient Robot Action Tokenization</a><br/>
    <code><em>Physical Intelligence</em></code> <code><em>01/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2501.13507">Iterative Shaping of Multi-Particle Aggregates based on Action Trees and VLM</a><br/>
    <code><em>arXiv</em></code> <code><em>01/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2501.06919">Shake-VLA: Vision-Language-Action Model-Based System for Bimanual Robotic Manipulations and Liquid Mixing</a><br/>
    <code><em>HRI 2025</em></code> <code><em>01/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2501.03606">VTAO-BiManip: Masked Visual-Tactile-Action Pre-training with Object Understanding for Bimanual Dexterous Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>01/2025</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://genesis-embodied-ai.github.io/">GENISIS: A generative world for general-purpose robotics & embodied AI learning. </a><br/>
    <code><em>GENISIS Team</em></code> <code><em>01/2025</em></code> | <a href="https://genesis-embodied-ai.github.io/">Website</a><br/>
  </li>
  <!-- <li>
    <a href="https://arxiv.org/abs/">Paper_Title</a><br/>
    <code><em>arXiv</em></code> <code><em>xx/2025</em></code> | <a href="https://">Website</a><br/>
  </li> -->

</ul>
</details>

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;">2024</summary>
<ul>
  <li>
    <a href="https://arxiv.org/abs/2412.06779">AnyBimanual: Transferring Unimanual Policy for General Bimanual Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>12/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2412.02676">Planning-Guided Diffusion Policy Learning for Generalizable Contact-Rich Bimanual Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>12/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2412.13877">RoboMIND: Benchmark on Multi-embodiment Intelligence Normative Data for Robot Manipulation</a><br/>
    <code><em>RSS 2025</em></code> <code><em>12/2024</em></code> | <a href="https://x-humanoid-robomind.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2411.15903">Bimanual Grasp Synthesis for Dexterous Robot Hands</a><br/>
    <code><em>RAL 2024</em></code> <code><em>11/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2411.13020">AsymDex: Asymmetry and Relative Coordinates for RL-based Bimanual Dexterity</a><br/>
    <code><em>CoRL 2024 WS</em></code> <code><em>11/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2411.01200">GarmentLab: A Unified Simulation and Benchmark for Garment Manipulation</a><br/>
    <code><em>NeurIPS 2024</em></code> <code><em>11/2024</em></code> | <a href="https://garmentlab.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2411.09942">ALPHA-α and Bi-ACT Are All You Need: Importance of Position and Force Information/Control for Imitation Learning of Unimanual and Bimanual Robotic Manipulation with Low-Cost System</a><br/>
    <code><em>arXiv</em></code> <code><em>11/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2411.02214">DexHub and DART: Towards Internet Scale Robot Data Collection</a><br/>
    <code><em>arXiv</em></code> <code><em>11/2024</em></code> | <a href="https://dexhub.ai/project">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2411.06542">Is Linear Feedback on Smoothed Dynamics Sufficient for Stabilizing Contact-Rich Plans?</a><br/>
    <code><em>ICRA 2025</em></code> <code><em>11/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2411.04549">Vision Language Models are In-Context Value Learners</a><br/>
    <code><em>ICLR 2025</em></code> <code><em>11/2024</em></code> | <a href="https://generative-value-learning.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2411.04005">Object-Centric Dexterous Manipulation from Human Motion Data</a><br/>
    <code><em>arXiv</em></code> <code><em>11/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/">RoboCrowd: Scaling Robot Data Collection through Crowdsourcing</a><br/>
    <code><em>ICRA 2025</em></code> <code><em>11/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://www.pi.website/blog/pi0">π-0: A Vision-Language-Action Flow Model for General Robot Control</a><br/>
    <code><em>Physical Inteeligence</em></code> <code><em>10/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2410.10088">The Ingredients for Robotic Diffusion Transformers</a><br/>
    <code><em>ICRA 2024</em></code> <code><em>10/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2410.24221">EgoMimic: Scaling Imitation Learning via Egocentric Video</a><br/>
    <code><em>ICRA 2025</em></code> <code><em>10/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2410.24185">DexMimicGen: Automated Data Generation for Bimanual Dexterous Manipulation via Imitation Learning</a><br/>
    <code><em>ICRA 2025</em></code> <code><em>10/2024</em></code> | <a href="https://dexmimicgen.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2410.24091">3D-ViTac: Learning Fine-Grained Manipulation with Visuo-Tactile Sensing</a><br/>
    <code><em>CoRL 2024</em></code> <code><em>10/2024</em></code> | <a href="https://binghao-huang.github.io/3D-ViTac/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2410.22355">Learning Goal-oriented Bimanual Dough Rolling Using Dynamic Heterogeneous Graph Based on Human Demonstration</a><br/>
    <code><em>ROBIO 2024</em></code> <code><em>10/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2410.13126">ALOHA Unleashed: A Simple Recipe for Robot Dexterity</a><br/>
    <code><em>CoRL 2024</em></code> <code><em>10/2024</em></code> | <a href="aloha-unleashed.github.io">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2410.07864">RDT-1B: a Diffusion Foundation Model for Bimanual Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>10/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2410.02477">Learning Diverse Bimanual Dexterous Manipulation Skills from Human Demonstrations</a><br/>
    <code><em>arXiv</em></code> <code><em>10/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2409.18707">Discrete Policy: Learning Disentangled Action Space for Multi-Task Robotic Manipulation</a><br/>
    <code><em>ICRA 2025</em></code> <code><em>09/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2409.18121">Robot See Robot Do: Imitating Articulated Object Manipulation with Monocular 4D Reconstruction</a><br/>
    <code><em>CoRL 2024</em></code> <code><em>09/2024</em></code> | <a href="https://robot-see-robot-do.github.io">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2409.17435">Active Vision Might Be All You Need: Exploring Active Vision in Bimanual Robotic Manipulation</a><br/>
    <code><em>CoRL 2024</em></code> <code><em>09/2024</em></code> | <a href="https://soltanilara.github.io/av-aloha/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2409.16275">Generative Factor Chaining: Coordinated Manipulation with Diffusion-based Factor Graph</a><br/>
    <code><em>CoRL 2024</em></code> <code><em>09/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2409.15465">In the Wild Ungraspable Object Picking with Bimanual Nonprehensile Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2409.14698">Bimanual In-hand Manipulation using Dual Limit Surfaces</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2409.14615">A Comparative Study on State-Action Spaces for Learning Viewpoint Selection and Manipulation with Diffusion Policy</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2024</em></code> | <a href="https://apollo-lab-yale.github.io/spaces_comparative_study/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2409.14411">Scaling Diffusion Policy in Transformer to 1 Billion Parameters for Robotic Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2409.07914">InterACT: Inter-dependency Aware Action Chunking with Hierarchical Attention Transformers for Bimanual Manipulation</a><br/>
    <code><em>CoRL 2024</em></code> <code><em>09/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2409.01652">ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2309.14975">AirExo: Low-Cost Exoskeletons for Learning Whole-Arm Manipulation in the Wild</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2024</em></code> | <a href="https://airexo.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2408.09058">Vision-assisted Avocado Harvesting with Aerial Bimanual Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>08/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2408.10899">All Robots in One: A New Standard and Unified Dataset for Versatile, General-Purpose Embodied Agents</a><br/>
    <code><em>arXiv</em></code> <code><em>08/2024</em></code> | <a href="https://imaei.github.io/project_pages/ario/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2407.01512">Open-TeleVision: Teleoperation with Immersive Active Visual Feedback</a><br/>
    <code><em>arXiv</em></code> <code><em>07/2024</em></code> | <a href="https://robot-tv.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2407.04152">VoxAct-B: Voxel-Based Acting and Stabilizing Policy for Bimanual Manipulation</a><br/>
    <code><em>CoRL 2024</em></code> <code><em>07/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2407.01479">EquiBot: SIM(3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning</a><br/>
    <code><em>CoRL 2024</em></code> <code><em>07/2024</em></code> | <a href="https://equi-bot.github.io/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2407.03162">Bunny-VisionPro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning</a><br/>
    <code><em>arXiv</em></code> <code><em>07/2024</em></code> | <a href="https://dingry.github.io/projects/bunny_visionpro.html">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2407.00278">PerAct2: Benchmarking and Learning for Robotic Bimanual Manipulation Tasks</a><br/>
    <code><em>arXiv</em></code> <code><em>07/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2406.14990">Learning Variable Compliance Control From a Few Demonstrations for Bimanual Robot with Haptic Feedback Teleoperation System</a><br/>
    <code><em>IROS 2024</em></code> <code><em>06/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2406.10093">BiKC: Keypose-Conditioned Consistency Policy for Bimanual Robotic Manipulation</a><br/>
    <code><em>WAFR 2024</em></code> <code><em>06/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2406.09953">DAG-Plan: Generating Directed Acyclic Dependency Graphs for Dual-Arm Cooperative Planning</a><br/>
    <code><em>arXiv</em></code> <code><em>06/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2405.18860">Empowering Embodied Manipulation: A Bimanual-Mobile Robot Manipulation Dataset for Household Tasks</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2405.06039">Bi-VLA: Vision-Language-Action Model-Based System for Bimanual Robotic Dexterous Manipulations</a><br/>
    <code><em>SMC 2024</em></code> <code><em>05/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2405.02292">ALOHA 2: An Enhanced Low-Cost Hardware for Bimanual Teleoperation</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2024</em></code> | <a href="https://aloha-2.github.io">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2405.03666">ScrewMimic: Bimanual Imitation from Human Videos with Screw Space Projection</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2405.06903">UniGarmentManip: A Unified Framework for Category-Level Garment Manipulation via Dense Visual Correspondence</a><br/>
    <code><em>CVPR 2024</em></code> <code><em>05/2024</em></code> | <a href="https://warshallrho.github.io/unigarmentmanip">Website</a><br/>
  </li>
  <li>
    <a href="[https://arxiv.org/abs/2506.07339](https://arxiv.org/abs/2404.03570)">Embodied AI with Two Arms: Zero-shot Learning, Safety and Modularity</a><br/>
    <code><em>IROS 2024</em></code> <code><em>04/2024</em></code> | <a href="https://sites.google.com/corp/view/safe-robots">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2404.16823">HATO: Learning Visuotactile Skills with Two Multifingered Hands</a><br/>
    <code><em>arXiv</em></code> <code><em>04/2024</em></code> | <a href="https://toruowo.github.io/hato/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2404.13206">Wheelchair Maneuvering with a Single-Spherical-Wheeled Balancing Mobile Manipulator</a><br/>
    <code><em>arXiv</em></code> <code><em>04/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2404.03790">A Bimanual Teleoperation Framework for Light Duty Underwater Vehicle-Manipulator Systems</a><br/>
    <code><em>UR 2024</em></code> <code><em>04/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2404.02018">Large Language Models for Orchestrating Bimanual Robots</a><br/>
    <code><em>Humanoids 2024</em></code> <code><em>04/2024</em></code> | <a href="http://labor-agent.github.io">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2403.07788">DexCap: Scalable and Portable Mocap Data Collection System for Dexterous Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2403.17249">Impact-Aware Bimanual Catching of Large-Momentum Objects</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2403.12685">Dynamic Manipulation of Deformable Objects using Imitation Learning with Adaptation to Hardware Constraints</a><br/>
    <code><em>IROS 2024</em></code> <code><em>03/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2403.10436">H-MaP: An Iterative and Hybrid Sequential Manipulation Planner</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2403.07870">OPEN TEACH: A Versatile Teleoperation System for Robotic Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2403.03270">Bi-KVIL: Keypoints-based Visual Imitation Learning of Bimanual Manipulation Tasks</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2403.02338">Twisting Lids Off with Two Hands</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2024</em></code> | <a href="https://toruowo.github.io/bimanual-twist">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2402.18088">Bimanual Manipulation of Steady Hand Eye Robots with Adaptive Sclera Force Control: Cooperative vs. Teleoperation Strategies</a><br/>
    <code><em>arXiv</em></code> <code><em>02/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2310.16603">Certifying Bimanual RRT Motion Plans in a Second</a><br/>
    <code><em>ICRA 2024</em></code> <code><em>02/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2402.10329">Universal Manipulation Interface: In-The-Wild Robot Teaching Without In-The-Wild Robots</a><br/>
    <code><em>RSS 2024</em></code> <code><em>02/2024</em></code> | <a href="https://umi-gripper.github.io">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2401.16899">MAkEable: Memory-centered and Affordance-based Task Execution Framework for Transferable Mobile Manipulation Skills</a><br/>
    <code><em>arXiv</em></code> <code><em>01/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2401.11432">Bimanual Deformable Bag Manipulation Using a Structure-of-Interest Based Neural Dynamics Model</a><br/>
    <code><em>arXiv</em></code> <code><em>01/2024</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2401.02117">Mobile ALOHA: Learning Bimanual Mobile Manipulation with Low-Cost Whole-Body Teleoperation</a><br/>
    <code><em>arXiv</em></code> <code><em>01/2024</em></code> | <a href="https://mobile-aloha.github.io">Website</a><br/>
  </li>
  <!-- <li>
    <a href="https://arxiv.org/abs/">Paper_Title</a><br/>
    <code><em>arXiv</em></code> <code><em>xx/2024</em></code> | <a href="https://">Website</a><br/>
  </li> -->

</ul>
</details>

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;">2023</summary>
<ul>
  <li>
    <a href="https://ieeexplore.ieee.org/abstract/document/10343126">Bi-DexHands: Towards Human-Level Bimanual Dexterous Manipulation</a><br/>
    <code><em>TPAMI 2023</em></code> <code><em>12/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://www.science.org/doi/10.1126/scirobotics.adf7843">Motion Planning Around Obstacles With Convex Optimization</a><br/>
    <code><em>Science Robotics 2023</em></code> <code><em>11/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2310.08864">Open X-Embodiment: Robotic Learning Datasets and RT-X Models</a><br/>
    <code><em>ICRA 2023</em></code> <code><em>10/2023</em></code> | <a href="https://robotics-transformer-x.github.io">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2309.13037">GELLO: A General, Low-Cost, and Intuitive Teleoperation Framework for Robot Manipulators</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2023</em></code> | <a href="https://wuphilipp.github.io/gello/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2309.08770">Constrained Bimanual Planning with Analytic Inverse Kinematics</a><br/>
    <code><em>ICRA 2024</em></code> <code><em>09/2023</em></code> | <a href="https://cohnt.github.io/Bimanual-Web/index.html">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2309.07609">Learning Quasi-Static 3D Models of Markerless Deformable Linear Objects for Bimanual Robotic Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2309.05197">Learning Sequential Acquisition Policies for Robot-Assisted Feeding</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2309.01087">Stabilize to Act: Learning to Coordinate for Bimanual Manipulation</a><br/>
    <code><em>CoRL 2023</em></code> <code><em>09/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2308.03479">Feasibility Retargeting for Multi-contact Teleoperation and Physical Interaction</a><br/>
    <code><em>ICRA 2023</em></code> <code><em>09/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2307.14326">Waypoint-Based Imitation Learning for Robotic Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>07/2023</em></code> | <a href="https://lucys0.github.io/awe/">Website</a><br/>
  </li>
  <li>
    <a href="https://ieeexplore.ieee.org/abstract/document/10160739">Efficient Bimanual Handover and Rearrangement via Symmetry-Aware Actor-Critic Learning</a><br/>
    <code><em>ICRA 2023</em></code> <code><em>07/2023</em></code> | <a href="https://sites.google.com/view/bimanual">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2307.06423">Bi-Touch: Bimanual Tactile Manipulation with Sim-to-Real Deep Reinforcement Learning</a><br/>
    <code><em>RAL 2023</em></code> <code><em>07/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2307.05933">BiRP: Learning Robot Generalized Bimanual Coordination using Relative Parameterization Method on Human Demonstration</a><br/>
    <code><em>CDC 2023</em></code> <code><em>07/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2307.04619">Learning Fine Pinch-Grasp Skills using Tactile Sensing from A Few Real-world Demonstrations</a><br/>
    <code><em>arXiv</em></code> <code><em>07/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2306.14595">A Closed-Loop Bin Picking System for Entangled Wire Harnesses using Bimanual and Dynamic Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>06/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2306.12649">Probabilistic Slide-support Manipulation Planning in Clutter</a><br/>
    <code><em>IROS 2023</em></code> <code><em>06/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2305.06341">Non-Euclidean Motion Planning with Graphs of Geodesically-Convex Sets</a><br/>
    <code><em>RSS 2023</em></code> <code><em>05/2023</em></code> | <a href="https://ggcs-anonymous-submission.github.io/">Website</a><br/>
  </li>
    <li>
    <a href="https://arxiv.org/abs/2210.15185">SAM-RL: Sensing-Aware Model-Based Reinforcement Learning via Differentiable Physics-Based Simulation and Rendering</a><br/>
    <code><em>RSS 2023</em></code> <code><em>05/2023</em></code> | <a href="https://sites.google.com/view/rss-sam-rl">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2305.04449">DeformerNet: Learning Bimanual Manipulation of 3D Deformable Objects</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2304.13705">Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware</a><br/>
    <code><em>arXiv</em></code> <code><em>04/2023</em></code> | <a href="https://tonyzhaozh.github.io/aloha/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2302.12219">Certified Polyhedral Decompositions of Collision-Free Configuration Space</a><br/>
    <code><em>IJRR 2023</em></code> <code><em>04/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2303.08975">HANDLOOM: Learned Tracing of One-Dimensional Objects for Inspection and Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2302.12219">Certified Polyhedral Decompositions of Collision-Free Configuration Space</a><br/>
    <code><em>arXiv</em></code> <code><em>02/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2206.10787">Global Planning for Contact-Rich Manipulation via Local Smoothing of Quasi-dynamic Contact Models</a><br/>
    <code><em>TRO 2023</em></code> <code><em>02/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2302.00741">Haptic Feedback of Tool Vibrations Facilitates Telerobotic Construction</a><br/>
    <code><em>arXiv</em></code> <code><em>02/2023</em></code> | <a href="https://">Website</a><br/>
  </li>
  <!-- <li>
    <a href="https://arxiv.org/abs/">Paper_Title</a><br/>
    <code><em>arXiv</em></code> <code><em>xx/2023</em></code> | <a href="https://">Website</a><br/>
  </li> -->

</ul>
</details>

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;">2022</summary>
<ul>
  <li>
    <a href="https://arxiv.org/abs/2211.14652">Learning Bimanual Scooping Policies for Food Acquisition</a><br/>
    <code><em>arXiv</em></code> <code><em>11/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2211.12408">Bimanual Motor Strategies and Handedness Role During Human-Exoskeleton Haptic Interaction</a><br/>
    <code><em>arXiv</em></code> <code><em>11/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2209.14261">Focused Adaptation of Dynamics Models for Deformable Object Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2022</em></code> | <a href="https://sites.google.com/view/focused-adaptation-dynamics/home">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2209.13850">Bimanual rope manipulation skill synthesis through context dependent correction policy learning from human demonstration</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2209.06074">Bimanual crop manipulation for human-inspired robotic harvesting</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2208.11845">Elly: A Real-Time Failure Recovery and Data Collection System for Robotic Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>08/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2208.10552">SpeedFolding: Learning Efficient Bimanual Folding of Garments</a><br/>
    <code><em>IROS 2022</em></code> <code><em>08/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2208.00596">A System for Imitation Learning of Contact-Rich Bimanual Manipulation Policies</a><br/>
    <code><em>IROS 2022</em></code> <code><em>08/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2206.08686">Towards Human-Level Bimanual Dexterous Manipulation with Reinforcement Learning</a><br/>
    <code><em>arXiv</em></code> <code><em>06/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2206.00528">Collaborative Bimanual Manipulation Using Optimal Motion Adaptation and Interaction Control</a><br/>
    <code><em>Robotics & Automation Magazine 2023</em></code> <code><em>06/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2205.05960">Robot Cooking with Stir-fry: Bimanual Non-prehensile Manipulation of Semi-fluid Objects</a><br/>
    <code><em>RAL 2022</em></code> <code><em>05/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2205.03690">Finding and Optimizing Certified, Collision-Free Regions in Configuration Space for Robot Manipulators</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2022</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2203.08277">Bi-Manual Manipulation and Attachment via Sim-to-Real Reinforcement Learning</a><br/>
    <code><em>arXiv</em></code> <code><em>03/2022</em></code> | <a href="https://sites.google.com/view/bimanual-attachment">Website</a><br/>
  </li>

  <!-- <li>
    <a href="https://arxiv.org/abs/">Paper_Title</a><br/>
    <code><em>arXiv</em></code> <code><em>xx/2024</em></code> | <a href="https://">Website</a><br/>
  </li> -->
</ul>
</details>

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;">2021</summary>
<ul>
  <li>
    <a href="https://arxiv.org/abs/2111.05623">FabricFlowNet: Bimanual Cloth Manipulation with a Flow-based Policy</a><br/>
    <code><em>CoRL 2021</em></code> <code><em>11/2021</em></code> | <a href="https://sites.google.com/view/fabricflownet">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2110.11652">Action Planning for Packing Long Linear Elastic Objects into Compact Boxes with Bimanual Robotic Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>10/2021</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2110.08962">Keypoint-Based Bimanual Shaping of Deformable Linear Objects under Environmental Constraints using Hierarchical Action Planning</a><br/>
    <code><em>arXiv</em></code> <code><em>10/2021</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2109.13772">NimbRo Avatar: Interactive Immersive Telepresence with Force-Feedback Telemanipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>09/2021</em></code> | <a href="https://">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2106.05907">DAIR: Disentangled Attention Intrinsic Regularization for Safe and Efficient Bimanual Manipulation</a><br/>
    <code><em>arXiv</em></code> <code><em>06/2021</em></code> | <a href="https://mehooz.github.io/bimanual-attention/">Website</a><br/>
  </li>
  <li>
    <a href="https://arxiv.org/abs/2105.14764">Bimanual Shelf Picking Planner Based on Collapse Prediction</a><br/>
    <code><em>arXiv</em></code> <code><em>05/2021</em></code> | <a href="https://">Website</a><br/>
  </li>

  <!-- <li>
    <a href="https://arxiv.org/abs/">Paper_Title</a><br/>
    <code><em>arXiv</em></code> <code><em>xx/2024</em></code> | <a href="https://">Website</a><br/>
  </li> -->
</ul>

</details>
<hr/>

<h2 id="wbcd-datasetbenchmark">📊 4. WBCD - Dataset & Benchmark</h2>
<p>
  Includes existing datasets and benchmarks that support bimanual manipulation.<br/>
  <strong>🚧 TODO:</strong> Currently listed in reverse chronological order by year; further categorization is in progress.
</p>

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;">2025</summary>
<!-- <ul>
  <li>
    <a href="https://arxiv.org/abs/2401.12345">Dexterous Dual-Arm Manipulation via Demonstration-Augmented Reinforcement Learning</a><br/>
    <code><em>ICRA 2025</em></code> | <a href="https://arxiv.org/abs/2401.12345">Website</a><br/>
  </li>
</ul> -->

</details>

<!-- <h4>2024</h4> -->
<!-- <ul>
  <li>
    <a href="https://arxiv.org/abs/2401.12345">Dexterous Dual-Arm Manipulation via Demonstration-Augmented Reinforcement Learning</a><br/>
    <code><em>ICRA 2025</em></code> | <a href="https://arxiv.org/abs/2401.12345">Website</a><br/>
  </li>
</ul> -->

<!-- <h4>2023</h4> -->
<!-- <ul>
  <li>
    <a href="https://arxiv.org/abs/2401.12345">Dexterous Dual-Arm Manipulation via Demonstration-Augmented Reinforcement Learning</a><br/>
    <code><em>ICRA 2025</em></code> | <a href="https://arxiv.org/abs/2401.12345">Website</a><br/>
  </li>
</ul> -->

<!-- <h4>2022</h4> -->
<!-- <ul>
  <li>
    <a href="https://arxiv.org/abs/2401.12345">Dexterous Dual-Arm Manipulation via Demonstration-Augmented Reinforcement Learning</a><br/>
    <code><em>ICRA 2025</em></code> | <a href="https://arxiv.org/abs/2401.12345">Website</a><br/>
  </li>
</ul> -->

<!-- <h4>2021</h4> -->
<!-- <ul>
  <li>
    <a href="https://arxiv.org/abs/2401.12345">Dexterous Dual-Arm Manipulation via Demonstration-Augmented Reinforcement Learning</a><br/>
    <code><em>ICRA 2025</em></code> | <a href="https://arxiv.org/abs/2401.12345">Website</a><br/>
  </li>
</ul> -->

<hr/>

<h2 id="wbcd-simulator">🧪 5. WBCD - Simulator</h2>

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;">2025</summary>
  <ul>
    <li>
      <a href="https://arxiv.org/abs/2505.11032">DexGarmentLab: Dexterous Garment Manipulation Environment with Generalizable Policy</a><br/>
      <code><em>arXiv</em></code> <code><em>05/2025</em></code> | <a href="https://wayrise.github.io/DexGarmentLab/">Website</a><br/>
    </li>
    <li>
      <a href="https://arxiv.org/abs/2504.18904">ROBOVERSE: Towards a Unified Platform, Dataset and Benchmark for Scalable and Generalizable Robot Learning</a><br/>
      <code><em>RSS 2025</em></code> <code><em>04/2025</em></code> | <a href="https://roboverseorg.github.io/">Website</a><br/>
    </li>
    <li>
      <a href="https://arxiv.org/abs/2504.13059">RoboTwin: Dual-Arm Robot Benchmark with Generative Digital Twins</a><br/>
      <code><em>CVPR 2025</em></code> <code><em>04/2025</em></code> | <a href="https://robotwin-benchmark.github.io/">Website</a><br/>
    </li>
    <li>
      <a href="https://genesis-embodied-ai.github.io/">GENISIS: A generative world for general-purpose robotics & embodied AI learning. </a><br/>
      <code><em>GENISIS Team</em></code> <code><em>01/2025</em></code> | <a href="https://genesis-embodied-ai.github.io/">Website</a><br/>
    </li>
  </ul>
</details>

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;">2024</summary>
<ul>
  <li>
    <a href="https://arxiv.org/abs/2411.01200">GarmentLab: A Unified Simulation and Benchmark for Garment Manipulation</a><br/>
    <code><em>NeurIPS 2024</em></code> <code><em>11/2024</em></code> | <a href="https://garmentlab.github.io/">Website</a><br/>
  </li>
</ul>
</details>

<hr/>

<h2 id="wbcd-hardware">🤖 6. WBCD - Hardware</h2>
<p>
  Includes hardware systems designed for bimanual manipulation tasks.<br/>
  <strong>🚧 TODO:</strong> Currently listed in reverse chronological order by year; further classification into lab prototypes vs. commercial/industrial products is in progress.
</p>

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;">2025</summary>
<ul>
  <li>
    <a href="https://arxiv.org/abs/2504.01554">Cafes: Cable-driven collaborative floating end-effectors for agriculture applications</a><br/>
    <code><em>1st WBCD - Second Prize Award</em></code> <code><em>04/2025</em></code> | <a href="https://www.youtube.com/watch?v=3R5OOFwtzek">Video</a><br/>
  </li>
  <li>
    <a href="https://github.com/Vector-Wangel/XLeRobot">XLeRobot: Fully Autonomous Household Dual-Arm Mobile Robot for $998</a><br/>
    <code><em>XLeRobot Team</em></code> <code><em>04/2025</em></code> | <a href="https://github.com/Vector-Wangel/XLeRobot">Website</a><br/>
  </li>

</ul>

</details>
<hr/>

<h2 id="wbcd-datacollection">🕹️ 7. WBCD - Data Collection Solution</h2>
<p>
  Includes various data collection setups and methods for bimanual manipulation tasks.<br/>
  <strong>🚧 TODO:</strong> TBD
</p>

<details open>
  <summary style="font-size: 1.2em; font-weight: bold;">2025</summary>
<!-- <ul>
  <li>
    <a href="https://arxiv.org/abs/2401.12345">Dexterous Dual-Arm Manipulation via Demonstration-Augmented Reinforcement Learning</a><br/>
    <code><em>ICRA 2025</em></code> | <a href="https://arxiv.org/abs/2401.12345">Website</a><br/>
  </li>
</ul> -->

</details>
