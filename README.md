# 2025 `rockmagpy` workshop
This repository contains material associated with the rock magnetic data processing workshop at the 2025 IRM Conference on Rock Magnetism.

📅 **Thursday, June 12th, 9:00 to 15:30**  
📍 **Room 401-20, Tate Hall, 116 Church St SE**

See steps that should be taken prior to the workshop here:
[pre-workshop set-up steps](https://github.com/Institute-for-Rock-Magnetism/2025_rockmagpy_workshop/blob/main/0_pre-workshop_prep/README.md)

## 🕘 Workshop schedule

- **9:00 to 9:45 am: `rockmagpy` and MagIC introduction**  
  🔍 *Intro to `rockmagpy` and using it with data in MagIC, including Rock Magnetic Bestiary datasets. Tour and interact with content in the [rockmagpy JupyterBook](https://pmagpy.github.io/RockmagPy-notebooks).*

- **9:45 to 10:30 am: Hands-on MagIC upload and data processing**  
  💻 *Upload hysteresis and backfield data into private MagIC workspace and process using Jupyter notebooks following the steps described in this [document](./2_MagIC_hysteresis/README.md)*

- **10:30 to 11:00 am: ☕ Coffee break**

- **11:00 to 12:00 pm: Interactive + reproducible data analysis in Jupyter notebooks**  
  🧪 *Estimate Verwey temperature with `rockmagpy`, explore data, make fits, and document those fits in the cloud.* [Rockmagpy exploration part 1](./3_rockmagpy_exploration/README.md).

- **12:00 to 1:00 pm: 🍽️ Lunch**

- **1:00 to 2:00 pm: Discussion of future directions for `rockmagpy`**  
  💬 Including:
  - 🐞 Contributing via GitHub issues, JupyterBook docs, and PmagPy code
  - 💡 Suggestions for feature development
  - 🔌 Designing export workflows from specialized instruments to MagIC
  We can document this discussion in [discussion.md](./4_rockmagpy_discussion/discussion.md).

- **2:00 to 3:30 pm: Continued `rockmagpy` exploration and development**  
  🚀 Explore more features (e.g., coercivity spectra; [Rockmagpy exploration part 2](./3_rockmagpy_exploration/README.md).) and participate in a "hack-a-thon" on functionality and documentation.

## 🕘 Background

A challenge in the presentation and synthesis of rock magnetic data is the sensitivity of many summary parameters to the specifics of the algorithms used for data processing. This challenge requires that we as a community move towards standard practices of:

- 🗂️ Archiving measurement-level data from rock magnetic experiments complete with rich metadata that document the experimental conditions.
- 📜 Documenting data analysis workflows such that reported results can be reproduced from the data with open source software.

Towards this end, we have been working on developing new rock magnetic data analysis capabilities within a module called `rockmagpy` 🐍 which is now part of the `pmagpy` project. One of the goals of `rockmagpy` is to make more widely available analysis methods that are applied within the IRM's internal software to data within the IRM database. The `rockmagpy` module utilizes the MagIC data model facilitating the manipulation of datasets from that database and the enrichment of datasets for contribution to the database. Utilizing `rockmagpy` within Jupyter notebooks 📓 provides one avenue to document data analysis workflows that can enhance reproducibility.

While `rockmagpy` is in active development, functionality is currently available associated with:
- 🔄 Hysteresis loops  
- 🧲 Backfield curves  
- ❄️ Low-temperature data  
- 🔥 High-temperature susceptibility data  
- 🧮 Anisotropy data

This workshop will give attendees hands-on experience with workflows for the open archiving of rock magnetic experimental data in MagIC. We seek to highlight the benefits of working directly with data from MagIC using `rockmagpy` for reproducible data analysis.

🗣️ We also seek to gather community input for priorities for further `rockmagpy` development and highlight how others can contribute to the project.

## 🔗 Key links

- 📘 `rockmagpy` documentation:  
  https://pmagpy.github.io/RockmagPy-notebooks  
  *The current capabilities of `rockmagpy` are documented within this online book.*

- 🧰 Workshop materials:  
  https://github.com/Institute-for-Rock-Magnetism/2025_rockmagpy_workshop  
  *Materials specific to the workshop can be found in this repository.*

- 🌐 MagIC website:  
  https://www2.earthref.org/MagIC  
  *We will be working with data in the MagIC database including data we upload into private workspaces.*

- ☁️ MagIC JupyterHub:  
  https://www2.earthref.org/MagIC  
  *We will be working with Jupyter notebooks hosted in the cloud.*
