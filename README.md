# Awesome-Computer-Vision-Object-Tracking

## Top Computer Vision & Object Tracking Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Real-Time Multi-Object Tracking (MOT), Video Annotation Pipelines, YOLO/SAM Detection Runtimes & Edge Vision AI*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Computer Vision & Object Tracking**. These tools detect, segment, track, annotate, train, and deploy real-time multi-object tracking (MOT) models across video streams, edge cameras, autonomous robotics, sports analytics, and dataset labeling pipelines.



**Examples** include Roboflow, Landing AI, Encord, Scale AI, Labelbox, V7 Labs, SuperAnnotate, Dataloop, Chooch, Clarifai, and mrsarac/ff-tracking (the category leaders and popular runtimes). 



**Open-source emphasis**: This section is heavily expanded with every major active project for real-time object tracking & detection (`mrsarac/ff-tracking`, `Supervision`, `Ultralytics YOLO`, `ByteTrack`, `BoT-SORT`, `SAM 2`, `CoTracker`), self-hosted video/image annotation (`CVAT`, `Label Studio`, `X-AnyLabeling`), and edge vision pipelines (`OpenCV`, `DeepStream-compatible OSS`) — ideal for computer vision engineers, ML researchers, robotics developers, and video analytics teams.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Support & Share](#support--share)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Valuation / Revenue Scale | Pricing (Starting Tier) | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Scale AI (Nucleus & Rapid)](https://scale.com)** | **$29B** valuation (~$1B ARR, raised $15.9B) | **$0.05 / labeling unit** (Scale Rapid pay-as-you-go) | **Free Forever plan**: 200 free labeling units/month (Rapid); Scale Nucleus free tier for individual & academic research | Enterprise AI data infrastructure platform providing high-volume 2D/3D video tracking annotation, sensor fusion labeling, and dataset curation. |
| **[Encord](https://encord.com)** | **~$1B** valuation (raised $159M total) | **$500/month** (Starter tier entry base, custom annual quote) | **14-day free trial** upon sales request/demo with full multimodal sandbox access | AI-assisted data engine and multimodal annotation platform built specifically for complex video object tracking, segmentation masks, and foundation model evaluation. |
| **[Labelbox](https://labelbox.com)** | **~$1B** valuation (raised $189M total) | **$0.10 / LBU** (Starter tier pay-as-you-go) | **Free Forever plan**: 500 free Labelbox Units (LBUs)/month, up to 30 users, 1,500 API req/min, 50 projects | Enterprise data-centric AI platform featuring automated video object tracking interpolation, model-assisted labeling, and human-in-the-loop quality workflows. |
| **[Clarifai](https://clarifai.com)** | **$775M** peak valuation / ~$16M ARR (raised $101M) | **$30/month** (Essential Plan) | **Free Forever plan**: 1,000 inputs/month, 1,000 operations/month, 1 application, unlimited concepts | Full-stack cloud AI platform offering visual recognition, object tracking workflows, automated data labeling, and multi-cloud model orchestration. |
| **[SuperAnnotate](https://superannotate.com)** | **~$200M** valuation (raised $68.5M total) | **$29/user/month** (Starter base, custom annual contract) | **Free Forever plan**: Up to 5 users, 1,000 Orchestrate compute hours, baseline image/video annotation items | Enterprise annotation and AI data platform supporting pixel-accurate video object tracking, polygon interpolation, and custom ML pipeline integrations. |
| **[V7 Labs (V7 Darwin)](https://v7labs.com)** | **~$200M** valuation (raised $36M total) | **$499/month** (Starter tier, billed annually; or £150/user/mo) | **14-day free trial** upon guided sales demo; no permanent free tier | Cloud computer vision training data platform offering SAM-powered auto-segmentation, temporal frame-to-frame object tracking, and dataset management. |
| **[Roboflow](https://roboflow.com)** | **~$175M** valuation / ~$12M ARR (raised $63M) | **$39/month** (Core Plan credit packs) | **Free Forever plan**: 10 recurring credits/month (~30 training jobs or ~80k cloud inferences), unlimited seats, free self-hosted inference | End-to-end cloud computer vision platform offering automated video/image labeling, dataset versioning, hosted model training, and edge/cloud inference APIs. |
| **[Dataloop](https://dataloop.ai)** | **$120M** acquisition valuation (Dell) / raised $50M | **$500/month** (Starter consumption base, AWS Marketplace / annual quote) | **14-day free trial** upon requested demo/PoC onboarding; no permanent free tier | Cloud data management and automated video annotation environment uniting multi-sensor labeling, active learning loops, and deployment pipelines. |
| **[Landing AI (LandingLens)](https://landing.ai)** | **~$100M** valuation (raised $57M Series A) | **$250/month** (Team tier; or enterprise credit packages) | **Free Forever plan**: 1,000 credits/month (non-rollover), up to 3 seats, 1 active deployable project, non-commercial use | Visual inspection and industrial computer vision platform enabling rapid defect detection, object tracking, and edge deployment for manufacturing teams. |
| **[Chooch](https://chooch.com)** | **~$80M** valuation / ~$10M ARR (raised $43M) | **$500/month** (Base edge stream licensing starting bracket) | **14-day free trial** / proof-of-concept pilot provided on request; ImageChat sandbox free tier | Enterprise edge-to-cloud computer vision platform delivering real-time video analytics, object detection, and automated anomaly alerts for CCTV and industrial streams. |





## Open-Source GitHub Projects



- **[mrsarac/ff-tracking](https://github.com)**  

  Open-source computer vision and object tracking project engineered for fast, practical video tracking workflows and real-time target state estimation.



- **[Supervision (`roboflow/supervision`)](https://github.com)**  

  Essential open-source Python toolkit providing reusable computer vision utilities—including ByteTrack integration, line/polygon zone counting, heatmaps, and video annotators—for any detection/segmentation model.



- **[SAM 2 — Segment Anything in Images and Videos (`facebookresearch/sam2`)](https://github.com)**  

  Breakthrough open-source foundation model from Meta AI for promptable, real-time video object segmentation and consistent multi-frame mask tracking.



- **[Ultralytics YOLO (`ultralytics/ultralytics`)](https://github.com)**  

  Widely adopted open-source computer vision framework supporting real-time object detection, instance segmentation, pose estimation, and integrated BoT-SORT/ByteTrack tracking.



- **[ByteTrack (`FoundationVision/ByteTrack`)](https://github.com)**  

  Landmark open-source multi-object tracking (MOT) algorithm that associates nearly every detection box (including low-score occluded targets) for high-FPS tracking stability.



- **[BoT-SORT (`NirAharon/BoT-SORT`)](https://github.com)**  

  High-accuracy open-source multi-object tracker combining Kalman filter motion modeling, camera-motion compensation, and appearance Re-Identification (ReID).



- **[BoxMOT (`mikel-brostrom/boxmot`)](https://github.com)**  

  Pluggable open-source Python library bundling state-of-the-art multi-object trackers (BoT-SORT, ByteTrack, DeepOCSORT, StrongSORT, ImprAsso) with ReID backbones for any detector.



- **[CoTracker (`facebookresearch/co-tracker`)](https://github.com)**  

  Open-source transformer-based dense point-tracking model from Meta AI capable of tracking arbitrary 2D points jointly across long video sequences even through occlusions.



- **[CVAT — Computer Vision Annotation Tool (`cvat-ai/cvat`)](https://github.com)**  

  Flagship self-hosted open-source interactive video and image annotation tool featuring automated bounding-box interpolation, SAM integration, and team QA workflows.



- **[Label Studio (`HumanSignal/label-studio`)](https://github.com)**  

  Versatile open-source multi-type data labeling platform supporting video timeline object tracking, polygon segmentation, and ML backend pre-labeling hooks.



- **[OpenCV (`opencv/opencv`)](https://github.com)**  

  Foundational open-source C++/Python computer vision library providing classical trackers (CSRT, KCF, MOSSE), optical flow, Kalman filters, and real-time video I/O.



### Additional Strong Open-Source Options



- **[X-AnyLabeling (`CVHub520/X-AnyLabeling`)](https://github.com)** for a fast, desktop-native open-source auto-labeling tool integrating YOLO, SAM 2, and ByteTrack locally with zero cloud dependency.

- **[MMTracking / MMDetection (`open-mmlab/mmdetection`)](https://github.com)** for OpenMMLab's modular PyTorch benchmarking and training suite across detection, MOT, and video instance segmentation.

- **[Norfair (`tryolabs/norfair`)](https://github.com)** for a lightweight, customizable open-source Python library adding real-time 2D/3D object tracking to any custom detector in a few lines of code.

- **[GroundingDINO (`IDEA-Research/GroundingDINO`)](https://github.com)** and **[Grounded-SAM-2 (`IDEA-Research/Grounded-SAM-2`)](https://github.com)** for open-vocabulary text-prompted object detection and video tracking without task-specific retraining.

- **[Frigate NVR (`blakeblackshear/frigate`)](https://github.com)** for a self-hosted open-source network video recorder with real-time AI object detection and tracking on Coral TPU, OpenVINO, and TensorRT.



**Frameworks for building custom systems**: Combine **CVAT** or **X-AnyLabeling** for SAM-assisted video annotation, **Ultralytics YOLO** or **Grounded-SAM-2** for detection/segmentation, and **Supervision + BoxMOT (ByteTrack/BoT-SORT)** for real-time multi-object tracking and zone analytics.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Support & Share



If you find this curated list helpful, consider supporting the project:



- ⭐ **Star this repository** to help others discover it.

- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.

- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!



[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Note that Ultralytics YOLO and SAM 2 carry specific license terms (AGPL-3.0 / Apache-2.0); verify model weight and software licenses before deploying in proprietary commercial products.

- Video analytics and object tracking systems processing public or workplace camera feeds must comply with regional privacy regulations (such as GDPR) and ethical surveillance guidelines.



---



**Made for computer vision engineers, ML researchers, robotics developers, video analytics architects, and open-source contributors.**  

Let's make computer vision and real-time object tracking more open, accurate, and accessible.
