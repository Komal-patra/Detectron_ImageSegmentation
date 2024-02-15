
In order to create the new conda environment, we can run the below command:
```
    conda create -n DL python=3.8
```

To activate the conda environment:
```
    conda activate DL
```

In order to annotate the image for Image Segmentation:
```
    pip install labelme
```

To run: labelme
```
    python labelme2coco.py label_mask/
```

