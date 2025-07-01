# UAV-UGV-Integration

This repository supports the Master's thesis of **Reza Ahmari** at **North Carolina A&T State University**, titled:

> **A Data-Driven Approach to Evaluate UAV/UGV integration in UAV deployment scenarios**

<pre> <code>
@article{ahmari2025evaluating,
  title={Evaluating trojan attack vulnerabilities in autonomous landing systems for urban air mobility},
  author={Ahmari, Reza and Hemmati, V and Mohammadi, A and Mynuddin, M and Kebria, P and Mahmoud, M and Homaifar, A},
  journal={Proceedings of the Automation, Robotics \& Communications for Industry},
  volume={4},
  number={5.0},
  pages={80},
  year={2025}
}

@article{ahmari2025data,
  title={A data-driven approach for uav-ugv integration},
  author={Ahmari, R and Hemmati, V and Mohammadi, A and Kebria, P and Mahmoud, M and Homaifar, A},
  journal={Proceedings of the Automation, Robotics \& Communications for Industry},
  volume={4},
  number={5.0},
  pages={77},
  year={2025}
}

@inproceedings{ahmari2025smc,
  title={An Experimental Study of Trojan Vulnerabilities in UAV Autonomous Landing},
  author={Ahmari, Reza and Mohammadi, Ahmad and Hemmati, Vahid and Mohammed, Mynuddin and Mahmoud, Mahmoud Nabil and Kebria, Parham and Homaifar, Abdollah},
  booktitle={2025 IEEE International Conference on Systems, Man, and Cybernetics (SMC) (accepted)},
  pages={},
  year={2025},
  organization={IEEE}
}

</code> </pre>

## 🧠 Overview

Urban Air Mobility (UAM) systems are increasingly reliant on deep learning for autonomous operations, making them susceptible to adversarial threats. This research investigates the impact of **Trojan attacks** on autonomous landing systems and proposes a **data-driven framework for UAV-UGV integration** to improve landing coordination and robustness.

## Main Contributions:
- 🚨 **Trojan Vulnerability Evaluation**: Trigger-based neural attacks on landing perception models.
- 🤝 **UAV-UGV Integration**: Real-time vision-based framework for UAV-UGV integration.
- 🔍 **Heading Angle Prediction**: A lightweight ANN for UGV-relative orientation estimation.
  
### 🎯 Thesis Contributions

To address the key research objectives, this work introduces the following contributions:

1. **Custom Dataset Development**  
   Created datasets tailored to UAV tasks including:
   - UGV detection under real-world conditions
   - Visual heading angle prediction
   - Landing behavior evaluation with and without adversarial triggers

2. **Vision-Based Heading Angle Estimation**  
   Designed a lightweight Artificial Neural Network (ANN) to predict the UAV's relative heading to a UGV using visual inputs only
   
4. **Robust YOLOv5-Based UGV Detection**  
   Fine-tuned YOLOv5 for UGV detection under occlusions and lighting variability, enabling accurate perception input for coordination and landing.

5. **Trojan Attack Evaluation Framework**  
   Proposed a methodology to inject and evaluate Trojan attacks in CNN-based UAV landing systems using modified VGG16

6. **Cross-Platform System Integration**  
   Integrated Windows (for VICON) and Linux (for ROS) environments into a unified architecture **without virtual machines**, enabling synchronized and efficient UAV-UGV control.

7. **Custom VICON API for Real-Time Labeling**  
   Developed an API to stream VICON data, allowing:
   - Real-time UAV/UGV position tracking
   - Automated dataset generation
   - Live ground truth acquisition for training and evaluation
