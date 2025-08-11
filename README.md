# PestNet: Hierarchical Scaled Dot-Product Attention for Insect Pest Detection

### Overall architecture of the proposed PestNet model for insect pest detection
<img width="687" height="360" alt="image" src="https://github.com/user-attachments/assets/edec43f5-3357-4f7e-96d2-d3a7cf675197" />


### Inference
'''
yolo task=detect mode=predict model=weights/best.pt source=input/images save=True
'''

### Quantitative results of different methods on the R2000 dataset:
<img width="316" height="364" alt="image" src="https://github.com/user-attachments/assets/592d2104-c8a7-46d2-afb1-19cbe3b8256d" />

