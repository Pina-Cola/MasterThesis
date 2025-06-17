# Master Thesis – Multimedia Processing: Real-Time Colour Grading with JIT using the MLT Framework

This repository contains  my Master's thesis in Computing Science at Umeå University, done in cooperation with Codemill.

The thesis explores multimedia processing with a focus on real-time, user-side RGB colour adjustment in video streaming. The implementation leverages **Just-In-Time (JIT)** techniques and the **Media Lovin' Toolkit (MLT)** framework, integrated into Codemill’s **Accurate Player** and using **WebRTC** as a data channel.

## Abstract

The topic of this thesis project is multimedia processing, focusing on the user-sided adjustment of RGB values in video streaming using Just-In-Time (JIT) techniques and the Media Lovin’ Toolkit (MLT) framework. This is implemented in Codemill’s Accurate Player and using Web Real-Time Communication (WebRTC) as a data channel. Colour theory and RGB colour representation are discussed and technical details on the structure and usage of the MLT framework are provided.

The first part of the research question aims to evaluate the feasibility of the real-time colour adjustment. This research question is answered positively by providing an implementation that can address real-world use cases. A comparison of different MLT filters is included, to select the most suitable filter for the RGB adjustment.

The second part of the research question considers the comparison of video colour grading results with MLT filters that were applied on different platforms: The Accurate Player, the command line video editor Melt and the editing software KDEN Live. For this, frames of the different platforms were extracted and subtracted from each other to show differences in the colour saturations. The results reveal that the Accurate Player plays back the original video more accurately than the Melt framework. Additionally, the results lead to the assumption that KDEN Live is not using the same Melt filter as the Accurate Player to adjust the RGB values. Those significant differences in the compared frames show the complexity of the topic of colour adjustment and representation.

## Tools & Technologies
- **MLT Framework** (`melt`, filters, custom integration)
- **WebRTC** for real-time communication
- **Codemill Accurate Player**
- **JavaScript & HTML (frontend integration)**
- **Python & Bash scripts** for video analysis


## Keywords
`Multimedia processing`, `RGB adjustment`, `MLT`, `colour grading`, `real-time`, `WebRTC`, `Accurate Player`, `Codemill`, `JIT`

## Year & Institution
**2024** 
**Umeå University – Department of Computing Science**

## eference
Official DiVA publication: 
[Link to Diva portal](www.diva-portal.org/smash/record.jsf?pid=diva2%3A1870057&dswid=-6973)

---

*This thesis was part of the Master of Science Programme in Computing Science.*
