# Federated Learning
<b> MUIC ICCS311 Final Project: Federated Learning </b>

# What I have learned
### 1. The Concept of Fedreated Learning:
   -  A machine learning approach where an algorithm is trained across multiple decentralized devices holding local datasets with exchanging the data samples.
   -  Unlike traditional machine learning, the raw data is not aggregated to a centralized server; rather, it is left distributed on the client devices.
   -  Federated Learning Applications are used on ... 
      -  Internet of Things (IoT)
      -  Smartphones

### 2. Federated Learning Implementation using PyTorch and Flower
   -  Train a Convolutional Neural Network on CIFAR10
   -  1 server, 2 clients with the same model
   -  Logic: Using local datasets, each client produces weight updates for the model, which will then send to a server to aggregate and improve the model. And the improved model will then send back to each client.  
```
Project Setup
   -  server.py
   -  client.py
```
```
Package Requirements
   -  Python3
   -  Pytorch
   -  Torchvision
   -  Flower
```

### 3. Intel VTune Profiler
   -  Tool for code analysis
   -  Shows the CPU utilization, the time spent on each function call, etc
   -  Guide to performance bottleneck

# Code analysis
<b> System Information </b>
```
CPU: 11th Gen Intel® Core™ i7-1165G7 @ 2.80GHz, 4 Cores 8 Threads.
RAM: 16 GB
OS: UBUNTU 20.04.2 LTS
Python Verison: Python 3.8.10
```
