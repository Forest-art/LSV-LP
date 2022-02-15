# LMV-LP

## Download
#### It can be downloaded from:
* [BaiduYun Drive]()
* It is worth noting that LMV-LP can only be used for academic research, not for commercial use. If you need the data download password, please contact us by email, and indicate your work unit and download purpose.

## Structure
```
LMV-LP
├── test
│   ├── jsons
│   │   ├── move2move
│   │   │   ├── 1
│   │   │   │   ├── frame1.json
│   │   │   │   ├── ...
│   │   ├── move2static
│   │   └── static2move
│   └── videos
│       ├── move2move
│       │   ├── 1
│       │   │   ├── frame1.jpg
│       │   │   ├── ...
│       ├── move2static
│       └── static2move
├── train
│   ├── jsons
│   │   ├── move2move
│   │   ├── move2static
│   │   └── static2move
│   └── videos
│       ├── move2move
│       ├── move2static
│       └── static2move
└── validation
    ├── jsons
    │   ├── move2move
    │   ├── move2static
    │   └── static2move
    └── videos
        ├── move2move
        ├── move2static
        └── static2move
```

## Annotation

* 'id': the id of the car and its plate in this video;
* 'carBox': the bounding box of the car in this frame;
* 'licPoly': the coordinates of the four vertices of the current license plate;
* 'licNumber': the number of the current license plate;

## Compare
![compare](imgs/compare.png)

## Samples
* [Google Drive](https://drive.google.com/file/d/1udqRddpJZMpTdHHQdwZRll6vaYALUiql/view?usp=sharing)

## Demo
![demo](imgs/demo.png)

## Label Toolkit
* [LP_Labler](https://github.com/Elin24/license_labeler)
  
## Acknowledgement

If you have any problems about LMV-LP, please contact xiaochenglu1997@gmail.com.
Please cite the paper _《LMV-LP: A Large-Scale Multi-Source Video-Based License Plate Dataset》_, if you benefit from this dataset.