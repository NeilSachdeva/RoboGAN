
# Using Conditional Generative Adversarial Networks to Reduce the Effects of Latency in Robotic Telesurgery

This work was coded by [Neil Sachdeva](https://www.linkedin.com/in/neil-sachdeva-221393177) with the help of the [Machine Perception and Cognitive Robotics Lab](https://mpcrlab.com/) and has published at the [Springer Journal of Robotic Surgery](https://link.springer.com/article/10.1007/s11701-020-01149-5). 

The pre-print paper, working code, and trained models have all been uploaded for open-source use. 

Original models can be found at https://phillipi.github.io/pix2pix/ and the dataset at https://endovissub-instrument.grand-challenge.org/Data/.

Our pre-trained generator (latest_net_G.pth) and pre-trained discriminator (latest_net_D.pth) models can be downloaded from the following [Google Drive folder](https://drive.google.com/drive/folders/10vTtnkjxbrl1YOpsY6vXsOOxwLyXHETp?usp=sharing).

If you use any of our code or models for your research, please cite our paper (link above).

Abstract:
The introduction of surgical robots brought about advancements in surgical procedures. The applications of remote telesurgery range from building medical clinics in underprivileged areas, to placing robots abroad in military hot-spots where accessibility and diversity of medical experience may be limited. Poor wireless connectivity may result in a prolonged delay, referred to as latency, between a surgeon’s input and action a robot takes. In surgery, any micro-delay can injure a patient severely and in some cases, result in fatality. One way to increase safety is to mitigate the effects of latency using deep learning aided computer vision. While the current surgical robots use calibrated sensors to measure the position of the arms and tools, in this work we present a purely optical approach that provides a backup measurement of the tool position in relation to the patient's tissues. This research aimed to produce a neural network that allowed a robot to detect its own mechanical manipulator arms. A conditional generative adversarial network (cGAN) was trained on 1107 frames of a mock gastrointestinal robotic surgery from the 2015 EndoVis Instrument Challenge and corresponding hand-drawn labels for each frame. When run on new testing data, the network generated near-perfect labels of the input images which were visually consistent with the hand-drawn labels and was able to do this in 299 milliseconds. These accurately generated labels can then be used as simplified identifiers for the robot to track its own controlled tools. These results show potential for a conditional GANs as a reaction mechanism such that the robot can detect when its arms move outside the operating area in a patient. This system allows for more accurate monitoring of the position of surgical instruments in relation to the patient's tissue, increasing safety measures of a telesurgery system.
 

 
