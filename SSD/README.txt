Autonomous Vehicles: Assisted Driving with CARLA 

Please find the folder structure for the source code given below:

.
├── README.txt
└── training_demo
    ├── annotations
    │   └── label_map.pbtxt
    ├── export_tflite_graph_tf2.py
    ├── exported_models
    ├── exporter_main_v2.py
    ├── generate_tfrecord.py
    ├── images
    │   ├── inference_image.png
    │   ├── test
    │   └── train
    ├── model_main_tf2.py
    ├── models
    │   ├── faster_rcnn
    │   │   └── pipeline.config
    │   ├── frcnn_export
    │   │   ├── checkpoint
    │   │   │   ├── checkpoint
    │   │   │   ├── ckpt-0.data-00000-of-00001
    │   │   │   └── ckpt-0.index
    │   │   ├── pipeline.config
    │   │   └── saved_model
    │   │       ├── assets
    │   │       ├── saved_model.pb
    │   │       └── variables
    │   │           ├── variables.data-00000-of-00001
    │   │           └── variables.index
    │   ├── ssd
    │   │   └── pipeline.config
    │   └── ssd_export
    │       ├── checkpoint
    │       │   ├── checkpoint
    │       │   ├── ckpt-0.data-00000-of-00001
    │       │   └── ckpt-0.index
    │       ├── pipeline.config
    │       └── saved_model
    │           ├── assets
    │           ├── saved_model.pb
    │           └── variables
    │               ├── variables.data-00000-of-00001
    │               └── variables.index
    └── pre-trained-models


Please populate the /images directory with the corresponding Test and Train dataset found on: https://github.com/DanielHfnr/Carla-Object-Detection-Dataset

For further information and implementation of each model (YOLO, SSD, Faster RCNN), please refer to the respective Python Notebooks. 


