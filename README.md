# MAIS
MAIS 2020 Hackathon

Implement ResNet for human motion recognition by OpenCV library and the Python programming language. The model we’re using for human activity recognition comes from Hara et al.’s 2018 CVPR paper, Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet?

To run the code on terminal: 
python squat.py -m resnet-34_kinetics.onnx -c action_recognition_kinetics.txt -i squat_test.mp4

Pretrained model:  resnet-34_kinetics.onnx 
It is provided in  "Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet?" (CVPR 2018)

Motion classes:  action_recognition_kinetics.txt

Video:  squat_test.mp4


