# VGNet: Multimodal Feature Extraction and Fusion Network for 3D CAD Model Retrieval
## Authors: Feiwei Qin, Gaoyang Zhan, Meie Fang, C.L.Philip Chen, Ping Li

![](https://github.com/xzzz011/VGNet) ![](https://github.com/xzzz011/VGNet)

## Abstract
*The reuse of 3D CAD models is crucial for industrial manufacturing as it shortens development cycles and reduces costs. Deep learning based 3D model retrieval has made significant progress. There are many representations for 3D models, among which multi-view representation has demonstrated superior retrieval performance. However, directly applying these 3D model retrieval approaches to 3D CAD model retrieval may result in issues, such as losing engineering semantic and structural information. In this paper, we find that multi-view and B-rep can complement each other and therefore propose the VGNet (View Graph neural Network), which effectively combines multi-view and B-rep to accomplish 3D CAD model retrieval. More specifically, based on the characteristics of the regular shape of 3D CAD models and the richness of attribute information in the B-rep attribute graph, we design two feature extraction networks for each modality separately. Meanwhile, to explore the latent relationship between multi-view and B-rep attribute graph, the multi-head attention enhance module is designed. Furthermore, the multimodal fusion module is adopted to make the joint representation of 3D CAD models more discriminative by using a correlation loss function. Experiments are carried out on the real manufacturing 3D CAD dataset and public dataset to validate the effectiveness of the proposed approach.*


---

## Installation

1. Create Conda virtual environment:

    ```
    conda create --name VGNet python=3.7
    conda activate VGNet
    ```
    
2. Clone this repository:
    ```
    git clone https://github.com/xzzz011/VGNet
    ```
    
3.  Install the following requirements:
    ```
    conda install pytorch==1.11.0 torch-geometric=2.3.1 torchaudio==0.13.1 -c pytorch
    conda install -c conda-forge tensorboardx
    conda install -c anaconda scikit-learn
    conda install -c conda-forge matplotlib
    conda install -c anaconda scikit-image
    conda install -c conda-forge pythonocc-core
    ```

# Usage

