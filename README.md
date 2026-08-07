# PhysLab: A Benchmark Dataset for Multi-Granularity Visual Parsing of Physics Experiments (ACM MM 2025)

<img src="img/Logo.png" alt="Logo" style="zoom: 45%;" />

<div align="center"><img src="https://img.shields.io/badge/Version-1.0--alpha-brightgreen"> </div>

## 🌐 Introduction

🚀 **PhysLab is the first video dataset for visual parsing of physics experimental processes!**

🚀 **We provide rich multi-level annotations to support diverse computer vision research!**

🚀 **Benchmark results on eight core vision tasks are established for comparison and reference!**

⭐ **If you find our dataset beneficial to your research, please kindly star the repository and cite our paper.**

## 🎓 Experimental Instruction

<p align="center">
  <img src="img/ins.svg" alt="Dataset Overview" width="1000">
</p>

## 🔎 Temporal Parsing

### 📸 Annotation Samples

<p align="center">
  <img src="img/Video Samples.jpg" alt="Dataset Overview" width="1000">
</p>

### 📝 Statistics

**The PhysLab dataset contains 620 long videos of four physical experiments, covering 3873 action clips of 32 types of actions, with an average length of 20 seconds per clip and a video frame rate of 30FPS. It subset provides valuable resources for video temporal research such as temporal action proposal, action classification, action alignment, and action segmentation.**

<p align="center">
  <img src="img/Fig. 5-1.svg" alt="Dataset Overview" width="400">
  <img src="img/Fig. 5-2.svg" alt="Dataset Overview" width="410">
</p>

<p align="center">
  <img src="img/Fig. 6-1.svg" alt="Dataset Overview" width="400">
  <img src="img/Fig. 6-2.svg" alt="Dataset Overview" width="400">
</p>

### 🔧 Experimental Results

- **Action Classification**
<p align="center">
  <img src="img/Table 1.png" alt="Dataset Overview" width="360">
</p>

- **Temporal Action Proposal**
<p align="center">
  <img src="img/Table 2.png" alt="Dataset Overview" width="400">
</p>

<p align="center">
  <img src="img/Fig. 8.jpg" alt="Dataset Overview" width="700">
</p>

- **Action Alignment & Action Segmentation**
<p align="center">
  <img src="img/Table 3.png" alt="Dataset Overview" width="800">
</p>

## 🔎 Spatial Parising

### 📸 Annotation Samples

<p align="center">
  <img src="img/intro.jpg" alt="Dataset Overview" width="330">
  <img src="img/obj.svg" alt="Dataset Overview" width="460">
</p>

<p align="center">
  <img src="img/seg.jpg" alt="Dataset Overview" width="790">
</p>
  

## 📣 Note

😉 **At present, we are supplementing data samples of six other experimental types and building collection devices for chemical and biological experiments!**

## 📥 Download

**We are currently in the process of aligning and integrating multi-source data. Once the integration is complete, the full dataset—including all video/image data and corresponding annotation files—will be made available via Google Cloud and Baidu Cloud download links. In the meantime, sample data has been temporarily provided in the project repository for reference. Please refer to the <ins>***samples***</ins> series folder for access to these examples.**

- **The HOI subset of PhysLab can be download at [Here](https://drive.google.com/file/d/1WRcpXzVsI597LmUPnG0YXL2rx3aK_00a/view?usp=sharing)!**
- **The action segmentation subset of PhysLab can be download at [Here](https://cf-my.sharepoint.com/:u:/g/personal/zoum1_cardiff_ac_uk/IQBzB4qb2CvyQ7qeyDthw7dOATL60J7NDeoAEySrMzIbH_A?e=CQVzAy)!**

## 👪 Team
**The dataset was developed with contributions from Qingtian Zeng, Yongping Miao, Hantao Liu, Wei Zhou, Minghao Zou, Shangkun Liu, Shuang Chen, Xirui Jia, Xingkai Bai, Aihang Jiang, Zhenkai Zhao, Zilong Wang, and over twenty additional participants, whose efforts are gratefully acknowledged.**

## 📄 Citation
```bibtex
@inproceedings{minghao2025phy,
          title={PhysLab: A Benchmark Dataset for Multi-Granularity Visual Parsing of Physics Experiments},
          author={Minghao Zou, Qingtian Zeng, Yongping Miao, Shangkun Liu, Zilong Wang, Hantao Liu, and Wei Zhou},
          booktitle={ACM International Conference on Multimedia (ACM MM)},
          year={2025},
        }

@misc{zou2025physlabbenchmarkdatasetmultigranularity,
      title={PhysLab: A Benchmark Dataset for Multi-Granularity Visual Parsing of Physics Experiments}, 
      author={Minghao Zou and Qingtian Zeng and Yongping Miao and Shangkun Liu and Zilong Wang and Hantao Liu and Wei Zhou},
      year={2025},
      eprint={2506.06631},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2506.06631}, 
}
```

## ⚠️ Disclaimer
**The PhysLab dataset provided by this project is collected and annotated based on specific experimental scenarios and methods, but the dataset may contain a certain degree of deviation, incompleteness or erroneous information.**




