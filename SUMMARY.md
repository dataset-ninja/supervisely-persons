**Supervisely Persons** is a dataset for instance segmentation, semantic segmentation, and object detection tasks. It is applicable or relevant across various domains. 

The dataset consists of 5711 images with 6884 labeled objects belonging to 3 different classes including *person_poly*, *person_bmp*, and *neutral*.

Images in the Supervisely Persons dataset have pixel-level instance segmentation annotations. Due to the nature of the instance segmentation task, it can be automatically transformed into a semantic segmentation (only one mask for every class) or object detection (bounding boxes for every object) tasks. All images are labeled (i.e. with annotations). There are 13 splits in the dataset: *ds6* (1988 images), *ds8* (1407 images), *ds2* (690 images), *ds7* (533 images), *ds1* (375 images), *ds11* (227 images), *ds5* (135 images), *ds9* (129 images), *ds3* (73 images), *ds4* (59 images), *ds12* (33 images), *ds13* (33 images), and *ds10* (29 images). Additionally, some images are marked with ***multipart-person*** and ***not-marked-people*** tags. The dataset was released in 2020 by the <span style="font-weight: 600; color: grey; border-bottom: 1px dashed #d3d3d3;">Supervisely</span>.

Here is the visualized example grid with animated annotations:

[animated grid](https://github.com/dataset-ninja/supervisely-persons/raw/main/visualizations/horizontal_grid.webm)
