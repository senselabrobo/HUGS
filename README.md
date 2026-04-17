# HUGS: Hybrid-Uncertainty-Guided Active 3D Reconstruction with Gaussian Splatting


<p align="center">
<img width="1477" height="623" alt="image" src="https://github.com/user-attachments/assets/4fad5a05-a83f-4e4c-abb0-39984ef00260" />
</p>

We proposes HUGS, a hybrid-uncertainty-guided active 3D reconstruction framework built on Gaussian Splatting. 

<p align="center">
<img width="721" height="326" alt="image" src="https://github.com/user-attachments/assets/9ea85827-eabf-47af-a993-1356015e2966" />
</p>

The proposed method jointly models uncertainty from two complementary scene representations: a Gaussian map that captures surface-level geometric and appearance reliability, and a voxel map that describes uncertain occupancy and unexplored spatial structure. 

<p align="center">
<img width="1246" height="390" alt="image" src="https://github.com/user-attachments/assets/f4f6c3c0-0e3c-459e-9462-c44745f38ade" />
</p>

These two forms of uncertainty are fused into a unified hybrid uncertainty map to guide candidate viewpoint generation and next-best-view selection.


## Datasets
We evaluate HUGS on two widely used indoor scene datasets: [Replica](https://github.com/facebookresearch/replica-dataset) and [Gibson](https://github.com/stanfordvl/gibsonenv)


## Experiment Results
<p align="center">
<img width="1840" height="528" alt="image" src="https://github.com/user-attachments/assets/d625168a-ceda-4066-9d96-8dce499757d7" />
</p>

HUGS achieves improved average reconstruction performance with a 30-second reduction in processing time.


## Acknowledgement
Parts of the code are based on [ActiveGS](https://github.com/dmar-bonn/active-gs). We thank the authors for open-sourcing their code.
