# Object Detection Cold Start

## How to run

```sh
bash install.sh
```

## Description

Those scripts contain steps for Ubuntu 22.04 cold start setup

1. Install reuqirement packages via apt
Check scripts/apt.sh to modify it
- python3-pip
- python3-venv
- nvidia-driver-535
- nvidia-utils-535
- nvidia-cuda-toolkit

2. Create virtual environment for object detecion task
3. Install python packages via pip
uncoment requirements_strict.txt if you need to install specific packages

Main packages:
- jupyter
- matplotlib
- numpy
- scikit-build
- scikit-learn
- scipy
- torch
- opencv-python


4. Update shell environment

# Status

Till release:
- [x] Add basic yolo train code
- [x] Add automatization bash scripts
- [ ] Add tools install helper (like CVAT and TensorBoard)
- [ ] Add training tips
- [ ] Add runs output explanation
- [ ] Test it again
