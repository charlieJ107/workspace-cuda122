FROM nvidia/cuda:12.2.2-cudnn8-devel-ubuntu22.04

RUN apt update && apt install -y wget python3 python3-pip sudo curl build-essentials git && \
    apt clean && rm -rf /var/lib/apt/lists/*