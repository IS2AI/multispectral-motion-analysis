# Thermal-Visual Human Pose Estimation with YOLO11-pose. 
<img src="https://github.com/IS2AI/multispectral-motion-analysis/blob/main/abstract.png">

Download checkpoints (nano, small, medium, large, and x-large) from [Google Drive](https://drive.google.com/file/d/1dGsVGgy-AUoQUraY2azS1dq6Ax2_UilY/view?usp=sharing).

```
pip install ultralytics
```

## Inference
```
from ultralytics import YOLO

# load one of the models
model = YOLO(PATH_TO_MODEL)  

# Predict with the model
results = model.predict(PATH_TO_IMAGE, save=True)  
```

## References
1. https://github.com/ultralytics/ultralytics
2. https://docs.ultralytics.com/tasks/pose/
3. https://github.com/IS2AI/OpenThermalPose
