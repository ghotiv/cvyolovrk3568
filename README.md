# cvyolovrk3568
video yolov for rk3568

# Use
- debain 10 in rk3568
- https://github.com/rockchip-linux/rknpu2/blob/master/runtime/RK356X/Linux/librknn_api/aarch64/librknnrt.so
- scp librknnrt.so /usr/lib
- https://github.com/rockchip-linux/rknn-toolkit2/blob/master/rknn_toolkit_lite2/packages/rknn_toolkit_lite2-1.5.0-cp37-cp37m-linux_aarch64.whl
- pip install *.whl
- python vido2jpg.py
- create test.jpg