> The pytorch-AdaIN file (test.py) has been modified with addition of a parameter (--style_interpolation_weights) for the Attempt 4 execution.

> Every "Attempt x" folder contains pytorch-AdaIN net: To get an idea of ​​the generated database, "content" folder 
  has 4 sample image of "VOC2007" database and "style" folder has style image/s used to generate database for "Attempt x" considered.

> Every "Attempt x" folder contains "pytorch-AdaIN test parameters.txt". 
  This file contains parameters used to generate database for "Attempt x" considered.

> Every "Attempt x" folder contains "vgg_ssd300_voc0712.yaml". 
  This file contains parameters used to finetune SSD for "Attempt x" considered.
  SSD code is the same used on "Step 1". The model_final produced by SSD finetune attempt is the only difference.
  Clipart1k database folder name is changed to "VOC2007" and included into the database folder to test SSD.