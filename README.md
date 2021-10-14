# Real Time Pose Estimation on Jetson Nano

🔴 Project Name : Real Time Pose Estimation on Jetson Nano

<br  />

📷 About Project -  

🚩   In this project, let's see a new computer vision, machine learning and, artificial intelligence based project. Real time Body pose estimation on, NVIDIA Jetson Nano development Board.  

<br  />

📜 Parts Required  

1. NVIDIA Jetson Nano Developer Kit  
2. AC8265 Wireless NIC Module  
3. UHS I/II High Speed microSD Card (64GB/32GB)  
4. Camera Module - USB Webcam (Logitech C270) or 
5. Camera Module - CSI (RPi Camera / IMX219 Series)  
6. LCD/LED Display Monitor with HDMI input capability  
7. Good Quality HDMI Cable    
8. Micro USB Cable  
9. Power Supply Adaptor - 5 Volts, 4Amps  

<br  />

🌐 YouTube Video Links -  

IoT based smart Lock V2.0    ▶️  [https://youtu.be/y38Mze43w-A]  

<br  />

||==========================================================================||  
🔗 *Important Links* 🔗  

📌 ⏩  https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit#intro  
📌 ⏩  https://developer.nvidia.com/embedded/jetpack  
📌 ⏩  https://docs.nvidia.com/deeplearning/frameworks/user-guide/index.html  
📌 ⏩  https://ngc.nvidia.com/catalog/containers  
📌 ⏩  https://github.com/NVIDIA-AI-IOT/trt_pose  
📌 ⏩ https://github.com/NVIDIA-AI-IOT/jetcam  
📌 ⏩ https://github.com/NVIDIA/nvidia-docker  

||==========================================================================||

Commands Used  
  
https://github.com/NVIDIA-AI-IOT/trt_pose  


apt-get update  

wget https://nvidia.box.com/shared/static/p57jwntv436lfrd78inwl7iml6p13fzh.whl -O torch-1.9.0-cp36-cp36m-linux_aarch64.whl  

apt-get install -v python3-pip libopenblas-base libopenmpi-dev  

pip3 install -v Cython  

pip3 install -v numpy  

pip3 install -v numpy torch-1.9.0-cp36-cp36m-linux_aarch64.whl  

apt-get install -v libjpeg-dev zlib1g-dev libpython3-dev libavcodec-dev libavformat-dev libswscale-dev  

git clone --branch v0.10.0 https://github.com/pytorch/vision torchvision  

cd torchvision  

export BUILD_VERSION=0.10.0  

python3 setup.py install --user  

cd ../  



git clone https://github.com/NVIDIA-AI-IOT/torch2trt  

cd torch2trt  

python3 setup.py install --plugins  

pip3 -v install tqdm cython pycocotools  

apt-get -v install python3-matplotlib  

pip3 -v install scipy  

pip3 -v install scikit-learn  

git clone https://github.com/NVIDIA-AI-IOT/trt_pose  

cd trt_pose  

sudo python3 setup.py install  