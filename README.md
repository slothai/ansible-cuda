# Ansible CUDA installation from source

[![Build Status](https://travis-ci.org/slothai/ansible-cuda.svg?branch=master)](https://travis-ci.org/slothai/ansible-cuda)
[![Ansible Galaxy](https://img.shields.io/ansible/role/16763.svg)](https://galaxy.ansible.com/slothai/cuda/)

This role installs and configures NVIDIA [CUDA](https://developer.nvidia.com/cuda-zone) 8.0 library, used for GPU computations.

### Install

```bash
ansible-galaxy install slothai.cuda
```

## Development

Check CUDA:

```bash
$ lspci | grep -i nvidia
02:00.0 3D controller: NVIDIA Corporation GK107M [GeForce GT 750M] (rev a1)
```

See also:

* Cuda 8 performance overview: http://developer.download.nvidia.com/compute/cuda/compute-docs/cuda-performance-report.pdf
* Detailed installation: http://docs.nvidia.com/cuda/cuda-installation-guide-linux/#axzz4cxFv4kEp
* Checksum file: http://developer.download.nvidia.com/compute/cuda/8.0/secure/Prod2/docs/sidebar/md5sum.txt?autho=1491026907_cc5ed9508e9d89f15c5eb34a1d8a87f7&file=md5sum.txt

### License

MIT
