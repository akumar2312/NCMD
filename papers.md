# UAV Target Geolocation – Key IEEE References
This section lists IEEE papers for drone-based target geolocation:
---

## 1️. Real-Time UAV Target Localization

**W. Wang, X. Li, H. Chen, et al.**  
*Real-Time Multi-Target Localization From Unmanned Aerial Vehicles*  
IEEE Access, 2017  

**DOI:**  
[https://doi.org/10.1109/ACCESS.2017.2785720  ](https://doi.org/10.3390/s17010033)

**Relevance:**
- UAV position + sensor angle fusion
- Body → NED → ECEF coordinate transformation
- Real-time ground target geolocation
- Accuracy evaluation framework

---

## 2️. Geolocation Accuracy & Error Propagation

**Y. Zhao, J. Gong, et al.**  
*Geolocation Accuracy Analysis of Airborne Imaging Systems Based on Error Propagation*  
IEEE Transactions on Geoscience and Remote Sensing  

**DOI:**  
[https://doi.org/10.1109/TGRS.2012.2224313  ](https://doi.org/10.1016/j.ijtst.2017.02.002)

**Relevance:**
- Analytical error propagation
- Impact of attitude uncertainty
- GPS + IMU error effects on target lat/lon
- Critical for military-grade precision systems





Drone-Based Target Pinpointing Approaches
Deep Learning Approaches for segementation

---

### 1️. YOLO (Ultralytics YOLOv8)

**Use Case:** Real-time vehicle detection from drone imagery  

**Strengths:**
- High speed (real-time on embedded GPUs)
- Strong detection accuracy (high mAP)
- Easy fine-tuning for aerial military vehicles
- Lightweight deployment

**GitHub:**  
https://github.com/ultralytics/ultralytics

**Best:** Operational, real-time drone systems

---

### 2️. DETR (Transformer-Based Detection)

**Use Case:** High-precision detection in cluttered environments  

**Strengths:**
- End-to-end detection (no anchor boxes)
- Global contextual reasoning
- Strong performance in complex scenes
- Transformer-based architecture

**GitHub:**  
https://github.com/facebookresearch/detr

**Best:** Research-grade, high-accuracy detection systems

---

### 3️. DeepSORT (Deep Tracking + Motion Filtering)

**Use Case:** Stable multi-frame vehicle tracking  

**Strengths:**
- Deep appearance embeddings
- Robust identity preservation
- Kalman-based motion smoothing
- Handles occlusions well

**GitHub:**  
https://github.com/nwojke/deep_sort

**Best:** Persistent target tracking after detection

---

### 4. MSCKF (Multi-State Constraint Kalman Filter)

**Use Case:** Visual–Inertial Odometry (Drone Pose Estimation)

**Strengths:**
- EKF-based
- Lightweight and real-time
- Designed for aerial robotics
- Accurate IMU + camera fusion

**GitHub:**  
https://github.com/KumarRobotics/msckf_vio

**use for:** Precise drone state estimation

--- 
