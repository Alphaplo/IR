
Tree detection

Darknet is an open source neural network used for object detection. The executed file of detection is darknet.exe in the directory 
darknet-master\build\darknet\x64. You should run it from console. The weight of network trained on real forests is in the directory 
darknet-master\build\darknet\x64\backup. The weight trained on the synthetic dataset locates in darknet-master\build\darknet\x64\backup2.

DenseDepth is a depth estimation network based on keras. The model of network trained on syhthetic dataset is uploaded in Releases. You
should unzip it and put them in the directory DenseDepth\models\1589218727-n53-e20-bs4-lr0.0001-densedepth_nyu.
The script file of test is test.py in DenseDepth-master.

AdepNet is a semantic segmentation network based on Tensorflow. The model of network trained on syhthetic dataset is uploaded in Releases.
You should unzip it and put them in the directory AdapNet-pp\init_checkpoint\UEdataset. The file of test is evaluate.py. 
The test result is in AdapNet-pp-master\images\test_synthetic.

