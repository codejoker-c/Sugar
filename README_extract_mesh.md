## Quickstart
run extract_mesh.py with command:
```shell
python extract_mesh.py -s ./load/scene -c ./load/scene_gaussian/ -o output/path --use_vanilla_3dgs true -i 3000
```
1. substitute the camera.json under ./load/scene_gaussian with your camera config 
2. add gaussians file under ./load/scene_gaussian/point_cloud
3. modify -i parameters to your gaussians training iteration, remember to be consistent with directory name under point_cloud