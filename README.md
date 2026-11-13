# 🎥 UVOS: Unsupervised Video Object Segmentation

A research-focused framework for **Unsupervised Video Object Segmentation (UVOS)** using **contrastive learning** on benchmark datasets including **DAVIS**, **FBMS**, and **YT-OBJ**.

### VISE web app

**VISE (Video Intelligence and Segmentation Engine)** is the web application built on this
framework: upload a video, VISE segments the moving objects, and the result can be played
back and downloaded as a video or image.

![VISE web app demo](demo/vise-demo.gif)

[Watch the full demo (MP4)](demo/vise-demo.mp4)

### Segmentation result

![BiCycle Demo](BiCycle.gif)

## 🧠 Key Idea

We aim to segment primary foreground objects in videos without manual annotations, leveraging:
- Temporal consistency  
- Appearance contrastive features  
- Flow-guided supervision  
- No ground-truth masks required

## 🛠️ Tech Stack

- Python, PyTorch  
- RAFT for Optical Flow

## 📂 Datasets Used

- [DAVIS 2016](https://davischallenge.org/davis2016/code.html)  
- [FBMS](https://github.com/tfzhou/ASE-Fast)  
- [DUTS](https://dut-omron.github.io/DUTS)  
- [YouTube-Objects](https://github.com/liulu112601/MBNM)

**FINAL CODE COMING SOON!**
