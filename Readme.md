# A Progressive Global-Local Shape Transform Network for Face-to-skull Translation

We propose a novel progressive global-local shape transformation network (ProGL-Net) for face-to-skull translation, which hierarchically learns the complex mapping between facial and skull geometries through three successive stages: global initialization, local refinement, and final global adjustment. In the global initialization stage, a point displacement sub-network generates a coarse skull point cloud from the input facial point cloud. In the local refinement stage, a point cloud patch partition module is developed to divide the combined coarse skull and facial shapes into anatomically relevant face–skull patches, which are individually refined by a patch-specific point displacement sub-network. The refined patches are then merged to produce a more detailed skull shape. Finally, in the global adjustment stage, an adjustment sub-network further optimizes the merged skull structure, ensuring overall geometric coherence and anatomical fidelity. Extensive experiments on a comprehensive dataset containing both normal and abnormal subjects demonstrate that our method achieves state-of-the-art performance, outperforming existing approaches in terms of global structural accuracy and preservation of local anatomical details.

## Environment
The code was developed and tested under the following environment:
- Python: 3.10.14
- CUDA: 11.7
- PyTorch: 1.13.0
- PyTorch3D: 0.7.5
- NumPy: 1.26.4
- SciPy: 1.14.0
- scikit-learn: 1.5.0
- Matplotlib: 3.8.4
- Trimesh: 4.6.6
- PyTorch Lightning: 1.8.0
- tqdm: 4.66.4

## Code is coming soon...
