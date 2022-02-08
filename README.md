# super_resolution


```
docker run -it --name <NAME> --gpus '"device=0,1,2,3,4,5,6,7"' -v ~:/work --shm-size=2g  nvidia/cuda:10.2-devel-ubuntu18.04 bash
```


```
pip install -r requirements.txt
```

```
python inference_realesrgan.py -n RealESRGAN_x4plus -i inputs --face_enhance
```
