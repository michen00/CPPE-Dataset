# Models for Mobile and Edge devices

This section contains an exhaustive list of models for mobile and edge devices
trained on the CPPE-5 (Medical Personal Protective Equipment) dataset that are
currently available and you could start using any of these models very easily.

#### Notes:

- All the models can also be trained from scratch using the configs provided in the `configs` or `baselines` directory.
- The metrics are the same as the COCO object detection metrics, more information about this could be found in the original paper.
- All the model here use the channels first format.

|   Method    | AP<sup>box</sup> | TF Lite | TF Lite (FP 16 quantized) | TFJS | TFJS (FP 16 quantized) | TFJS (uint16 quantized) | TFJS (uint8 quantized) |
|:----------:|:------------:|:--------:|:----------------------------:|:--------:|:----------------------------:|:----------------------------:|:----------------------------:|
| SSD | 29.5 | [bucket](https://storage.googleapis.com/cppe-5/trained_models/ssd/lite/model.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/ssd/lite/model_f16.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/ssd/tfjs/ssd_tfjs.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/ssd/tfjs/ssd_fp16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/ssd/tfjs/ssd_uint16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/ssd/tfjs/ssd_uint8.tar.gz) |
| YOLO | 38.5 | [bucket](https://storage.googleapis.com/cppe-5/trained_models/yolo/lite/model.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/yolo/lite/model_f16.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/yolo/tfjs/yolo_tfjs.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/yolo/tfjs/yolo_fp16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/yolo/tfjs/yolo_uint16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/yolo/tfjs/yolo_uint8.tar.gz) |
| Faster RCNN | 44.0 | [bucket](https://storage.googleapis.com/cppe-5/trained_models/faster_rcnn/lite/model.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/faster_rcnn/lite/model_fp16.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/faster_rcnn/tfjs/faster_rcnn_tfjs.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/faster_rcnn/tfjs/faster_rcnn_fp16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/faster_rcnn/tfjs/faster_rcnn_uint16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/faster_rcnn/tfjs/faster_rcnn_uint8.tar.gz) |
| FCOS | 44.4 | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fcos/lite/model.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fcos/lite/model_f16.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fcos/tfjs/fcos_tfjs.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fcos/tfjs/fcos_fp16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fcos/tfjs/fcos_uint16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fcos/tfjs/fcos_uint8.tar.gz) |
| FSAF | 49.2 | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fsaf/lite/model.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fsaf/lite/model_f16.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fsaf/tfjs/fsaf_tfjs.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fsaf/tfjs/fsaf_fp16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fsaf/tfjs/fsaf_uint16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/fsaf/tfjs/fsaf_uint8.tar.gz) |
| RegNet | 51.3 | [bucket](https://storage.googleapis.com/cppe-5/trained_models/regnet/lite/model.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/regnet/lite/model_f16.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/regnet/tfjs/regnet_tfjs.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/regnet/tfjs/regnet_fp16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/regnet/tfjs/regnet_uint16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/regnet/tfjs/regnet_uint8.tar.gz) |
| TridentNet | 52.9 | [bucket](https://storage.googleapis.com/cppe-5/trained_models/tridentnet/lite/model.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/tridentnet/lite/model_f16.tflite) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/tridentnet/tfjs/tridentnet_tfjs.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/tridentnet/tfjs/tridentnet_fp16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/tridentnet/tfjs/tridentnet_uint16.tar.gz) | [bucket](https://storage.googleapis.com/cppe-5/trained_models/tridentnet/tfjs/tridentnet_uint8.tar.gz) |