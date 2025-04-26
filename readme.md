## 为修复在更高版本的d2l版本中课程代码中出现的报错:

`
AttributeError: module 'd2l.torch' has no attribute 'train_ch3'
`

使用方法：将新的`torch.py`文件覆盖到d2l对应源码
找源：`pip show d2l`, 找到d2l包所在文件夹位置,将新的`torch.py`文件覆盖即可
###### *（缺少的函数：`train_ch3`, `train_epoch_ch3`,  `evaluate_accuracy`）

