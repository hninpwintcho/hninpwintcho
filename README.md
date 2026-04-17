<div align="center">

# 👋 Hnin Pwint Cho

### Devops/Cloud Engineer  AI/ML Infrastructure · Data Pipeline 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-hnin--pwint--cho-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/hnin-pwint-cho-35152a47)
[![GitHub](https://img.shields.io/badge/GitHub-hninpwintcho-181717?style=for-the-badge&logo=github)](https://github.com/hninpwintcho)
![Location](https://img.shields.io/badge/📍-Yangon,_Myanmar_(UTC+6:30)-success?style=for-the-badge)
![Experience](https://img.shields.io/badge/Experience-14+_Years_Infra_&_Cloud-orange?style=for-the-badge)

</div>

---

## 💡 What I Do

I bridge **telecom-grade infrastructure reliability** with **modern MLOps and AI deployment** — building systems that run at sea, in the cloud, and at scale.

```
12 yrs Telecom/Network  →  AWS Cloud Infra  →  AI/MLOps Pipeline
     (VSAT, VPN, WAN)       (EC2, S3, IAM)      (SageMaker, YOLOv8)
```

Currently leading **AI infrastructure and data pipeline** for Marine-Drone Co., Ltd (Korea):
- 🐟 **19–32 TB Tuna Detection Dataset Pipeline** — largest in Southeast Asia
- 🚁 **51-vessel drone fleet** RTSP/MQTT command-and-control infrastructure
- ☁️ **Full AWS IaC** via Terraform — S3, SageMaker, EC2 GPU, CodePipeline

---

## 🛠️ Tech Stack

### ☁️ Cloud & MLOps
![AWS](https://img.shields.io/badge/AWS-EC2·S3·SageMaker·VPC·IAM·CloudFront-FF9900?style=flat-square&logo=amazonaws)
![Terraform](https://img.shields.io/badge/IaC-Terraform-7B42BC?style=flat-square&logo=terraform)
![Docker](https://img.shields.io/badge/Container-Docker·Kubernetes-2496ED?style=flat-square&logo=docker)
![SageMaker](https://img.shields.io/badge/MLOps-SageMaker·ECR·CodePipeline-A020F0?style=flat-square&logo=amazonaws)

### 🤖 AI / Computer Vision
![YOLOv8](https://img.shields.io/badge/Detection-YOLOv8·MaskRCNN-00FFFF?style=flat-square)
![PyTorch](https://img.shields.io/badge/Framework-PyTorch·OpenCV-EE4C2C?style=flat-square&logo=pytorch)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python)
![CVAT](https://img.shields.io/badge/Labeling-CVAT·SageMaker_GT-blue?style=flat-square)

### 📡 Streaming & Networking
![RTSP](https://img.shields.io/badge/Video-RTSP·RTMP·MediaMTX·Janus_WebRTC-orange?style=flat-square)
![MQTT](https://img.shields.io/badge/IoT-MQTT·Mosquitto-3C5280?style=flat-square)
![Network](https://img.shields.io/badge/Network-VSAT·VPN·WAN·Firewall·DNS-blue?style=flat-square)

### ⚙️ CI/CD & Monitoring
![Jenkins](https://img.shields.io/badge/CI/CD-Jenkins·GitHub_Actions·CodePipeline-D24939?style=flat-square&logo=jenkins)
![CloudWatch](https://img.shields.io/badge/Monitor-CloudWatch·Grafana·Prometheus-FF4438?style=flat-square)
![Ansible](https://img.shields.io/badge/Automation-Ansible·Bash·Python-EE0000?style=flat-square&logo=ansible)

---

## 🏆 Flagship Project — MDT Dataset Pipeline

> 🐟 **End-to-end MLOps pipeline** for the largest private tuna fish school detection dataset in Southeast Asia.

[![Scale](https://img.shields.io/badge/Dataset-19–32_TB-brightgreen?style=flat-square)](https://github.com/hninpwintcho/MDT_DataSet_pipeline)
[![Fleet](https://img.shields.io/badge/Fleet-51_Drone_Vessels-blue?style=flat-square)](https://github.com/hninpwintcho/MDT_DataSet_pipeline)
[![IaC](https://img.shields.io/badge/IaC-Terraform_Plug--and--Play-7B42BC?style=flat-square)](https://github.com/hninpwintcho/MDT_DataSet_pipeline)
[![Region](https://img.shields.io/badge/AWS-ap--northeast--2-FF9900?style=flat-square)](https://github.com/hninpwintcho/MDT_DataSet_pipeline)

```
51 Vessels → RTSP Recording → EC2 MediaMTX → S3 (19–32 TB)
     → CVAT Labeling → SageMaker GPU Training → Model Registry
     → CodePipeline CI/CD → EC2 GPU Inference → MDT Gallery App
```

**Key achievements:**
- ☁️ Full IaC: S3, IAM (`MDTGallery_Dataset` group), EC2, SageMaker, CloudWatch — `terraform apply` deploys everything
- 💰 Cost-optimized from ~$1,454/mo → **~$870/mo** with Spot Instances + Intelligent Tiering
- 🔐 Least-privilege IAM with access to 9 existing + 1 new S3 dataset buckets
- 📊 Real-world data: 3 years × 51 vessels × 700–1,200 flight hrs/vessel

---

## 📦 Other Projects

| Repo | Description | Stack | Status |
|------|-------------|-------|--------|
| [drone-station-server](https://github.com/hninpwintcho/drone-station-server) | Multi-vessel MQTT + RTSP fleet management | Python · Mosquitto · MediaMTX · Docker | 🟢 Public |
| [drone-streaming](https://github.com/hninpwintcho/drone-streaming) | RTMP + RTSP dual-protocol streaming | Docker · Node Media Server | 🟢 Public |
| tuna_v2-ai-server | YOLOv8 real-time tuna detection + RTSP | Python · YOLOv8 · EC2 GPU | 🔒 Private |
| janus-streaming-server | WebRTC gateway for live drone video | Janus · WebRTC · Docker | 🔒 Private |

---

## 📈 Career Journey

```
2009  B.Eng Electronics & Communication — Technological University Myanmar
  │
2016  Telecom Executive Engineer — Petronas Carigali (HF/VHF, Satellite, PABX)
  │
2017  Network & System Engineer — Golden TMH Telecom (VSAT, VPN, WAN, 99.99% uptime)
  │
2024  Cloud Engineer — Nex4 ICT (KBZ Bank, AWS security, Ansible automation)
  │
2025  ── Junior Cloud/DevOps — Video Streaming Platform (100+ servers, CloudFront, CI/CD)
  │
2025  Cloud / DevOps Engineer — Marine-Drone Co. Ltd Korea (AI, MLOps, Drone Fleet)
  │
2026  🎯 Building: 19–32 TB AI Data Pipeline · Terraform IaC · SageMaker MLOps
```

---

## 💼 What I Can Build For Your Company

| Domain | What I Deliver |
|--------|---------------|
| **MLOps & AI Pipeline** | Data ingestion → labeling → GPU training → CI/CD deploy → monitoring |
| **Computer Vision** | YOLOv8 / Mask R-CNN detection systems on custom datasets |
| **AWS Infrastructure (IaC)** | Terraform plug-and-play: S3, EC2, SageMaker, VPC, IAM, CloudWatch |
| **Video Streaming** | RTSP, RTMP, WebRTC systems — low-latency, multi-source |
| **IoT / Drone Fleet** | MQTT command-and-control, real-time telemetry, multi-vessel management |
| **Cloud Security** | IAM least-privilege, VPC, WAF, ACM, audit logging |
| **Network Engineering** | Enterprise VPN, VSAT, WAN, firewall design |

---

## 📬 Open to Opportunities

> 🚀 **Available for remote consulting, contract work, and full-time roles worldwide.**
> Specializing in: *MLOps · AI Infrastructure · AWS Cloud · Drone/IoT Systems*

| | |
|--|--|
| 📞 | +95 998 453 1435 |
| 💼 | [linkedin.com/in/hnin-pwint-cho-35152a47](https://www.linkedin.com/in/hnin-pwint-cho-35152a47) |
| 📍 | Yangon, Myanmar — available remote globally |

---

<div align="center">

*14+ years of infrastructure. From satellites to AI models. From the sea to the cloud.* 🌊🚁🤖

</div>
