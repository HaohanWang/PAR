# Patch-wise Adversarial Regularization

![PAR](PAR.jpg "PAR")

### Example Usage of the Regularization

- [example/AlexNet.py](https://github.com/HaohanWang/PAR/blob/master/example/alexNet.py)
    - Example usuage of how to plug in our idea into existing AlexNet
    - One only need to concern with the codes controlled by the boolean varialable adv_flag, including:
        -  [Line 182](https://github.com/HaohanWang/PAR/blob/master/example/alexNet.py#L182)
        -  [Line 291](https://github.com/HaohanWang/PAR/blob/master/example/alexNet.py#L291)
        -  [Line 317](https://github.com/HaohanWang/PAR/blob/master/example/alexNet.py#L317)
- utility/ 
    - Other codes needed to run the AlexNet, not part of the contributions of this repository
    
### Replication

- This repository is made for a clear demonstration of our method. For replication of the numbers in our paper, please visit: [HaohanWang/PAR_experiments](https://github.com/HaohanWang/PAR_experiments)
    
### Data

- For the ImageNet-Sketch Data, please visit: [HaohanWang/ImageNet-Sketch](https://github.com/HaohanWang/ImageNet-Sketch)
    
### Reference

If you find this method helpful, please consider cite: 
    
&emsp; _Haohan Wang, Songwei Ge, Eric P. Xing, and Zachary C. Lipton. "[Learning Robust Global Representations by Penalizing Local Predictive Power](https://arxiv.org/abs/1905.13549)" (NeurIPS 2019)_

### Other Resources

- You may be also interested in [HaohanWang/HEX](https://github.com/HaohanWang/HEX)

