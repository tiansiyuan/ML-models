Table Transformer is actually a DETR model - by Microsoft Research (which is part of Transformers) to perform table detection and table structure recognition on documents.

DETR is short for DEtection TRansformer, and consists of a convolutional backbone (ResNet-50 or ResNet-101) followed by an encoder-decoder Transformer. It can be trained end-to-end to perform object detection (and panoptic segmentation).The main contribution of DETR is its simplicity: compared to other models like Faster R-CNN and Mask R-CNN, which rely on several highly engineered things like region proposals, non-maximum suppression procedure and anchor generation, DETR is a model that can simply be trained end-to-end, and fine-tuned just like you would fine-tune BERT. This is possible due to the use of a clever loss function, the so-called bipartite matching loss.

The notebook is taken from [here](https://github.com/NielsRogge/Transformers-Tutorials/blob/master/Table%20Transformer/Using_Table_Transformer_for_table_detection_and_table_structure_recognition.ipynb).

It requires 1 CPU/2G RAM, but no GPU.

Use the following custom Docker image when creating notebook server:

projects.registry.vmware.com/models/notebook/inference:cv-pytorch-cpu-v1
