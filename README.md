# LG-DGL
Code for Local to Global  Dynamic Graph Learning

![框架图](https://github.com/user-attachments/assets/9f58920d-795c-4247-b48a-1557cec7cb5d)

(1) The L-DGL module captured the local spatiotemporal dynamics within a single time window by temporal convolution, while the G-DGL module captured the global spatiotemporal dynamics by fusing features among all time windows.

(2) LG-DGL extracted complex brain dynamic features from BFCNs on various templates, while the brain attention readout (BARO) identified discriminative ROIs related to neurodevelopmental disorders. 

(3) LG-DGL was validated on the publicly available ABIDE-II and ADHD-200 datasets. The experimental results demonstrated its superiority over some state-of-the-art methods for ASD and ADHD diagnosis. The fusion of features among imaging data and non-imaging data further improved diagnostic accuracy. 


# Requirement
pytorch 2.1.0

python 3.11.5

cuda 12.1

numpy 1.26.2

pandas 2.1.3

scikit-learn 1.3.2
