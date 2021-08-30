**AI chat bot**

## Table of contents

- [Table of contents](https://github.com/satya-500/ai_bot#table-of-contents)
- [Description](https://github.com/satya-500/ai_bot#description)
- [Installation](https://github.com/satya-500/ai_bot#installation)
 
 - [Start app locally](https://github.com/satya-500/ai_bot#start-app-locally)

## Description

**Artificial intelligence  Chatbot**


## Installation

### dependencies
NVIDIA driver

```
$ wget https://developer.download.nvidia.com/compute/cuda/11.4.1/local_installers/cuda-repo-debian10-11-4-local_11.4.1-470.57.02-1_amd64.deb
$ sudo dpkg -i cuda-repo-debian10-11-4-local_11.4.1-470.57.02-1_amd64.deb
$ sudo apt-key add /var/cuda-repo-debian10-11-4-local/7fa2af80.pub
$ sudo add-apt-repository contrib
$ sudo apt-get update
$ sudo apt-get -y install cuda
$ sudo apt install nvidia-cuda-toolkit
```

#### install using pip3

```
$ pip3 install -r requirements.txt
```


## Start app locally

```
$ python3 train.py
$ python3 chat.py
```