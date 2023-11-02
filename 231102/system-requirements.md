# System requirements

### Minimal requirements

OS: Windows 10 x64, Windows Server 2016 x64, Windows Server 2019 x64\
CPU: Intel i7-7700, AMD Ryzen 5 3600\
RAM: 8 GB\
GPU: NVIDIA GTX 750 Ti

Note please that for NVIDIA-powered encoding options (NVENC) there is a limitation on the maximal number of concurrent sessions. Please refer to this table:\
[https://developer.nvidia.com/video-encode-and-decode-gpu-support-matrix-new](https://developer.nvidia.com/video-encode-and-decode-gpu-support-matrix-new)

For example, if you use GTX 1070 you can record up to 3 streams with NVENC.

### Cloud-based configuration reference

Amazon EC2 g4dn.16xlarge can handle 9 FullHD recordings to ProRes Proxy with 35-40% CPU load.
