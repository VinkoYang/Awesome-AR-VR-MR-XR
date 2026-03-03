# Awesome AR / VR / MR / XR

A curated list of awesome resources related to immersive technologies, including Augmented Reality (AR), Virtual Reality (VR), Mixed Reality (MR), and Extended Reality (XR). This list includes papers, SDKs, tools, frameworks, tutorials, development resources, research labs, and industry trends.

**Contributions are welcome!** See [CONTRIBUTING.md](CONTRIBUTING.md)

## 📚 Table of Contents

- [Introduction](#introduction)
- [Libraries & Frameworks]
  - 
- [SDKs & Development Tools](#sdks--development-tools)
  - [Cross-Platform](#cross-platform)
  - [AR SDKs](#ar-sdks)
  - [VR SDKs](#vr-sdks)
- [AR Libraries & Frameworks](#ar-libraries--frameworks)
- [VR Libraries & Frameworks](#vr-libraries--frameworks)
- [MR/XR Toolkits](#mrxr-toolkits)
- [Papers](#papers)
  - [3D Reconstruction & Tracking](#3d-reconstruction--tracking)
  - [Human–XR Interaction](#humanxr-interaction)
  - [Perception in XR](#perception-in-xr)
- [Courses & Tutorials](#courses--tutorials)
- [Devices & Hardware](#devices--hardware)
- [Labs & Research Groups](#labs--research-groups)
- [Industry Resources](#industry-resources)
  - [Standards & Conferences](#standards--conferences)
  - [Blogs & News](#blogs--news)
- [License](#license)

## 🚀 Basic Knowledge

This repository collects resources that support learning, research, and development in AR/VR/MR/XR technologies. Whether you're a developer, researcher, or enthusiast, you'll find curated resources across multiple domains.

Topics Covered
- **AR/VR/XR Basic**
- **Tracking & SLAM** – Spatial mapping and localization techniques
- **Rendering** – Graphics and visualization pipelines
- **Interaction Techniques** – User interaction design and implementation
- **XR Hardware** – Devices and technical specifications
- **User Experience & Ergonomics** – Design best practices
- **Immersive Application Development** – Tools and frameworks
- **Machine Learning for XR** – AI/ML in immersive applications

### AR/VR/XR Basic

### Tracking & SLAM – Spatial mapping and localization techniques
- [SLAM Handbook（MIT / Cambridge University Press）](https://dspace.mit.edu/handle/1721.1/163400)
- [SLAM Public Release](https://github.com/SLAM-Handbook-contributors/slam-handbook-public-release)
- [Review of SLAM Algorithms（MDPI）](https://www.mdpi.com/2032-6653/16/2/56)

### Rendering – Graphics and visualization pipelines
- [Unity XR Graphics Official Documentation](https://docs.unity3d.com/2022.3/Documentation/Manual/xr-graphics.html)
- [Unity URP XR Render Pipeline Compatibility](https://docs.unity3d.com/2022.1/Documentation/Manual/xr-render-pipeline-compatibility.html)
- [VIVE Wave XR – URP Support Guide](https://hub.vive.com/storage/docs/en-us/UnityXR/UnityXRURPGuidance.html)

### Interaction Techniques – User interaction design and implementation

- [XR Interaction Techniques in Education Games（MDPI）](https://www.mdpi.com/2078-2489/16/7/572)
- [XR Design Handbook（GitHub）](https://github.com/jackyangzzh/XR-Design-Handbook)
- [XR Design Guidelines Resource Library](https://xrdesignhandbook.com/docs/Resources)

### XR Hardware – Devices and technical specifications

- [Android XR Device Types（Android Developers）](https://developer.android.com/develop/xr/devices)
- [Unity XR Solutions(XR Platforms Overview)](https://unity.com/solutions/xr)

### User Experience & Ergonomics – Design best practices

- [XR Experience Design & Evaluation Framework（Springer）](https://link.springer.com/chapter/10.1007/978-3-031-78357-9_5)
- [XRgonomics: Ergonomic 3D UI Toolkit（ACM CHI）](https://dl.acm.org/doi/fullHtml/10.1145/3411764.3445349)
- [Scania XR Guidelines（Ergonomics + Accessibility）(https://tegel.scania.com/resources/xr-guidelines)

### Immersive Application Development – Tools and frameworks

- [Unity XR Development Hub](https://unity.com/solutions/xr)
- [Ultimate XR Development Guide（GitHub）](https://github.com/authorTom/ultimate-XR-dev-guide)

### Machine Learning for XR – AI/ML in immersive applications

- [Machine Learning for XR Environmental Prediction（Springer）](https://link.springer.com/chapter/10.1007/978-3-031-88013-1_24)
- [XR Blocks: AI + XR Framework（Google Research）](https://research.google/blog/xr-blocks-accelerating-ai-xr-innovation/)
- [ML for XR Spatial Positioning（DIVA Portal）](https://su.diva-portal.org/smash/get/diva2:1830965/FULLTEXT01.pdf)



---

## Frameworks
Popular frameworks to build AR/VR experiences.

### Cross‑Platform XR Frameworks
Frameworks that support multiple XR platforms (AR, VR, MR) through a unified API or runtime.

- Unity XR Interaction Toolkit
- [Unity AR Foundation](https://docs.unity3d.com/Packages/com.unity.xr.arfoundation@1.0/manual/index.html) - SDK integrated with Unity game engine to build handheld (tablet and smartphon) based AR solutions. Can target both ARCore and ARKit.
- **[Unreal Engine XR Framework](https://docs.unrealengine.com/5.0/en-US/xr-development/)** – Comprehensive VR/AR development in Unreal Engine
- **[OpenXR](https://www.khronos.org/openxr/)** – Open standard for AR/VR runtime interoperability, ensuring cross-platform compatibility
- A‑Frame / WebXR API
- **[Varjo XR SDK](https://developer.varjo.com/)** – SDK for high-end XR devices
- **[Magic Leap SDK](https://www.magicleap.com/en-us/developers)** – Development tools for Magic Leap spatial computing devices

### AR Frameworks

Frameworks focused on mobile AR, spatial tracking, and AR interaction.

- **[ARCore](https://developers.google.com/ar)** – Google's AR platform for Android devices
- **[ARKit](https://developer.apple.com/arkit/)** – Apple's AR framework for iOS and iPadOS
- **[EasyAR](https://www.easyar.com/)** – Cross-platform AR engine with marker and markerless tracking
- [RealityKit](https://developer.apple.com/augmented-reality/reality-composer) - High-level AR framework by Apple. Comparable to Unity and Unreal Engine but specific for AR solutions.
- [Vuforia](https://developer.vuforia.com/) - AR SDK that is directly integrated in the Unity Editor. Proprietary license, [free to develop with](https://developer.vuforia.com/vui/pricing)
- Wikitude
- [8th Wall](https://www.8thwall.com) - SDK's to build either Web or Smartphone based AR solutions
- RealityKit
- [Torch AR](https://www.torch.app) - Mobile augmented reality prototyping and design
- [Spark AR Studio](https://sparkar.facebook.com/ar-studio) - Facebook's AR content creation tool for Facebook, Messenger, and Instagram.


### VR Frameworks (Virtual Reality)
Frameworks dedicated to VR interaction, locomotion, UI, input, and device‑specific features.

- VRTK (Virtual Reality Toolkit)
- **[SteamVR](https://www.steampowered.com/steamvr/)** – Valve's VR platform supporting multiple headsets
- **[Meta Quest SDK](https://developer.oculus.com/)** – Official SDK for Meta/Oculus VR headsets
- **[HTC Vive Wave SDK](https://developer.vive.com/)** – Development framework for HTC Vive devices
- **[Pico SDK](https://developer.picoxr.com/)** – SDK for Pico Interactive VR headsets

### MR / Spatial Computing Frameworks
Frameworks supporting advanced spatial interaction, environmental understanding, and mixed‑reality UI.

- MRTK / MRTK3 (Mixed Reality Toolkit) [MRTK3 Official Documentation (Microsoft Learn)](https://learn.microsoft.com/en-us/windows/mixed-reality/mrtk-unity/mrtk3-overview/) & [MRTK3 GitHub Repository](https://github.com/MixedRealityToolkit/MixedRealityToolkit-Unity)
- Magic Leap SDK [Magic Leap 2 Developer Portal](https://ml2-developer.magicleap.com/) [Magic Leap Developer Documentation](https://developer-docs.magicleap.cloud/)
- Varjo XR SDK
- Apple VisionOS Spatial frameworks (RealityKit + spatial APIs)


### Web‑based XR Frameworks
Frameworks for creating XR content that runs directly in the browser.

A‑Frame
- [AR.js](https://github.com/jeromeetienne/ar.js) - JavaScript (WebGL, WebRTC) AR SDK based on [A-Frame](https://aframe.io)
ZapWorks WebAR
8th Wall WebXR
- [WebXR Device API Specification](https://github.com/immersive-web/webxr) - Repository for the WebXR Device API Specification.
- [ZapWorks](https://zap.works) - All-in-one AR toolkit to build, publish, and analyze AR solutions. Built by Zappar, the company behind the [AR cardboard](#hardware).


### No‑Code / Low‑Code XR Tools
Tools that provide an authoring environment for creating XR content without programming.

- [Adobe Project Aero](https://www.adobe.com/products/projectaero.html) - AR authoring tool targeted at designers
- [Reality Composer](https://developer.apple.com/augmented-reality/reality-composer) - AR prototyping tool by Apple
- [wiARframe](https://www.wiarframe.com) - AR Prototyping inspired by Invision, Sketch, and Marvel
- ZapWorks Studio




## 🔧 SDKs & Development Tools

### Tracking / SLAM / Visual–Inertial Estimation
- **[OpenVINS](https://github.com/rpng/open_vins)** – Open-source visual-inertial SLAM framework
- **[ORB-SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3)** – Versatile SLAM system for monocular, stereo, and RGB-D cameras

### Computer Vision Libraries（for XR perception）
- [OpenCV](https://opencv.org) - Open Source Computer Vision Library

### Hand Tracking / Body Tracking / Interaction Perception
- **[Unity XR Interaction Toolkit](https://docs.unity3d.com/Manual/XRInteractionToolkit.html)** – Standard cross-XR interaction framework for Unity
- **[VRTK (Virtual Reality Toolkit)](https://github.com/ExtendRealityLtd/VRTK)** – Comprehensive VR interaction framework
- [MediaPipe Hands / Hand Landmarker（Google）](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker) - 21‑point 3D hand landmarks for AR/VR gesture interaction.

### Rendering, Graphics & XR Runtime APIs


---


## 🎓 Courses & Tutorials

- **[MIT OpenCourseWare VR/AR](https://ocw.mit.edu/)** – Free MIT courses on immersive technologies
- **[Stanford CS448: AR/VR](https://cs448.stanford.edu/)** – Advanced graduate course on AR/VR technologies
- **[Unity Learn XR Courses](https://learn.unity.com/course/vr-fundamentals)** – Official Unity XR learning paths
- **[Udacity Nanodegree Programs](https://www.udacity.com/)** – Professional VR/AR development programs
- **[Coursera XR Specializations](https://www.coursera.org/)** – University-level courses on XR
- **XR Interaction & UX Design Tutorials** – Design principles and implementation guides

---

## 🛠️ Devices & Hardware

### Consumer VR
- **[Meta Quest 3 / Quest Pro](https://www.meta.com/quest/)** – Leading consumer VR platform
- **[PlayStation VR2](https://www.playstation.com/en-us/ps5/ps-vr2/)** – Console-based VR

### Premium/Professional XR
- **[Apple Vision Pro](https://www.apple.com/vision-pro/)** – Spatial computer with AR/VR capabilities
- **[Microsoft HoloLens 2](https://www.microsoft.com/en-us/hololens/hardware)** – Enterprise mixed reality device
- **[HTC Vive XR Elite](https://www.vive.com/us/product/vive-xr-elite/)** – High-end VR headset
- **[Varjo XR Series](https://varjo.com/)** – Professional XR with ultra-high resolution
- **[Magic Leap 2](https://www.magicleap.com/)** – Spatial computing platform


---

## 📰 Industry Resources

### Blogs & News

- **[Mozilla Mixed Reality Blog](https://blog.mozilla.org/en/)** – News about AR, VR, and MR from Mozilla
- **[Next Reality](https://www.nextreality.net/)** – AR & MR news, rumors, and developer guides
- **[Reddit r/AR](https://www.reddit.com/r/augmentedreality/)** & **[r/VR](https://www.reddit.com/r/virtualreality/)** – Community discussions on AR and VR
- **[VentureBeat AR/VR Channel](https://venturebeat.com/)** – Technology news with dedicated AR/VR coverage
- **[Upload VR](https://www.uploadvr.com/)** – VR news and game reviews
- **[Road to VR](https://www.roadtovr.com/)** – Comprehensive VR coverage and analysis


### Standards 

- **[OpenXR Standards](https://www.khronos.org/openxr/)** – Official OpenXR specification and documentation
- **[IEEE VR Conference](https://ieeevr.org/)** – Premier international conference on virtual reality
- **[ISMAR (International Symposium on Mixed and Augmented Reality)](https://www.ismarconf.org/)** – Top conference on AR/MR
- **[SIGGRAPH](https://www.siggraph.org/)** – Leading computer graphics conference with XR tracks
- **[XR Industry Reports](https://www.idc.com/)** – Market research and industry analysis

## 📰 Academic Resources

### Conferences

Influential conferences.
- [Augmented World Expo (AWE USA)](https://augmentedworldexpo.com/) - AR + VR conference and expo
- [Augmented World Expo (AWE EU)](https://eu.augmentedworldexpo.com/) - AR + VR conference and expo
- [CES](https://www.ces.tech/) - consumer electronics conference and expo
- [CES ASIA](http://www.cesasia.cn/) - consumer electronics conference and expo
- [E3](https://www.e3expo.com/) - computer games conference and expo
- [Game Developer Conference](https://www.gdconf.com/) - computer games conference and expo
- [Google I/O](https://events.google.com/io/) - Google developer conference
- [L.E.A.P.](https://www.magicleap.com/conference) - Magic Leap conference
- [Mobile World Congress](https://www.mobileworldcongress.com/) - Largest exhibition for the mobile industry
- [Mobile World Congress Americas](https://www.mwcamericas.com/) - Exhibition for the mobile industry
- [Unite](https://unite.unity.com/) - Unity conference
- [VR DAYS](https://vrdays.co/) - AR + VR conference and expo
- [VR/AR Global Summit](http://www.thevrara.com/vr-ar-global-summit) - AR + VR conference
- [VRTO](https://conference.virtualreality.to/) - AR + VR conference and expo
- [VRWorld](http://www.vrworldevent.com/) - AR + VR conference and expo
- [VRX](https://events.vr-intelligence.com/vrx/) - AR + VR conference and expo
- [wave](http://www.wavexc.com/) - AR + VR conference and expo
- [XRDC](http://www.xrdconf.com/) - AR + VR conference
- [WWDC](https://developer.apple.com/wwdc/) - Apple developer conference


### 🏢 Labs & Research Groups

- **[Meta Reality Labs](https://about.facebook.com/realitylabs/)** – Leading XR research division
- **[Microsoft Research](https://www.microsoft.com/en-us/research/)** – XR and mixed reality research
- **[Unity Labs](https://unity.com/labs)** – Advanced XR and gaming research
- **[MIT Media Lab](https://www.media.mit.edu/)** – Interdisciplinary XR and human-computer interaction
- **[Stanford Virtual Human Interaction Lab](https://vhil.stanford.edu/)** – Social interaction in VR
- **[CMU Graphics Lab](http://graphics.cs.cmu.edu/)** & **[HCII](https://www.hcii.cmu.edu/)** – Graphics and human-computer interaction research

---

## 🎬 Movies & TV

### Movies
- Spider-Man: Far From Home (2019) — Features AR illusions and HUD‑style visual overlays.
- Auggie (2019) — A man becomes obsessed with an AR companion.
- Replicas (2019) — VR‑like brain/digital consciousness interface.
- Ready Player One (2018) — Immersive VR world “OASIS.”
- Ghost in the Shell (2017) — Cyber‑enhanced VR/brain‑augmented experiences.
- Sword Art Online: Ordinal Scale (2017) — VR/AR hybrid world game.
- Blade Runner 2049 (2017) — Includes holographic MR projections.
- Creative Control (2016) — AR glasses used for personal escapism and relationships.
- Let’s Be Evil (2016) — Children use AR tech for manipulation.
- Source Code (2011) — TMDB tags it as AR‑related.
- Tron: Legacy (2010) — Digitized VR environments.
- Iron Man (2008) — Famous for helmet‑HUD AR interfaces.
- Sleep Dealer (2008) — MR used for remote telepresence labor.
- Minority Report (2002) — Gesture‑controlled MR display UI.
- The Matrix (1999) — Iconic VR simulation world.
- They Live (1988) — AR‑like “reveal glasses” exposing hidden messages.
- Brainstorm (1983) — Early depiction of VR/HCI brain‑recording tech.
- Tron (1982) — Classic digitized VR environment


### TV Shows
- The Peripheral (2022– ) — Deep VR technology plus remote bodies (“peripherals”). [collider.com]
- VR.5 (1995–1997) — Early VR mind‑access concept. [collider.com]
- Westworld (2016–2022) — Immersive simulation theme park blending AI and XR concepts.
- Classroom for Heroes (2023) — Tagged with AR elements. [imdb.com]
- Sword Art Online series — VRMMO with AR extensions.



## 📖 Papers

### 🏗️ 3D Reconstruction & Tracking

- Structure from Motion (SfM)
- Bundle Adjustment techniques
- Real-time tracking algorithms
- Optical flow and feature matching

### 🧍 Human–XR Interaction

- Hand gesture recognition
- Eye gaze interaction
- Voice command systems
- Natural interaction paradigms

### 👁️ Perception in XR

- Visual perception in immersive environments
- Spatial awareness and presence
- User comfort and cybersickness
- Audiovisual synchronization

*For a curated list of specific papers, please contribute to this section!*

---
## 📄 License

This project is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE). You are free to use, modify, and distribute this list with appropriate attribution.