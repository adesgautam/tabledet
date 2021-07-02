# Used Matterport's version of Mask RCNN

### The original implementation of Matterport is [here](https://github.com/matterport/Mask_RCNN)

Using Mask-RCNN train your own Table Structure Recognition model

It also has a super-resolution model to enhance the image quality before sending to OCR.
Reference is from [here](https://github.com/amanshenoy/image-super-resolution)

For OCR Google's Tesseract is used here.

The datasets are provided under `dataset_custom` and `dataset_marmot`

Additions:
* A Flask based UI for easy testing of the trained model.
* To test the model use `extract_tables.ipynb`

### The pretrained weights are [here](https://drive.google.com/file/d/1A75braLW3SrweJzXWl0BAJePdM4BEY4s/view?usp=sharing). Put it in the `models` directory
