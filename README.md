# yolo_prune

1. set weights &lt; 0.01 to 0; 

2. pruning output feature maps according to BN scales (darknet prune)

3. conv connection sparsification by using a mask of 0 and 1

The first function is based on the work of https://github.com/hjimce/compress_yolo

The second function is pruning feature maps according to BN scales parameter,

and the regularization method is L1 NORM

train result is as below:

![Image text](https://github.com/ArtyZe/yolo_prune/blob/master/result.png)

If you want to use my code, please let me know
