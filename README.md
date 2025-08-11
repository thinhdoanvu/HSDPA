## PestNet: Hierarchical Scaled Dot-Product Attention for Insect Pest Detection

#### Overall architecture of the proposed PestNet model for insect pest detection
<img width="687" height="360" alt="image" src="https://github.com/user-attachments/assets/edec43f5-3357-4f7e-96d2-d3a7cf675197" />

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


#### Visualization
![ours](https://github.com/user-attachments/assets/78cab0a6-a7c7-41cb-9c38-2d1000f725a4)
