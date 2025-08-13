## PestNet: Hierarchical Scaled Dot-Product Attention for Insect Pest Detection

#### Overall architecture of the proposed PestNet model for insect pest detection
<img width="968" height="505" alt="image" src="https://github.com/user-attachments/assets/7a5517c3-4f62-479e-abb5-415f0ea958ee" />


#### Dataset
| Dataset | Download | Class # | Image # |
|---------|----------|---------|---------|
| IP102   | [Drive](https://drive.google.com/drive/folders/1svFSy2Da3cVMvekBwe13mzyx38XZ9xWo?usp=sharing)   | 102 | 75,222 |
| R2000   | [GitHub](https://github.com/awsomespark/R2000)        | 16  | 2,046  |

#### Training
Hyperparameters:
* Epochs: 200
* Batch size: 16
* Pre-train: None
  
| Dataset | mAP@50 | mAP@50:95 |
|---------|--------|----------|
| IP102   | 69.7   | 44.9     |
| R2000   | 82.6   | 68.2     |

#### IP102 Training Plot


#### R2000 Training Plot

<img width="2400" height="1200" alt="results" src="https://github.com/user-attachments/assets/50455831-9020-4f70-9d47-60b60ff36883" />

#### Visualization
![ours](https://github.com/user-attachments/assets/78cab0a6-a7c7-41cb-9c38-2d1000f725a4)
