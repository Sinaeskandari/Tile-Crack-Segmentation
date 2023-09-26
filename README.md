# Tile-Crack-Segmentation

Final project of Computer Vision course.

Implementation of U-Net model to segment cracks and anomalies in tile pictures.

The following steps were done for this project

1. We initiate the process by matching the image of the tile's design with the image of the manufactured tile. This involves identifying key points in both images to establish correspondence. This step aids in aligning the design with the actual tile, even in cases of slight variations in angle or scale.
   
2. After obtaining the matched data, we employ it to train a unet model. This model is trained to recognize areas on the tile where cracks are present. It utilizes the information gathered during the image matching phase to enhance the accuracy of crack detection.
