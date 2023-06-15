#FROM pytorch/pytorch:1.11.0-cuda11.3-cudnn8-devel
FROM pytorch/pytorch:1.8.1-cuda10.2-cudnn7-devel

# needed to allow apt update
RUN apt-key adv --keyserver keyserver.ubuntu.com --recv-keys A4B469963BF863CC

#RUN apt update && apt install -y \
#	git \
#    	ninja-build \
#    	libglib2.0-0 \
#    	libsm6 \
#    	libxrender-dev \
#    	libxext6 \
#    	libgl1-mesa-glx \
#    	vim \
#	curl \
#	libboost-dev \
#	tmux \
#	freeglut3-dev \
#   	unzip \
#	wget \
#	libusb-1.0-0-dev \
#	libssl1.0-dev

# install python dependencies
#RUN pip install --ignore-installed \
#	chumpy==0.70 \
#	imageio==2.9.0 \
#	jpeg4py==0.1.4 \
#	joblib==1.0.0 \
#	kornia==0.4.1 \
#	loguru==0.5.3 \
#	matplotlib==3.3.3 \
#	numpy==1.19.5 \
#	omegaconf==2.0.6 \
#	opencv-python==4.5.1.48 \
#	open3d \
#	Pillow \
#	PyOpenGL==3.1.0 \
#	pyrender==0.1.43 \
#	pytorch-lightning==1.3.0rc1 \
#	scikit-image==0.18.1 \
#	scikit-learn==0.24.0 \
#	scipy==1.6.0 \
#	sklearn==0.0 \
#	smplx==0.1.27 \
#	torch==1.7.1 \
#	torchgeometry==0.1.2 \
#	torchmetrics==0.2.0 \
#	torchvision==0.8.2 \
#	tqdm==4.55.1 \
#	trimesh==3.9.1 \
#	yacs==0.1.8 \
#	fvcore \
#	nflows==0.14 \
#	PyYAML==5.3.1

#RUN cd /shapy/attributes/ && pip install .

#RUN cd /shapy/mesh-mesh-intersection/ && pip install .

#RUN git clone https://github.com/pyenv/pyenv /root/.pyenv

#RUN /root/.pyenv/bin/pyenv install -v 3.8.2

RUN mkdir -p /shapy

WORKDIR /shapy
